# OrgActivityLogEntry

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ActorChannel** | Pointer to **string** |  | [optional] 
**ActorName** | Pointer to **string** |  | [optional] 
**CreatedAt** | Pointer to **time.Time** |  | [optional] 
**Details** | Pointer to **map[string]interface{}** |  | [optional] 
**EventCategory** | Pointer to **string** |  | [optional] 
**EventLabel** | Pointer to **string** |  | [optional] 
**EventType** | Pointer to **string** |  | [optional] 

## Methods

### NewOrgActivityLogEntry

`func NewOrgActivityLogEntry() *OrgActivityLogEntry`

NewOrgActivityLogEntry instantiates a new OrgActivityLogEntry object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOrgActivityLogEntryWithDefaults

`func NewOrgActivityLogEntryWithDefaults() *OrgActivityLogEntry`

NewOrgActivityLogEntryWithDefaults instantiates a new OrgActivityLogEntry object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetActorChannel

`func (o *OrgActivityLogEntry) GetActorChannel() string`

GetActorChannel returns the ActorChannel field if non-nil, zero value otherwise.

### GetActorChannelOk

`func (o *OrgActivityLogEntry) GetActorChannelOk() (*string, bool)`

GetActorChannelOk returns a tuple with the ActorChannel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActorChannel

`func (o *OrgActivityLogEntry) SetActorChannel(v string)`

SetActorChannel sets ActorChannel field to given value.

### HasActorChannel

`func (o *OrgActivityLogEntry) HasActorChannel() bool`

HasActorChannel returns a boolean if a field has been set.

### GetActorName

`func (o *OrgActivityLogEntry) GetActorName() string`

GetActorName returns the ActorName field if non-nil, zero value otherwise.

### GetActorNameOk

`func (o *OrgActivityLogEntry) GetActorNameOk() (*string, bool)`

GetActorNameOk returns a tuple with the ActorName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActorName

`func (o *OrgActivityLogEntry) SetActorName(v string)`

SetActorName sets ActorName field to given value.

### HasActorName

`func (o *OrgActivityLogEntry) HasActorName() bool`

HasActorName returns a boolean if a field has been set.

### GetCreatedAt

`func (o *OrgActivityLogEntry) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *OrgActivityLogEntry) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *OrgActivityLogEntry) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *OrgActivityLogEntry) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetDetails

`func (o *OrgActivityLogEntry) GetDetails() map[string]interface{}`

GetDetails returns the Details field if non-nil, zero value otherwise.

### GetDetailsOk

`func (o *OrgActivityLogEntry) GetDetailsOk() (*map[string]interface{}, bool)`

GetDetailsOk returns a tuple with the Details field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDetails

`func (o *OrgActivityLogEntry) SetDetails(v map[string]interface{})`

SetDetails sets Details field to given value.

### HasDetails

`func (o *OrgActivityLogEntry) HasDetails() bool`

HasDetails returns a boolean if a field has been set.

### GetEventCategory

`func (o *OrgActivityLogEntry) GetEventCategory() string`

GetEventCategory returns the EventCategory field if non-nil, zero value otherwise.

### GetEventCategoryOk

`func (o *OrgActivityLogEntry) GetEventCategoryOk() (*string, bool)`

GetEventCategoryOk returns a tuple with the EventCategory field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEventCategory

`func (o *OrgActivityLogEntry) SetEventCategory(v string)`

SetEventCategory sets EventCategory field to given value.

### HasEventCategory

`func (o *OrgActivityLogEntry) HasEventCategory() bool`

HasEventCategory returns a boolean if a field has been set.

### GetEventLabel

`func (o *OrgActivityLogEntry) GetEventLabel() string`

GetEventLabel returns the EventLabel field if non-nil, zero value otherwise.

### GetEventLabelOk

`func (o *OrgActivityLogEntry) GetEventLabelOk() (*string, bool)`

GetEventLabelOk returns a tuple with the EventLabel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEventLabel

`func (o *OrgActivityLogEntry) SetEventLabel(v string)`

SetEventLabel sets EventLabel field to given value.

### HasEventLabel

`func (o *OrgActivityLogEntry) HasEventLabel() bool`

HasEventLabel returns a boolean if a field has been set.

### GetEventType

`func (o *OrgActivityLogEntry) GetEventType() string`

GetEventType returns the EventType field if non-nil, zero value otherwise.

### GetEventTypeOk

`func (o *OrgActivityLogEntry) GetEventTypeOk() (*string, bool)`

GetEventTypeOk returns a tuple with the EventType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEventType

`func (o *OrgActivityLogEntry) SetEventType(v string)`

SetEventType sets EventType field to given value.

### HasEventType

`func (o *OrgActivityLogEntry) HasEventType() bool`

HasEventType returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


