# DashboardRowResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Archived** | Pointer to **bool** |  | [optional] 
**InstallationRepoId** | Pointer to **int64** |  | [optional] 
**LastRunAt** | Pointer to **string** |  | [optional] 
**LastRunStatus** | Pointer to **string** |  | [optional] 
**RepoFullName** | Pointer to **string** |  | [optional] 
**RepoId** | Pointer to **int64** |  | [optional] 
**RunCount** | Pointer to **int32** |  | [optional] 
**SetupPrUrl** | Pointer to **string** |  | [optional] 
**Status** | Pointer to **string** |  | [optional] 
**StatusLabel** | Pointer to **string** |  | [optional] 
**WorkflowPresent** | Pointer to **bool** |  | [optional] 

## Methods

### NewDashboardRowResponse

`func NewDashboardRowResponse() *DashboardRowResponse`

NewDashboardRowResponse instantiates a new DashboardRowResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDashboardRowResponseWithDefaults

`func NewDashboardRowResponseWithDefaults() *DashboardRowResponse`

NewDashboardRowResponseWithDefaults instantiates a new DashboardRowResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetArchived

`func (o *DashboardRowResponse) GetArchived() bool`

GetArchived returns the Archived field if non-nil, zero value otherwise.

### GetArchivedOk

`func (o *DashboardRowResponse) GetArchivedOk() (*bool, bool)`

GetArchivedOk returns a tuple with the Archived field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArchived

`func (o *DashboardRowResponse) SetArchived(v bool)`

SetArchived sets Archived field to given value.

### HasArchived

`func (o *DashboardRowResponse) HasArchived() bool`

HasArchived returns a boolean if a field has been set.

### GetInstallationRepoId

`func (o *DashboardRowResponse) GetInstallationRepoId() int64`

GetInstallationRepoId returns the InstallationRepoId field if non-nil, zero value otherwise.

### GetInstallationRepoIdOk

`func (o *DashboardRowResponse) GetInstallationRepoIdOk() (*int64, bool)`

GetInstallationRepoIdOk returns a tuple with the InstallationRepoId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInstallationRepoId

`func (o *DashboardRowResponse) SetInstallationRepoId(v int64)`

SetInstallationRepoId sets InstallationRepoId field to given value.

### HasInstallationRepoId

`func (o *DashboardRowResponse) HasInstallationRepoId() bool`

HasInstallationRepoId returns a boolean if a field has been set.

### GetLastRunAt

`func (o *DashboardRowResponse) GetLastRunAt() string`

GetLastRunAt returns the LastRunAt field if non-nil, zero value otherwise.

### GetLastRunAtOk

`func (o *DashboardRowResponse) GetLastRunAtOk() (*string, bool)`

GetLastRunAtOk returns a tuple with the LastRunAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastRunAt

`func (o *DashboardRowResponse) SetLastRunAt(v string)`

SetLastRunAt sets LastRunAt field to given value.

### HasLastRunAt

`func (o *DashboardRowResponse) HasLastRunAt() bool`

HasLastRunAt returns a boolean if a field has been set.

### GetLastRunStatus

`func (o *DashboardRowResponse) GetLastRunStatus() string`

GetLastRunStatus returns the LastRunStatus field if non-nil, zero value otherwise.

### GetLastRunStatusOk

`func (o *DashboardRowResponse) GetLastRunStatusOk() (*string, bool)`

GetLastRunStatusOk returns a tuple with the LastRunStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastRunStatus

`func (o *DashboardRowResponse) SetLastRunStatus(v string)`

SetLastRunStatus sets LastRunStatus field to given value.

### HasLastRunStatus

`func (o *DashboardRowResponse) HasLastRunStatus() bool`

HasLastRunStatus returns a boolean if a field has been set.

### GetRepoFullName

`func (o *DashboardRowResponse) GetRepoFullName() string`

GetRepoFullName returns the RepoFullName field if non-nil, zero value otherwise.

### GetRepoFullNameOk

`func (o *DashboardRowResponse) GetRepoFullNameOk() (*string, bool)`

GetRepoFullNameOk returns a tuple with the RepoFullName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRepoFullName

`func (o *DashboardRowResponse) SetRepoFullName(v string)`

SetRepoFullName sets RepoFullName field to given value.

### HasRepoFullName

`func (o *DashboardRowResponse) HasRepoFullName() bool`

HasRepoFullName returns a boolean if a field has been set.

### GetRepoId

`func (o *DashboardRowResponse) GetRepoId() int64`

GetRepoId returns the RepoId field if non-nil, zero value otherwise.

### GetRepoIdOk

`func (o *DashboardRowResponse) GetRepoIdOk() (*int64, bool)`

GetRepoIdOk returns a tuple with the RepoId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRepoId

`func (o *DashboardRowResponse) SetRepoId(v int64)`

SetRepoId sets RepoId field to given value.

### HasRepoId

`func (o *DashboardRowResponse) HasRepoId() bool`

HasRepoId returns a boolean if a field has been set.

### GetRunCount

`func (o *DashboardRowResponse) GetRunCount() int32`

GetRunCount returns the RunCount field if non-nil, zero value otherwise.

### GetRunCountOk

`func (o *DashboardRowResponse) GetRunCountOk() (*int32, bool)`

GetRunCountOk returns a tuple with the RunCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRunCount

`func (o *DashboardRowResponse) SetRunCount(v int32)`

SetRunCount sets RunCount field to given value.

### HasRunCount

`func (o *DashboardRowResponse) HasRunCount() bool`

HasRunCount returns a boolean if a field has been set.

### GetSetupPrUrl

`func (o *DashboardRowResponse) GetSetupPrUrl() string`

GetSetupPrUrl returns the SetupPrUrl field if non-nil, zero value otherwise.

### GetSetupPrUrlOk

`func (o *DashboardRowResponse) GetSetupPrUrlOk() (*string, bool)`

GetSetupPrUrlOk returns a tuple with the SetupPrUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSetupPrUrl

`func (o *DashboardRowResponse) SetSetupPrUrl(v string)`

SetSetupPrUrl sets SetupPrUrl field to given value.

### HasSetupPrUrl

`func (o *DashboardRowResponse) HasSetupPrUrl() bool`

HasSetupPrUrl returns a boolean if a field has been set.

### GetStatus

`func (o *DashboardRowResponse) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *DashboardRowResponse) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *DashboardRowResponse) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *DashboardRowResponse) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetStatusLabel

`func (o *DashboardRowResponse) GetStatusLabel() string`

GetStatusLabel returns the StatusLabel field if non-nil, zero value otherwise.

### GetStatusLabelOk

`func (o *DashboardRowResponse) GetStatusLabelOk() (*string, bool)`

GetStatusLabelOk returns a tuple with the StatusLabel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatusLabel

`func (o *DashboardRowResponse) SetStatusLabel(v string)`

SetStatusLabel sets StatusLabel field to given value.

### HasStatusLabel

`func (o *DashboardRowResponse) HasStatusLabel() bool`

HasStatusLabel returns a boolean if a field has been set.

### GetWorkflowPresent

`func (o *DashboardRowResponse) GetWorkflowPresent() bool`

GetWorkflowPresent returns the WorkflowPresent field if non-nil, zero value otherwise.

### GetWorkflowPresentOk

`func (o *DashboardRowResponse) GetWorkflowPresentOk() (*bool, bool)`

GetWorkflowPresentOk returns a tuple with the WorkflowPresent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkflowPresent

`func (o *DashboardRowResponse) SetWorkflowPresent(v bool)`

SetWorkflowPresent sets WorkflowPresent field to given value.

### HasWorkflowPresent

`func (o *DashboardRowResponse) HasWorkflowPresent() bool`

HasWorkflowPresent returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


