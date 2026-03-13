# pulp-bindings-go

The following steps are based on https://github.com/content-services/zest

* get pulp api schema
```sh
curl https://packages.redhat.com/api/pulp/api/v3/docs/api.json > pulp_api.json

echo "$( jq '.components.schemas.TaskResponse.properties.error.additionalProperties.type = "string"' ./pulp_api.json )" > ./pulp_api.json
sed -i 's/\\n//g' pulp_api.json #remove \n characters that break generation

#https://github.com/OpenAPITools/openapi-generator/issues/18006
jq '(.components.schemas.ContentScan.properties[] | select(.format == "binary" and .nullable == true) | .nullable) = false' pulp_api.json > pulp_api_new.json
mv pulp_api_new.json pulp_api.json

# Remove nullable: true from all schema properties (this makes the NullableString/NullableInt64 definitions to become *string/*int)
jq 'walk(if type == "object" and .nullable == true then del(.nullable) else . end)'  pulp_api.json > pulp_api_new.json && mv pulp_api_new.json pulp_api.json

# Add "additionalProperties": false to the schema (fix the AdditionalProperties map[string]interface{} being created without the jsonschema)
jq '.components.schemas |= with_entries(
  if (.key | (endswith("Response") or endswith("ResponseList")))
  then .value.additionalProperties = false
  else .
  end
)' pulp_api.json > pulp_api_new.json
mv pulp_api_new.json pulp_api.json

# Add "additionalProperties": false to hidden_fields items (fix schema validation for remotes)
jq 'walk(if type == "object" and .hidden_fields? then .hidden_fields.items.additionalProperties = false else . end)' pulp_api.json > pulp_api_new.json
mv pulp_api_new.json pulp_api.json
```

* generate the bindings
```sh
GIT_USER_ID=git-hyagi
GIT_REPO_ID=pulp-bindings-go
PACKAGE_NAME=bindings
PACKAGE_VERSION="1.0"

podman run --rm -v ${PWD}:/local:z openapitools/openapi-generator-cli:latest-release generate \
  -i /local/pulp_api.json \
  -g go \
  -o /local/${PACKAGE_NAME} --minimal-update --skip-validate-spec \
  --git-user-id=${GIT_USER_ID} --git-repo-id=${GIT_REPO_ID}/${PACKAGE_NAME} \
  --package-name=${PACKAGE_NAME} -p enumClassPrefix=true  -p structPrefix=true \
  -p disallowAdditionalPropertiesIfNotPresent=false \
  -p packageVersion=${PACKAGE_VERSION} \
  --global-property skipFormModel=false,apiTests=false,modelTests=false
```
