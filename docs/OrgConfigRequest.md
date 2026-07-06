# OrgConfigRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Config** | **map[string]interface{}** |  | 
**DeveloperAccessEnabled** | Pointer to **bool** |  | [optional] 
**ExpectedVersion** | Pointer to **int64** |  | [optional] 

## Methods

### NewOrgConfigRequest

`func NewOrgConfigRequest(config map[string]interface{}, ) *OrgConfigRequest`

NewOrgConfigRequest instantiates a new OrgConfigRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOrgConfigRequestWithDefaults

`func NewOrgConfigRequestWithDefaults() *OrgConfigRequest`

NewOrgConfigRequestWithDefaults instantiates a new OrgConfigRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetConfig

`func (o *OrgConfigRequest) GetConfig() map[string]interface{}`

GetConfig returns the Config field if non-nil, zero value otherwise.

### GetConfigOk

`func (o *OrgConfigRequest) GetConfigOk() (*map[string]interface{}, bool)`

GetConfigOk returns a tuple with the Config field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfig

`func (o *OrgConfigRequest) SetConfig(v map[string]interface{})`

SetConfig sets Config field to given value.


### GetDeveloperAccessEnabled

`func (o *OrgConfigRequest) GetDeveloperAccessEnabled() bool`

GetDeveloperAccessEnabled returns the DeveloperAccessEnabled field if non-nil, zero value otherwise.

### GetDeveloperAccessEnabledOk

`func (o *OrgConfigRequest) GetDeveloperAccessEnabledOk() (*bool, bool)`

GetDeveloperAccessEnabledOk returns a tuple with the DeveloperAccessEnabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeveloperAccessEnabled

`func (o *OrgConfigRequest) SetDeveloperAccessEnabled(v bool)`

SetDeveloperAccessEnabled sets DeveloperAccessEnabled field to given value.

### HasDeveloperAccessEnabled

`func (o *OrgConfigRequest) HasDeveloperAccessEnabled() bool`

HasDeveloperAccessEnabled returns a boolean if a field has been set.

### GetExpectedVersion

`func (o *OrgConfigRequest) GetExpectedVersion() int64`

GetExpectedVersion returns the ExpectedVersion field if non-nil, zero value otherwise.

### GetExpectedVersionOk

`func (o *OrgConfigRequest) GetExpectedVersionOk() (*int64, bool)`

GetExpectedVersionOk returns a tuple with the ExpectedVersion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpectedVersion

`func (o *OrgConfigRequest) SetExpectedVersion(v int64)`

SetExpectedVersion sets ExpectedVersion field to given value.

### HasExpectedVersion

`func (o *OrgConfigRequest) HasExpectedVersion() bool`

HasExpectedVersion returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


