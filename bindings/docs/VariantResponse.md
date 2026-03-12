# VariantResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**VariantId** | **string** | Variant id. | 
**Uid** | **string** | Variant uid. | 
**Name** | **string** | Variant name. | 
**Type** | **string** | Variant type. | 
**Packages** | **string** | Relative path to directory with binary RPMs. | 
**SourcePackages** | **string** | Relative path to directory with source RPMs. | 
**SourceRepository** | **string** | Relative path to YUM repository with source RPMs. | 
**DebugPackages** | **string** | Relative path to directory with debug RPMs. | 
**DebugRepository** | **string** | Relative path to YUM repository with debug RPMs. | 
**Identity** | **string** | Relative path to a pem file that identifies a product. | 

## Methods

### NewVariantResponse

`func NewVariantResponse(variantId string, uid string, name string, type_ string, packages string, sourcePackages string, sourceRepository string, debugPackages string, debugRepository string, identity string, ) *VariantResponse`

NewVariantResponse instantiates a new VariantResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewVariantResponseWithDefaults

`func NewVariantResponseWithDefaults() *VariantResponse`

NewVariantResponseWithDefaults instantiates a new VariantResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetVariantId

`func (o *VariantResponse) GetVariantId() string`

GetVariantId returns the VariantId field if non-nil, zero value otherwise.

### GetVariantIdOk

`func (o *VariantResponse) GetVariantIdOk() (*string, bool)`

GetVariantIdOk returns a tuple with the VariantId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVariantId

`func (o *VariantResponse) SetVariantId(v string)`

SetVariantId sets VariantId field to given value.


### GetUid

`func (o *VariantResponse) GetUid() string`

GetUid returns the Uid field if non-nil, zero value otherwise.

### GetUidOk

`func (o *VariantResponse) GetUidOk() (*string, bool)`

GetUidOk returns a tuple with the Uid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUid

`func (o *VariantResponse) SetUid(v string)`

SetUid sets Uid field to given value.


### GetName

`func (o *VariantResponse) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *VariantResponse) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *VariantResponse) SetName(v string)`

SetName sets Name field to given value.


### GetType

`func (o *VariantResponse) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *VariantResponse) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *VariantResponse) SetType(v string)`

SetType sets Type field to given value.


### GetPackages

`func (o *VariantResponse) GetPackages() string`

GetPackages returns the Packages field if non-nil, zero value otherwise.

### GetPackagesOk

`func (o *VariantResponse) GetPackagesOk() (*string, bool)`

GetPackagesOk returns a tuple with the Packages field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPackages

`func (o *VariantResponse) SetPackages(v string)`

SetPackages sets Packages field to given value.


### GetSourcePackages

`func (o *VariantResponse) GetSourcePackages() string`

GetSourcePackages returns the SourcePackages field if non-nil, zero value otherwise.

### GetSourcePackagesOk

`func (o *VariantResponse) GetSourcePackagesOk() (*string, bool)`

GetSourcePackagesOk returns a tuple with the SourcePackages field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourcePackages

`func (o *VariantResponse) SetSourcePackages(v string)`

SetSourcePackages sets SourcePackages field to given value.


### GetSourceRepository

`func (o *VariantResponse) GetSourceRepository() string`

GetSourceRepository returns the SourceRepository field if non-nil, zero value otherwise.

### GetSourceRepositoryOk

`func (o *VariantResponse) GetSourceRepositoryOk() (*string, bool)`

GetSourceRepositoryOk returns a tuple with the SourceRepository field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceRepository

`func (o *VariantResponse) SetSourceRepository(v string)`

SetSourceRepository sets SourceRepository field to given value.


### GetDebugPackages

`func (o *VariantResponse) GetDebugPackages() string`

GetDebugPackages returns the DebugPackages field if non-nil, zero value otherwise.

### GetDebugPackagesOk

`func (o *VariantResponse) GetDebugPackagesOk() (*string, bool)`

GetDebugPackagesOk returns a tuple with the DebugPackages field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDebugPackages

`func (o *VariantResponse) SetDebugPackages(v string)`

SetDebugPackages sets DebugPackages field to given value.


### GetDebugRepository

`func (o *VariantResponse) GetDebugRepository() string`

GetDebugRepository returns the DebugRepository field if non-nil, zero value otherwise.

### GetDebugRepositoryOk

`func (o *VariantResponse) GetDebugRepositoryOk() (*string, bool)`

GetDebugRepositoryOk returns a tuple with the DebugRepository field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDebugRepository

`func (o *VariantResponse) SetDebugRepository(v string)`

SetDebugRepository sets DebugRepository field to given value.


### GetIdentity

`func (o *VariantResponse) GetIdentity() string`

GetIdentity returns the Identity field if non-nil, zero value otherwise.

### GetIdentityOk

`func (o *VariantResponse) GetIdentityOk() (*string, bool)`

GetIdentityOk returns a tuple with the Identity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdentity

`func (o *VariantResponse) SetIdentity(v string)`

SetIdentity sets Identity field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


