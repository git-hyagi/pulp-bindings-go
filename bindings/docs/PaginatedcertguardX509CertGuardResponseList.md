# PaginatedcertguardX509CertGuardResponseList

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Count** | **int32** |  | 
**Next** | Pointer to **string** |  | [optional] 
**Previous** | Pointer to **string** |  | [optional] 
**Results** | [**[]CertguardX509CertGuardResponse**](CertguardX509CertGuardResponse.md) |  | 

## Methods

### NewPaginatedcertguardX509CertGuardResponseList

`func NewPaginatedcertguardX509CertGuardResponseList(count int32, results []CertguardX509CertGuardResponse, ) *PaginatedcertguardX509CertGuardResponseList`

NewPaginatedcertguardX509CertGuardResponseList instantiates a new PaginatedcertguardX509CertGuardResponseList object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPaginatedcertguardX509CertGuardResponseListWithDefaults

`func NewPaginatedcertguardX509CertGuardResponseListWithDefaults() *PaginatedcertguardX509CertGuardResponseList`

NewPaginatedcertguardX509CertGuardResponseListWithDefaults instantiates a new PaginatedcertguardX509CertGuardResponseList object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCount

`func (o *PaginatedcertguardX509CertGuardResponseList) GetCount() int32`

GetCount returns the Count field if non-nil, zero value otherwise.

### GetCountOk

`func (o *PaginatedcertguardX509CertGuardResponseList) GetCountOk() (*int32, bool)`

GetCountOk returns a tuple with the Count field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCount

`func (o *PaginatedcertguardX509CertGuardResponseList) SetCount(v int32)`

SetCount sets Count field to given value.


### GetNext

`func (o *PaginatedcertguardX509CertGuardResponseList) GetNext() string`

GetNext returns the Next field if non-nil, zero value otherwise.

### GetNextOk

`func (o *PaginatedcertguardX509CertGuardResponseList) GetNextOk() (*string, bool)`

GetNextOk returns a tuple with the Next field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNext

`func (o *PaginatedcertguardX509CertGuardResponseList) SetNext(v string)`

SetNext sets Next field to given value.

### HasNext

`func (o *PaginatedcertguardX509CertGuardResponseList) HasNext() bool`

HasNext returns a boolean if a field has been set.

### GetPrevious

`func (o *PaginatedcertguardX509CertGuardResponseList) GetPrevious() string`

GetPrevious returns the Previous field if non-nil, zero value otherwise.

### GetPreviousOk

`func (o *PaginatedcertguardX509CertGuardResponseList) GetPreviousOk() (*string, bool)`

GetPreviousOk returns a tuple with the Previous field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrevious

`func (o *PaginatedcertguardX509CertGuardResponseList) SetPrevious(v string)`

SetPrevious sets Previous field to given value.

### HasPrevious

`func (o *PaginatedcertguardX509CertGuardResponseList) HasPrevious() bool`

HasPrevious returns a boolean if a field has been set.

### GetResults

`func (o *PaginatedcertguardX509CertGuardResponseList) GetResults() []CertguardX509CertGuardResponse`

GetResults returns the Results field if non-nil, zero value otherwise.

### GetResultsOk

`func (o *PaginatedcertguardX509CertGuardResponseList) GetResultsOk() (*[]CertguardX509CertGuardResponse, bool)`

GetResultsOk returns a tuple with the Results field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResults

`func (o *PaginatedcertguardX509CertGuardResponseList) SetResults(v []CertguardX509CertGuardResponse)`

SetResults sets Results field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


