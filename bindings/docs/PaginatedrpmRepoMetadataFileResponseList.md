# PaginatedrpmRepoMetadataFileResponseList

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Count** | **int32** |  | 
**Next** | Pointer to **string** |  | [optional] 
**Previous** | Pointer to **string** |  | [optional] 
**Results** | [**[]RpmRepoMetadataFileResponse**](RpmRepoMetadataFileResponse.md) |  | 

## Methods

### NewPaginatedrpmRepoMetadataFileResponseList

`func NewPaginatedrpmRepoMetadataFileResponseList(count int32, results []RpmRepoMetadataFileResponse, ) *PaginatedrpmRepoMetadataFileResponseList`

NewPaginatedrpmRepoMetadataFileResponseList instantiates a new PaginatedrpmRepoMetadataFileResponseList object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPaginatedrpmRepoMetadataFileResponseListWithDefaults

`func NewPaginatedrpmRepoMetadataFileResponseListWithDefaults() *PaginatedrpmRepoMetadataFileResponseList`

NewPaginatedrpmRepoMetadataFileResponseListWithDefaults instantiates a new PaginatedrpmRepoMetadataFileResponseList object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCount

`func (o *PaginatedrpmRepoMetadataFileResponseList) GetCount() int32`

GetCount returns the Count field if non-nil, zero value otherwise.

### GetCountOk

`func (o *PaginatedrpmRepoMetadataFileResponseList) GetCountOk() (*int32, bool)`

GetCountOk returns a tuple with the Count field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCount

`func (o *PaginatedrpmRepoMetadataFileResponseList) SetCount(v int32)`

SetCount sets Count field to given value.


### GetNext

`func (o *PaginatedrpmRepoMetadataFileResponseList) GetNext() string`

GetNext returns the Next field if non-nil, zero value otherwise.

### GetNextOk

`func (o *PaginatedrpmRepoMetadataFileResponseList) GetNextOk() (*string, bool)`

GetNextOk returns a tuple with the Next field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNext

`func (o *PaginatedrpmRepoMetadataFileResponseList) SetNext(v string)`

SetNext sets Next field to given value.

### HasNext

`func (o *PaginatedrpmRepoMetadataFileResponseList) HasNext() bool`

HasNext returns a boolean if a field has been set.

### GetPrevious

`func (o *PaginatedrpmRepoMetadataFileResponseList) GetPrevious() string`

GetPrevious returns the Previous field if non-nil, zero value otherwise.

### GetPreviousOk

`func (o *PaginatedrpmRepoMetadataFileResponseList) GetPreviousOk() (*string, bool)`

GetPreviousOk returns a tuple with the Previous field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrevious

`func (o *PaginatedrpmRepoMetadataFileResponseList) SetPrevious(v string)`

SetPrevious sets Previous field to given value.

### HasPrevious

`func (o *PaginatedrpmRepoMetadataFileResponseList) HasPrevious() bool`

HasPrevious returns a boolean if a field has been set.

### GetResults

`func (o *PaginatedrpmRepoMetadataFileResponseList) GetResults() []RpmRepoMetadataFileResponse`

GetResults returns the Results field if non-nil, zero value otherwise.

### GetResultsOk

`func (o *PaginatedrpmRepoMetadataFileResponseList) GetResultsOk() (*[]RpmRepoMetadataFileResponse, bool)`

GetResultsOk returns a tuple with the Results field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResults

`func (o *PaginatedrpmRepoMetadataFileResponseList) SetResults(v []RpmRepoMetadataFileResponse)`

SetResults sets Results field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


