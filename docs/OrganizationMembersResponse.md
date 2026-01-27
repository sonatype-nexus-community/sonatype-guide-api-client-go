# OrganizationMembersResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Avatar** | Pointer to **string** |  | [optional] 
**Email** | Pointer to **string** |  | [optional] 
**InvitedHistory** | Pointer to [**[]time.Time**](time.Time.md) |  | [optional] 
**JoinedAt** | Pointer to **time.Time** |  | [optional] 
**LastActive** | Pointer to **time.Time** |  | [optional] 
**Name** | Pointer to **string** |  | [optional] 
**Role** | Pointer to **string** |  | [optional] 
**Status** | Pointer to **string** |  | [optional] 

## Methods

### NewOrganizationMembersResponse

`func NewOrganizationMembersResponse() *OrganizationMembersResponse`

NewOrganizationMembersResponse instantiates a new OrganizationMembersResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOrganizationMembersResponseWithDefaults

`func NewOrganizationMembersResponseWithDefaults() *OrganizationMembersResponse`

NewOrganizationMembersResponseWithDefaults instantiates a new OrganizationMembersResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAvatar

`func (o *OrganizationMembersResponse) GetAvatar() string`

GetAvatar returns the Avatar field if non-nil, zero value otherwise.

### GetAvatarOk

`func (o *OrganizationMembersResponse) GetAvatarOk() (*string, bool)`

GetAvatarOk returns a tuple with the Avatar field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvatar

`func (o *OrganizationMembersResponse) SetAvatar(v string)`

SetAvatar sets Avatar field to given value.

### HasAvatar

`func (o *OrganizationMembersResponse) HasAvatar() bool`

HasAvatar returns a boolean if a field has been set.

### GetEmail

`func (o *OrganizationMembersResponse) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *OrganizationMembersResponse) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *OrganizationMembersResponse) SetEmail(v string)`

SetEmail sets Email field to given value.

### HasEmail

`func (o *OrganizationMembersResponse) HasEmail() bool`

HasEmail returns a boolean if a field has been set.

### GetInvitedHistory

`func (o *OrganizationMembersResponse) GetInvitedHistory() []time.Time`

GetInvitedHistory returns the InvitedHistory field if non-nil, zero value otherwise.

### GetInvitedHistoryOk

`func (o *OrganizationMembersResponse) GetInvitedHistoryOk() (*[]time.Time, bool)`

GetInvitedHistoryOk returns a tuple with the InvitedHistory field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvitedHistory

`func (o *OrganizationMembersResponse) SetInvitedHistory(v []time.Time)`

SetInvitedHistory sets InvitedHistory field to given value.

### HasInvitedHistory

`func (o *OrganizationMembersResponse) HasInvitedHistory() bool`

HasInvitedHistory returns a boolean if a field has been set.

### GetJoinedAt

`func (o *OrganizationMembersResponse) GetJoinedAt() time.Time`

GetJoinedAt returns the JoinedAt field if non-nil, zero value otherwise.

### GetJoinedAtOk

`func (o *OrganizationMembersResponse) GetJoinedAtOk() (*time.Time, bool)`

GetJoinedAtOk returns a tuple with the JoinedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJoinedAt

`func (o *OrganizationMembersResponse) SetJoinedAt(v time.Time)`

SetJoinedAt sets JoinedAt field to given value.

### HasJoinedAt

`func (o *OrganizationMembersResponse) HasJoinedAt() bool`

HasJoinedAt returns a boolean if a field has been set.

### GetLastActive

`func (o *OrganizationMembersResponse) GetLastActive() time.Time`

GetLastActive returns the LastActive field if non-nil, zero value otherwise.

### GetLastActiveOk

`func (o *OrganizationMembersResponse) GetLastActiveOk() (*time.Time, bool)`

GetLastActiveOk returns a tuple with the LastActive field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastActive

`func (o *OrganizationMembersResponse) SetLastActive(v time.Time)`

SetLastActive sets LastActive field to given value.

### HasLastActive

`func (o *OrganizationMembersResponse) HasLastActive() bool`

HasLastActive returns a boolean if a field has been set.

### GetName

`func (o *OrganizationMembersResponse) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *OrganizationMembersResponse) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *OrganizationMembersResponse) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *OrganizationMembersResponse) HasName() bool`

HasName returns a boolean if a field has been set.

### GetRole

`func (o *OrganizationMembersResponse) GetRole() string`

GetRole returns the Role field if non-nil, zero value otherwise.

### GetRoleOk

`func (o *OrganizationMembersResponse) GetRoleOk() (*string, bool)`

GetRoleOk returns a tuple with the Role field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRole

`func (o *OrganizationMembersResponse) SetRole(v string)`

SetRole sets Role field to given value.

### HasRole

`func (o *OrganizationMembersResponse) HasRole() bool`

HasRole returns a boolean if a field has been set.

### GetStatus

`func (o *OrganizationMembersResponse) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *OrganizationMembersResponse) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *OrganizationMembersResponse) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *OrganizationMembersResponse) HasStatus() bool`

HasStatus returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


