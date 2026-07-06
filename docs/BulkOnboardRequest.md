# BulkOnboardRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**InstallationRepoIds** | **[]int64** |  | 
**Merge** | Pointer to **bool** |  | [optional] 

## Methods

### NewBulkOnboardRequest

`func NewBulkOnboardRequest(installationRepoIds []int64, ) *BulkOnboardRequest`

NewBulkOnboardRequest instantiates a new BulkOnboardRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBulkOnboardRequestWithDefaults

`func NewBulkOnboardRequestWithDefaults() *BulkOnboardRequest`

NewBulkOnboardRequestWithDefaults instantiates a new BulkOnboardRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetInstallationRepoIds

`func (o *BulkOnboardRequest) GetInstallationRepoIds() []int64`

GetInstallationRepoIds returns the InstallationRepoIds field if non-nil, zero value otherwise.

### GetInstallationRepoIdsOk

`func (o *BulkOnboardRequest) GetInstallationRepoIdsOk() (*[]int64, bool)`

GetInstallationRepoIdsOk returns a tuple with the InstallationRepoIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInstallationRepoIds

`func (o *BulkOnboardRequest) SetInstallationRepoIds(v []int64)`

SetInstallationRepoIds sets InstallationRepoIds field to given value.


### GetMerge

`func (o *BulkOnboardRequest) GetMerge() bool`

GetMerge returns the Merge field if non-nil, zero value otherwise.

### GetMergeOk

`func (o *BulkOnboardRequest) GetMergeOk() (*bool, bool)`

GetMergeOk returns a tuple with the Merge field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMerge

`func (o *BulkOnboardRequest) SetMerge(v bool)`

SetMerge sets Merge field to given value.

### HasMerge

`func (o *BulkOnboardRequest) HasMerge() bool`

HasMerge returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


