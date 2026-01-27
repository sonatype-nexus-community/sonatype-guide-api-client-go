# CreateTokenRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DaysUntilExpiration** | **int32** |  | 
**Name** | **string** |  | 

## Methods

### NewCreateTokenRequest

`func NewCreateTokenRequest(daysUntilExpiration int32, name string, ) *CreateTokenRequest`

NewCreateTokenRequest instantiates a new CreateTokenRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateTokenRequestWithDefaults

`func NewCreateTokenRequestWithDefaults() *CreateTokenRequest`

NewCreateTokenRequestWithDefaults instantiates a new CreateTokenRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDaysUntilExpiration

`func (o *CreateTokenRequest) GetDaysUntilExpiration() int32`

GetDaysUntilExpiration returns the DaysUntilExpiration field if non-nil, zero value otherwise.

### GetDaysUntilExpirationOk

`func (o *CreateTokenRequest) GetDaysUntilExpirationOk() (*int32, bool)`

GetDaysUntilExpirationOk returns a tuple with the DaysUntilExpiration field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDaysUntilExpiration

`func (o *CreateTokenRequest) SetDaysUntilExpiration(v int32)`

SetDaysUntilExpiration sets DaysUntilExpiration field to given value.


### GetName

`func (o *CreateTokenRequest) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CreateTokenRequest) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CreateTokenRequest) SetName(v string)`

SetName sets Name field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


