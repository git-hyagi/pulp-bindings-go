# PaginatedcontainerContainerPullThroughDistributionResponseList

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Count** | **int32** |  | 
**Next** | Pointer to **string** |  | [optional] 
**Previous** | Pointer to **string** |  | [optional] 
**Results** | [**[]ContainerContainerPullThroughDistributionResponse**](ContainerContainerPullThroughDistributionResponse.md) |  | 

## Methods

### NewPaginatedcontainerContainerPullThroughDistributionResponseList

`func NewPaginatedcontainerContainerPullThroughDistributionResponseList(count int32, results []ContainerContainerPullThroughDistributionResponse, ) *PaginatedcontainerContainerPullThroughDistributionResponseList`

NewPaginatedcontainerContainerPullThroughDistributionResponseList instantiates a new PaginatedcontainerContainerPullThroughDistributionResponseList object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPaginatedcontainerContainerPullThroughDistributionResponseListWithDefaults

`func NewPaginatedcontainerContainerPullThroughDistributionResponseListWithDefaults() *PaginatedcontainerContainerPullThroughDistributionResponseList`

NewPaginatedcontainerContainerPullThroughDistributionResponseListWithDefaults instantiates a new PaginatedcontainerContainerPullThroughDistributionResponseList object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCount

`func (o *PaginatedcontainerContainerPullThroughDistributionResponseList) GetCount() int32`

GetCount returns the Count field if non-nil, zero value otherwise.

### GetCountOk

`func (o *PaginatedcontainerContainerPullThroughDistributionResponseList) GetCountOk() (*int32, bool)`

GetCountOk returns a tuple with the Count field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCount

`func (o *PaginatedcontainerContainerPullThroughDistributionResponseList) SetCount(v int32)`

SetCount sets Count field to given value.


### GetNext

`func (o *PaginatedcontainerContainerPullThroughDistributionResponseList) GetNext() string`

GetNext returns the Next field if non-nil, zero value otherwise.

### GetNextOk

`func (o *PaginatedcontainerContainerPullThroughDistributionResponseList) GetNextOk() (*string, bool)`

GetNextOk returns a tuple with the Next field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNext

`func (o *PaginatedcontainerContainerPullThroughDistributionResponseList) SetNext(v string)`

SetNext sets Next field to given value.

### HasNext

`func (o *PaginatedcontainerContainerPullThroughDistributionResponseList) HasNext() bool`

HasNext returns a boolean if a field has been set.

### GetPrevious

`func (o *PaginatedcontainerContainerPullThroughDistributionResponseList) GetPrevious() string`

GetPrevious returns the Previous field if non-nil, zero value otherwise.

### GetPreviousOk

`func (o *PaginatedcontainerContainerPullThroughDistributionResponseList) GetPreviousOk() (*string, bool)`

GetPreviousOk returns a tuple with the Previous field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrevious

`func (o *PaginatedcontainerContainerPullThroughDistributionResponseList) SetPrevious(v string)`

SetPrevious sets Previous field to given value.

### HasPrevious

`func (o *PaginatedcontainerContainerPullThroughDistributionResponseList) HasPrevious() bool`

HasPrevious returns a boolean if a field has been set.

### GetResults

`func (o *PaginatedcontainerContainerPullThroughDistributionResponseList) GetResults() []ContainerContainerPullThroughDistributionResponse`

GetResults returns the Results field if non-nil, zero value otherwise.

### GetResultsOk

`func (o *PaginatedcontainerContainerPullThroughDistributionResponseList) GetResultsOk() (*[]ContainerContainerPullThroughDistributionResponse, bool)`

GetResultsOk returns a tuple with the Results field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResults

`func (o *PaginatedcontainerContainerPullThroughDistributionResponseList) SetResults(v []ContainerContainerPullThroughDistributionResponse)`

SetResults sets Results field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


