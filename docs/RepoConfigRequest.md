# RepoConfigRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ExpectedVersion** | Pointer to **int64** |  | [optional] 
**Overrides** | **map[string]interface{}** |  | 

## Methods

### NewRepoConfigRequest

`func NewRepoConfigRequest(overrides map[string]interface{}, ) *RepoConfigRequest`

NewRepoConfigRequest instantiates a new RepoConfigRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRepoConfigRequestWithDefaults

`func NewRepoConfigRequestWithDefaults() *RepoConfigRequest`

NewRepoConfigRequestWithDefaults instantiates a new RepoConfigRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetExpectedVersion

`func (o *RepoConfigRequest) GetExpectedVersion() int64`

GetExpectedVersion returns the ExpectedVersion field if non-nil, zero value otherwise.

### GetExpectedVersionOk

`func (o *RepoConfigRequest) GetExpectedVersionOk() (*int64, bool)`

GetExpectedVersionOk returns a tuple with the ExpectedVersion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpectedVersion

`func (o *RepoConfigRequest) SetExpectedVersion(v int64)`

SetExpectedVersion sets ExpectedVersion field to given value.

### HasExpectedVersion

`func (o *RepoConfigRequest) HasExpectedVersion() bool`

HasExpectedVersion returns a boolean if a field has been set.

### GetOverrides

`func (o *RepoConfigRequest) GetOverrides() map[string]interface{}`

GetOverrides returns the Overrides field if non-nil, zero value otherwise.

### GetOverridesOk

`func (o *RepoConfigRequest) GetOverridesOk() (*map[string]interface{}, bool)`

GetOverridesOk returns a tuple with the Overrides field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOverrides

`func (o *RepoConfigRequest) SetOverrides(v map[string]interface{})`

SetOverrides sets Overrides field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


