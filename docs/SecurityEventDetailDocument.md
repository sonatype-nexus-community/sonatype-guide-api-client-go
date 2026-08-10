# SecurityEventDetailDocument

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AdvisoryReferenceIds** | Pointer to **[]string** |  | [optional] 
**AffectedComponentVersionsCount** | Pointer to **int32** |  | [optional] 
**AffectedEcosystems** | Pointer to **[]string** |  | [optional] 
**Cwes** | Pointer to **[]string** |  | [optional] 
**Detail** | Pointer to **string** |  | [optional] 
**EventId** | Pointer to **string** |  | [optional] 
**EventSeverityCategory** | Pointer to **string** |  | [optional] 
**EventThreatType** | Pointer to **string** |  | [optional] 
**Guidance** | Pointer to **string** |  | [optional] 
**IsKnownExploited** | Pointer to **bool** |  | [optional] 
**LastUpdatedDate** | Pointer to **time.Time** |  | [optional] 
**MalwareAttackVectors** | Pointer to **[]string** |  | [optional] 
**MalwareThreatTypes** | Pointer to **[]string** |  | [optional] 
**Overview** | Pointer to **string** |  | [optional] 
**PublishedDate** | Pointer to **time.Time** |  | [optional] 
**SonatypeBlogUrl** | Pointer to **string** |  | [optional] 
**Title** | Pointer to **string** |  | [optional] 

## Methods

### NewSecurityEventDetailDocument

`func NewSecurityEventDetailDocument() *SecurityEventDetailDocument`

NewSecurityEventDetailDocument instantiates a new SecurityEventDetailDocument object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSecurityEventDetailDocumentWithDefaults

`func NewSecurityEventDetailDocumentWithDefaults() *SecurityEventDetailDocument`

NewSecurityEventDetailDocumentWithDefaults instantiates a new SecurityEventDetailDocument object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAdvisoryReferenceIds

`func (o *SecurityEventDetailDocument) GetAdvisoryReferenceIds() []string`

GetAdvisoryReferenceIds returns the AdvisoryReferenceIds field if non-nil, zero value otherwise.

### GetAdvisoryReferenceIdsOk

`func (o *SecurityEventDetailDocument) GetAdvisoryReferenceIdsOk() (*[]string, bool)`

GetAdvisoryReferenceIdsOk returns a tuple with the AdvisoryReferenceIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdvisoryReferenceIds

`func (o *SecurityEventDetailDocument) SetAdvisoryReferenceIds(v []string)`

SetAdvisoryReferenceIds sets AdvisoryReferenceIds field to given value.

### HasAdvisoryReferenceIds

`func (o *SecurityEventDetailDocument) HasAdvisoryReferenceIds() bool`

HasAdvisoryReferenceIds returns a boolean if a field has been set.

### GetAffectedComponentVersionsCount

`func (o *SecurityEventDetailDocument) GetAffectedComponentVersionsCount() int32`

GetAffectedComponentVersionsCount returns the AffectedComponentVersionsCount field if non-nil, zero value otherwise.

### GetAffectedComponentVersionsCountOk

`func (o *SecurityEventDetailDocument) GetAffectedComponentVersionsCountOk() (*int32, bool)`

GetAffectedComponentVersionsCountOk returns a tuple with the AffectedComponentVersionsCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAffectedComponentVersionsCount

`func (o *SecurityEventDetailDocument) SetAffectedComponentVersionsCount(v int32)`

SetAffectedComponentVersionsCount sets AffectedComponentVersionsCount field to given value.

### HasAffectedComponentVersionsCount

`func (o *SecurityEventDetailDocument) HasAffectedComponentVersionsCount() bool`

HasAffectedComponentVersionsCount returns a boolean if a field has been set.

### GetAffectedEcosystems

`func (o *SecurityEventDetailDocument) GetAffectedEcosystems() []string`

GetAffectedEcosystems returns the AffectedEcosystems field if non-nil, zero value otherwise.

### GetAffectedEcosystemsOk

`func (o *SecurityEventDetailDocument) GetAffectedEcosystemsOk() (*[]string, bool)`

GetAffectedEcosystemsOk returns a tuple with the AffectedEcosystems field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAffectedEcosystems

`func (o *SecurityEventDetailDocument) SetAffectedEcosystems(v []string)`

SetAffectedEcosystems sets AffectedEcosystems field to given value.

### HasAffectedEcosystems

`func (o *SecurityEventDetailDocument) HasAffectedEcosystems() bool`

HasAffectedEcosystems returns a boolean if a field has been set.

### GetCwes

`func (o *SecurityEventDetailDocument) GetCwes() []string`

GetCwes returns the Cwes field if non-nil, zero value otherwise.

### GetCwesOk

`func (o *SecurityEventDetailDocument) GetCwesOk() (*[]string, bool)`

GetCwesOk returns a tuple with the Cwes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCwes

`func (o *SecurityEventDetailDocument) SetCwes(v []string)`

SetCwes sets Cwes field to given value.

### HasCwes

`func (o *SecurityEventDetailDocument) HasCwes() bool`

HasCwes returns a boolean if a field has been set.

### GetDetail

`func (o *SecurityEventDetailDocument) GetDetail() string`

GetDetail returns the Detail field if non-nil, zero value otherwise.

### GetDetailOk

`func (o *SecurityEventDetailDocument) GetDetailOk() (*string, bool)`

GetDetailOk returns a tuple with the Detail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDetail

`func (o *SecurityEventDetailDocument) SetDetail(v string)`

SetDetail sets Detail field to given value.

### HasDetail

`func (o *SecurityEventDetailDocument) HasDetail() bool`

HasDetail returns a boolean if a field has been set.

### GetEventId

`func (o *SecurityEventDetailDocument) GetEventId() string`

GetEventId returns the EventId field if non-nil, zero value otherwise.

### GetEventIdOk

`func (o *SecurityEventDetailDocument) GetEventIdOk() (*string, bool)`

GetEventIdOk returns a tuple with the EventId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEventId

`func (o *SecurityEventDetailDocument) SetEventId(v string)`

SetEventId sets EventId field to given value.

### HasEventId

`func (o *SecurityEventDetailDocument) HasEventId() bool`

HasEventId returns a boolean if a field has been set.

### GetEventSeverityCategory

`func (o *SecurityEventDetailDocument) GetEventSeverityCategory() string`

GetEventSeverityCategory returns the EventSeverityCategory field if non-nil, zero value otherwise.

### GetEventSeverityCategoryOk

`func (o *SecurityEventDetailDocument) GetEventSeverityCategoryOk() (*string, bool)`

GetEventSeverityCategoryOk returns a tuple with the EventSeverityCategory field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEventSeverityCategory

`func (o *SecurityEventDetailDocument) SetEventSeverityCategory(v string)`

SetEventSeverityCategory sets EventSeverityCategory field to given value.

### HasEventSeverityCategory

`func (o *SecurityEventDetailDocument) HasEventSeverityCategory() bool`

HasEventSeverityCategory returns a boolean if a field has been set.

### GetEventThreatType

`func (o *SecurityEventDetailDocument) GetEventThreatType() string`

GetEventThreatType returns the EventThreatType field if non-nil, zero value otherwise.

### GetEventThreatTypeOk

`func (o *SecurityEventDetailDocument) GetEventThreatTypeOk() (*string, bool)`

GetEventThreatTypeOk returns a tuple with the EventThreatType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEventThreatType

`func (o *SecurityEventDetailDocument) SetEventThreatType(v string)`

SetEventThreatType sets EventThreatType field to given value.

### HasEventThreatType

`func (o *SecurityEventDetailDocument) HasEventThreatType() bool`

HasEventThreatType returns a boolean if a field has been set.

### GetGuidance

`func (o *SecurityEventDetailDocument) GetGuidance() string`

GetGuidance returns the Guidance field if non-nil, zero value otherwise.

### GetGuidanceOk

`func (o *SecurityEventDetailDocument) GetGuidanceOk() (*string, bool)`

GetGuidanceOk returns a tuple with the Guidance field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGuidance

`func (o *SecurityEventDetailDocument) SetGuidance(v string)`

SetGuidance sets Guidance field to given value.

### HasGuidance

`func (o *SecurityEventDetailDocument) HasGuidance() bool`

HasGuidance returns a boolean if a field has been set.

### GetIsKnownExploited

`func (o *SecurityEventDetailDocument) GetIsKnownExploited() bool`

GetIsKnownExploited returns the IsKnownExploited field if non-nil, zero value otherwise.

### GetIsKnownExploitedOk

`func (o *SecurityEventDetailDocument) GetIsKnownExploitedOk() (*bool, bool)`

GetIsKnownExploitedOk returns a tuple with the IsKnownExploited field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsKnownExploited

`func (o *SecurityEventDetailDocument) SetIsKnownExploited(v bool)`

SetIsKnownExploited sets IsKnownExploited field to given value.

### HasIsKnownExploited

`func (o *SecurityEventDetailDocument) HasIsKnownExploited() bool`

HasIsKnownExploited returns a boolean if a field has been set.

### GetLastUpdatedDate

`func (o *SecurityEventDetailDocument) GetLastUpdatedDate() time.Time`

GetLastUpdatedDate returns the LastUpdatedDate field if non-nil, zero value otherwise.

### GetLastUpdatedDateOk

`func (o *SecurityEventDetailDocument) GetLastUpdatedDateOk() (*time.Time, bool)`

GetLastUpdatedDateOk returns a tuple with the LastUpdatedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastUpdatedDate

`func (o *SecurityEventDetailDocument) SetLastUpdatedDate(v time.Time)`

SetLastUpdatedDate sets LastUpdatedDate field to given value.

### HasLastUpdatedDate

`func (o *SecurityEventDetailDocument) HasLastUpdatedDate() bool`

HasLastUpdatedDate returns a boolean if a field has been set.

### GetMalwareAttackVectors

`func (o *SecurityEventDetailDocument) GetMalwareAttackVectors() []string`

GetMalwareAttackVectors returns the MalwareAttackVectors field if non-nil, zero value otherwise.

### GetMalwareAttackVectorsOk

`func (o *SecurityEventDetailDocument) GetMalwareAttackVectorsOk() (*[]string, bool)`

GetMalwareAttackVectorsOk returns a tuple with the MalwareAttackVectors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMalwareAttackVectors

`func (o *SecurityEventDetailDocument) SetMalwareAttackVectors(v []string)`

SetMalwareAttackVectors sets MalwareAttackVectors field to given value.

### HasMalwareAttackVectors

`func (o *SecurityEventDetailDocument) HasMalwareAttackVectors() bool`

HasMalwareAttackVectors returns a boolean if a field has been set.

### GetMalwareThreatTypes

`func (o *SecurityEventDetailDocument) GetMalwareThreatTypes() []string`

GetMalwareThreatTypes returns the MalwareThreatTypes field if non-nil, zero value otherwise.

### GetMalwareThreatTypesOk

`func (o *SecurityEventDetailDocument) GetMalwareThreatTypesOk() (*[]string, bool)`

GetMalwareThreatTypesOk returns a tuple with the MalwareThreatTypes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMalwareThreatTypes

`func (o *SecurityEventDetailDocument) SetMalwareThreatTypes(v []string)`

SetMalwareThreatTypes sets MalwareThreatTypes field to given value.

### HasMalwareThreatTypes

`func (o *SecurityEventDetailDocument) HasMalwareThreatTypes() bool`

HasMalwareThreatTypes returns a boolean if a field has been set.

### GetOverview

`func (o *SecurityEventDetailDocument) GetOverview() string`

GetOverview returns the Overview field if non-nil, zero value otherwise.

### GetOverviewOk

`func (o *SecurityEventDetailDocument) GetOverviewOk() (*string, bool)`

GetOverviewOk returns a tuple with the Overview field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOverview

`func (o *SecurityEventDetailDocument) SetOverview(v string)`

SetOverview sets Overview field to given value.

### HasOverview

`func (o *SecurityEventDetailDocument) HasOverview() bool`

HasOverview returns a boolean if a field has been set.

### GetPublishedDate

`func (o *SecurityEventDetailDocument) GetPublishedDate() time.Time`

GetPublishedDate returns the PublishedDate field if non-nil, zero value otherwise.

### GetPublishedDateOk

`func (o *SecurityEventDetailDocument) GetPublishedDateOk() (*time.Time, bool)`

GetPublishedDateOk returns a tuple with the PublishedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublishedDate

`func (o *SecurityEventDetailDocument) SetPublishedDate(v time.Time)`

SetPublishedDate sets PublishedDate field to given value.

### HasPublishedDate

`func (o *SecurityEventDetailDocument) HasPublishedDate() bool`

HasPublishedDate returns a boolean if a field has been set.

### GetSonatypeBlogUrl

`func (o *SecurityEventDetailDocument) GetSonatypeBlogUrl() string`

GetSonatypeBlogUrl returns the SonatypeBlogUrl field if non-nil, zero value otherwise.

### GetSonatypeBlogUrlOk

`func (o *SecurityEventDetailDocument) GetSonatypeBlogUrlOk() (*string, bool)`

GetSonatypeBlogUrlOk returns a tuple with the SonatypeBlogUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSonatypeBlogUrl

`func (o *SecurityEventDetailDocument) SetSonatypeBlogUrl(v string)`

SetSonatypeBlogUrl sets SonatypeBlogUrl field to given value.

### HasSonatypeBlogUrl

`func (o *SecurityEventDetailDocument) HasSonatypeBlogUrl() bool`

HasSonatypeBlogUrl returns a boolean if a field has been set.

### GetTitle

`func (o *SecurityEventDetailDocument) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *SecurityEventDetailDocument) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *SecurityEventDetailDocument) SetTitle(v string)`

SetTitle sets Title field to given value.

### HasTitle

`func (o *SecurityEventDetailDocument) HasTitle() bool`

HasTitle returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


