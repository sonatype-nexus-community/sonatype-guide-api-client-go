# UserTokenWithPlaintextDTO

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**PlaintextToken** | Pointer to **string** |  | [optional] 
**TokenDTO** | Pointer to [**UserTokenDTO**](UserTokenDTO.md) |  | [optional] 

## Methods

### NewUserTokenWithPlaintextDTO

`func NewUserTokenWithPlaintextDTO() *UserTokenWithPlaintextDTO`

NewUserTokenWithPlaintextDTO instantiates a new UserTokenWithPlaintextDTO object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUserTokenWithPlaintextDTOWithDefaults

`func NewUserTokenWithPlaintextDTOWithDefaults() *UserTokenWithPlaintextDTO`

NewUserTokenWithPlaintextDTOWithDefaults instantiates a new UserTokenWithPlaintextDTO object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPlaintextToken

`func (o *UserTokenWithPlaintextDTO) GetPlaintextToken() string`

GetPlaintextToken returns the PlaintextToken field if non-nil, zero value otherwise.

### GetPlaintextTokenOk

`func (o *UserTokenWithPlaintextDTO) GetPlaintextTokenOk() (*string, bool)`

GetPlaintextTokenOk returns a tuple with the PlaintextToken field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlaintextToken

`func (o *UserTokenWithPlaintextDTO) SetPlaintextToken(v string)`

SetPlaintextToken sets PlaintextToken field to given value.

### HasPlaintextToken

`func (o *UserTokenWithPlaintextDTO) HasPlaintextToken() bool`

HasPlaintextToken returns a boolean if a field has been set.

### GetTokenDTO

`func (o *UserTokenWithPlaintextDTO) GetTokenDTO() UserTokenDTO`

GetTokenDTO returns the TokenDTO field if non-nil, zero value otherwise.

### GetTokenDTOOk

`func (o *UserTokenWithPlaintextDTO) GetTokenDTOOk() (*UserTokenDTO, bool)`

GetTokenDTOOk returns a tuple with the TokenDTO field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTokenDTO

`func (o *UserTokenWithPlaintextDTO) SetTokenDTO(v UserTokenDTO)`

SetTokenDTO sets TokenDTO field to given value.

### HasTokenDTO

`func (o *UserTokenWithPlaintextDTO) HasTokenDTO() bool`

HasTokenDTO returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


