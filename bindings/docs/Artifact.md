# Artifact

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**File** | ***os.File** | The stored file. | 
**Size** | Pointer to **int64** | The size of the file in bytes. | [optional] 
**Md5** | Pointer to **string** | The MD5 checksum of the file if available. | [optional] 
**Sha1** | Pointer to **string** | The SHA-1 checksum of the file if available. | [optional] 
**Sha224** | Pointer to **string** | The SHA-224 checksum of the file if available. | [optional] 
**Sha256** | Pointer to **string** | The SHA-256 checksum of the file if available. | [optional] 
**Sha384** | Pointer to **string** | The SHA-384 checksum of the file if available. | [optional] 
**Sha512** | Pointer to **string** | The SHA-512 checksum of the file if available. | [optional] 

## Methods

### NewArtifact

`func NewArtifact(file *os.File, ) *Artifact`

NewArtifact instantiates a new Artifact object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewArtifactWithDefaults

`func NewArtifactWithDefaults() *Artifact`

NewArtifactWithDefaults instantiates a new Artifact object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetFile

`func (o *Artifact) GetFile() *os.File`

GetFile returns the File field if non-nil, zero value otherwise.

### GetFileOk

`func (o *Artifact) GetFileOk() (**os.File, bool)`

GetFileOk returns a tuple with the File field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFile

`func (o *Artifact) SetFile(v *os.File)`

SetFile sets File field to given value.


### GetSize

`func (o *Artifact) GetSize() int64`

GetSize returns the Size field if non-nil, zero value otherwise.

### GetSizeOk

`func (o *Artifact) GetSizeOk() (*int64, bool)`

GetSizeOk returns a tuple with the Size field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSize

`func (o *Artifact) SetSize(v int64)`

SetSize sets Size field to given value.

### HasSize

`func (o *Artifact) HasSize() bool`

HasSize returns a boolean if a field has been set.

### GetMd5

`func (o *Artifact) GetMd5() string`

GetMd5 returns the Md5 field if non-nil, zero value otherwise.

### GetMd5Ok

`func (o *Artifact) GetMd5Ok() (*string, bool)`

GetMd5Ok returns a tuple with the Md5 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMd5

`func (o *Artifact) SetMd5(v string)`

SetMd5 sets Md5 field to given value.

### HasMd5

`func (o *Artifact) HasMd5() bool`

HasMd5 returns a boolean if a field has been set.

### GetSha1

`func (o *Artifact) GetSha1() string`

GetSha1 returns the Sha1 field if non-nil, zero value otherwise.

### GetSha1Ok

`func (o *Artifact) GetSha1Ok() (*string, bool)`

GetSha1Ok returns a tuple with the Sha1 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSha1

`func (o *Artifact) SetSha1(v string)`

SetSha1 sets Sha1 field to given value.

### HasSha1

`func (o *Artifact) HasSha1() bool`

HasSha1 returns a boolean if a field has been set.

### GetSha224

`func (o *Artifact) GetSha224() string`

GetSha224 returns the Sha224 field if non-nil, zero value otherwise.

### GetSha224Ok

`func (o *Artifact) GetSha224Ok() (*string, bool)`

GetSha224Ok returns a tuple with the Sha224 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSha224

`func (o *Artifact) SetSha224(v string)`

SetSha224 sets Sha224 field to given value.

### HasSha224

`func (o *Artifact) HasSha224() bool`

HasSha224 returns a boolean if a field has been set.

### GetSha256

`func (o *Artifact) GetSha256() string`

GetSha256 returns the Sha256 field if non-nil, zero value otherwise.

### GetSha256Ok

`func (o *Artifact) GetSha256Ok() (*string, bool)`

GetSha256Ok returns a tuple with the Sha256 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSha256

`func (o *Artifact) SetSha256(v string)`

SetSha256 sets Sha256 field to given value.

### HasSha256

`func (o *Artifact) HasSha256() bool`

HasSha256 returns a boolean if a field has been set.

### GetSha384

`func (o *Artifact) GetSha384() string`

GetSha384 returns the Sha384 field if non-nil, zero value otherwise.

### GetSha384Ok

`func (o *Artifact) GetSha384Ok() (*string, bool)`

GetSha384Ok returns a tuple with the Sha384 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSha384

`func (o *Artifact) SetSha384(v string)`

SetSha384 sets Sha384 field to given value.

### HasSha384

`func (o *Artifact) HasSha384() bool`

HasSha384 returns a boolean if a field has been set.

### GetSha512

`func (o *Artifact) GetSha512() string`

GetSha512 returns the Sha512 field if non-nil, zero value otherwise.

### GetSha512Ok

`func (o *Artifact) GetSha512Ok() (*string, bool)`

GetSha512Ok returns a tuple with the Sha512 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSha512

`func (o *Artifact) SetSha512(v string)`

SetSha512 sets Sha512 field to given value.

### HasSha512

`func (o *Artifact) HasSha512() bool`

HasSha512 returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


