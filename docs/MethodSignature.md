# MethodSignature

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Signature** | Pointer to **string** |  | [optional] 
**Type** | Pointer to **string** |  | [optional] 
**VulnerableParameters** | Pointer to **[]int32** |  | [optional] 

## Methods

### NewMethodSignature

`func NewMethodSignature() *MethodSignature`

NewMethodSignature instantiates a new MethodSignature object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewMethodSignatureWithDefaults

`func NewMethodSignatureWithDefaults() *MethodSignature`

NewMethodSignatureWithDefaults instantiates a new MethodSignature object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSignature

`func (o *MethodSignature) GetSignature() string`

GetSignature returns the Signature field if non-nil, zero value otherwise.

### GetSignatureOk

`func (o *MethodSignature) GetSignatureOk() (*string, bool)`

GetSignatureOk returns a tuple with the Signature field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSignature

`func (o *MethodSignature) SetSignature(v string)`

SetSignature sets Signature field to given value.

### HasSignature

`func (o *MethodSignature) HasSignature() bool`

HasSignature returns a boolean if a field has been set.

### GetType

`func (o *MethodSignature) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *MethodSignature) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *MethodSignature) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *MethodSignature) HasType() bool`

HasType returns a boolean if a field has been set.

### GetVulnerableParameters

`func (o *MethodSignature) GetVulnerableParameters() []int32`

GetVulnerableParameters returns the VulnerableParameters field if non-nil, zero value otherwise.

### GetVulnerableParametersOk

`func (o *MethodSignature) GetVulnerableParametersOk() (*[]int32, bool)`

GetVulnerableParametersOk returns a tuple with the VulnerableParameters field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVulnerableParameters

`func (o *MethodSignature) SetVulnerableParameters(v []int32)`

SetVulnerableParameters sets VulnerableParameters field to given value.

### HasVulnerableParameters

`func (o *MethodSignature) HasVulnerableParameters() bool`

HasVulnerableParameters returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


