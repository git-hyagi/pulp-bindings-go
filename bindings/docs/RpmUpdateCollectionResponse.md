# RpmUpdateCollectionResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **string** | Collection name. | 
**Shortname** | **string** | Collection short name. | 
**Module** | **interface{}** | Collection modular NSVCA. | 
**Packages** | Pointer to **[]map[string]interface{}** | List of packages | [optional] [readonly] 

## Methods

### NewRpmUpdateCollectionResponse

`func NewRpmUpdateCollectionResponse(name string, shortname string, module interface{}, ) *RpmUpdateCollectionResponse`

NewRpmUpdateCollectionResponse instantiates a new RpmUpdateCollectionResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRpmUpdateCollectionResponseWithDefaults

`func NewRpmUpdateCollectionResponseWithDefaults() *RpmUpdateCollectionResponse`

NewRpmUpdateCollectionResponseWithDefaults instantiates a new RpmUpdateCollectionResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *RpmUpdateCollectionResponse) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *RpmUpdateCollectionResponse) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *RpmUpdateCollectionResponse) SetName(v string)`

SetName sets Name field to given value.


### GetShortname

`func (o *RpmUpdateCollectionResponse) GetShortname() string`

GetShortname returns the Shortname field if non-nil, zero value otherwise.

### GetShortnameOk

`func (o *RpmUpdateCollectionResponse) GetShortnameOk() (*string, bool)`

GetShortnameOk returns a tuple with the Shortname field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShortname

`func (o *RpmUpdateCollectionResponse) SetShortname(v string)`

SetShortname sets Shortname field to given value.


### GetModule

`func (o *RpmUpdateCollectionResponse) GetModule() interface{}`

GetModule returns the Module field if non-nil, zero value otherwise.

### GetModuleOk

`func (o *RpmUpdateCollectionResponse) GetModuleOk() (*interface{}, bool)`

GetModuleOk returns a tuple with the Module field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModule

`func (o *RpmUpdateCollectionResponse) SetModule(v interface{})`

SetModule sets Module field to given value.


### SetModuleNil

`func (o *RpmUpdateCollectionResponse) SetModuleNil(b bool)`

 SetModuleNil sets the value for Module to be an explicit nil

### UnsetModule
`func (o *RpmUpdateCollectionResponse) UnsetModule()`

UnsetModule ensures that no value is present for Module, not even an explicit nil
### GetPackages

`func (o *RpmUpdateCollectionResponse) GetPackages() []map[string]interface{}`

GetPackages returns the Packages field if non-nil, zero value otherwise.

### GetPackagesOk

`func (o *RpmUpdateCollectionResponse) GetPackagesOk() (*[]map[string]interface{}, bool)`

GetPackagesOk returns a tuple with the Packages field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPackages

`func (o *RpmUpdateCollectionResponse) SetPackages(v []map[string]interface{})`

SetPackages sets Packages field to given value.

### HasPackages

`func (o *RpmUpdateCollectionResponse) HasPackages() bool`

HasPackages returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


