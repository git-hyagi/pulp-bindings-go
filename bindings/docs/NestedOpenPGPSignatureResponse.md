# NestedOpenPGPSignatureResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Issuer** | Pointer to **string** |  | [optional] 
**Created** | **time.Time** |  | 
**ExpirationTime** | Pointer to **string** |  | [optional] 
**SignersUserId** | Pointer to **string** |  | [optional] 
**KeyExpirationTime** | Pointer to **string** |  | [optional] 
**Expired** | **bool** |  | 
**KeyExpired** | Pointer to **string** |  | [optional] [readonly] 

## Methods

### NewNestedOpenPGPSignatureResponse

`func NewNestedOpenPGPSignatureResponse(created time.Time, expired bool, ) *NestedOpenPGPSignatureResponse`

NewNestedOpenPGPSignatureResponse instantiates a new NestedOpenPGPSignatureResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewNestedOpenPGPSignatureResponseWithDefaults

`func NewNestedOpenPGPSignatureResponseWithDefaults() *NestedOpenPGPSignatureResponse`

NewNestedOpenPGPSignatureResponseWithDefaults instantiates a new NestedOpenPGPSignatureResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIssuer

`func (o *NestedOpenPGPSignatureResponse) GetIssuer() string`

GetIssuer returns the Issuer field if non-nil, zero value otherwise.

### GetIssuerOk

`func (o *NestedOpenPGPSignatureResponse) GetIssuerOk() (*string, bool)`

GetIssuerOk returns a tuple with the Issuer field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIssuer

`func (o *NestedOpenPGPSignatureResponse) SetIssuer(v string)`

SetIssuer sets Issuer field to given value.

### HasIssuer

`func (o *NestedOpenPGPSignatureResponse) HasIssuer() bool`

HasIssuer returns a boolean if a field has been set.

### GetCreated

`func (o *NestedOpenPGPSignatureResponse) GetCreated() time.Time`

GetCreated returns the Created field if non-nil, zero value otherwise.

### GetCreatedOk

`func (o *NestedOpenPGPSignatureResponse) GetCreatedOk() (*time.Time, bool)`

GetCreatedOk returns a tuple with the Created field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreated

`func (o *NestedOpenPGPSignatureResponse) SetCreated(v time.Time)`

SetCreated sets Created field to given value.


### GetExpirationTime

`func (o *NestedOpenPGPSignatureResponse) GetExpirationTime() string`

GetExpirationTime returns the ExpirationTime field if non-nil, zero value otherwise.

### GetExpirationTimeOk

`func (o *NestedOpenPGPSignatureResponse) GetExpirationTimeOk() (*string, bool)`

GetExpirationTimeOk returns a tuple with the ExpirationTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpirationTime

`func (o *NestedOpenPGPSignatureResponse) SetExpirationTime(v string)`

SetExpirationTime sets ExpirationTime field to given value.

### HasExpirationTime

`func (o *NestedOpenPGPSignatureResponse) HasExpirationTime() bool`

HasExpirationTime returns a boolean if a field has been set.

### GetSignersUserId

`func (o *NestedOpenPGPSignatureResponse) GetSignersUserId() string`

GetSignersUserId returns the SignersUserId field if non-nil, zero value otherwise.

### GetSignersUserIdOk

`func (o *NestedOpenPGPSignatureResponse) GetSignersUserIdOk() (*string, bool)`

GetSignersUserIdOk returns a tuple with the SignersUserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSignersUserId

`func (o *NestedOpenPGPSignatureResponse) SetSignersUserId(v string)`

SetSignersUserId sets SignersUserId field to given value.

### HasSignersUserId

`func (o *NestedOpenPGPSignatureResponse) HasSignersUserId() bool`

HasSignersUserId returns a boolean if a field has been set.

### GetKeyExpirationTime

`func (o *NestedOpenPGPSignatureResponse) GetKeyExpirationTime() string`

GetKeyExpirationTime returns the KeyExpirationTime field if non-nil, zero value otherwise.

### GetKeyExpirationTimeOk

`func (o *NestedOpenPGPSignatureResponse) GetKeyExpirationTimeOk() (*string, bool)`

GetKeyExpirationTimeOk returns a tuple with the KeyExpirationTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKeyExpirationTime

`func (o *NestedOpenPGPSignatureResponse) SetKeyExpirationTime(v string)`

SetKeyExpirationTime sets KeyExpirationTime field to given value.

### HasKeyExpirationTime

`func (o *NestedOpenPGPSignatureResponse) HasKeyExpirationTime() bool`

HasKeyExpirationTime returns a boolean if a field has been set.

### GetExpired

`func (o *NestedOpenPGPSignatureResponse) GetExpired() bool`

GetExpired returns the Expired field if non-nil, zero value otherwise.

### GetExpiredOk

`func (o *NestedOpenPGPSignatureResponse) GetExpiredOk() (*bool, bool)`

GetExpiredOk returns a tuple with the Expired field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpired

`func (o *NestedOpenPGPSignatureResponse) SetExpired(v bool)`

SetExpired sets Expired field to given value.


### GetKeyExpired

`func (o *NestedOpenPGPSignatureResponse) GetKeyExpired() string`

GetKeyExpired returns the KeyExpired field if non-nil, zero value otherwise.

### GetKeyExpiredOk

`func (o *NestedOpenPGPSignatureResponse) GetKeyExpiredOk() (*string, bool)`

GetKeyExpiredOk returns a tuple with the KeyExpired field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKeyExpired

`func (o *NestedOpenPGPSignatureResponse) SetKeyExpired(v string)`

SetKeyExpired sets KeyExpired field to given value.

### HasKeyExpired

`func (o *NestedOpenPGPSignatureResponse) HasKeyExpired() bool`

HasKeyExpired returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


