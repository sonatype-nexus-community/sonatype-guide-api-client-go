# CurrentUserOrganizationResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**IsOwner** | Pointer to **bool** |  | [optional] 
**Logo** | Pointer to **string** |  | [optional] 
**Name** | Pointer to **string** |  | [optional] 
**People** | Pointer to **int32** |  | [optional] 
**Plan** | Pointer to [**OrganizationPlanDTO**](OrganizationPlanDTO.md) |  | [optional] 
**Slug** | Pointer to **string** |  | [optional] 
**Url** | Pointer to **string** |  | [optional] 
**Usage** | Pointer to **int32** |  | [optional] 
**UsageDetail** | Pointer to [**OrganizationUsageDTO**](OrganizationUsageDTO.md) |  | [optional] 

## Methods

### NewCurrentUserOrganizationResponse

`func NewCurrentUserOrganizationResponse() *CurrentUserOrganizationResponse`

NewCurrentUserOrganizationResponse instantiates a new CurrentUserOrganizationResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCurrentUserOrganizationResponseWithDefaults

`func NewCurrentUserOrganizationResponseWithDefaults() *CurrentUserOrganizationResponse`

NewCurrentUserOrganizationResponseWithDefaults instantiates a new CurrentUserOrganizationResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIsOwner

`func (o *CurrentUserOrganizationResponse) GetIsOwner() bool`

GetIsOwner returns the IsOwner field if non-nil, zero value otherwise.

### GetIsOwnerOk

`func (o *CurrentUserOrganizationResponse) GetIsOwnerOk() (*bool, bool)`

GetIsOwnerOk returns a tuple with the IsOwner field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsOwner

`func (o *CurrentUserOrganizationResponse) SetIsOwner(v bool)`

SetIsOwner sets IsOwner field to given value.

### HasIsOwner

`func (o *CurrentUserOrganizationResponse) HasIsOwner() bool`

HasIsOwner returns a boolean if a field has been set.

### GetLogo

`func (o *CurrentUserOrganizationResponse) GetLogo() string`

GetLogo returns the Logo field if non-nil, zero value otherwise.

### GetLogoOk

`func (o *CurrentUserOrganizationResponse) GetLogoOk() (*string, bool)`

GetLogoOk returns a tuple with the Logo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLogo

`func (o *CurrentUserOrganizationResponse) SetLogo(v string)`

SetLogo sets Logo field to given value.

### HasLogo

`func (o *CurrentUserOrganizationResponse) HasLogo() bool`

HasLogo returns a boolean if a field has been set.

### GetName

`func (o *CurrentUserOrganizationResponse) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CurrentUserOrganizationResponse) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CurrentUserOrganizationResponse) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *CurrentUserOrganizationResponse) HasName() bool`

HasName returns a boolean if a field has been set.

### GetPeople

`func (o *CurrentUserOrganizationResponse) GetPeople() int32`

GetPeople returns the People field if non-nil, zero value otherwise.

### GetPeopleOk

`func (o *CurrentUserOrganizationResponse) GetPeopleOk() (*int32, bool)`

GetPeopleOk returns a tuple with the People field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeople

`func (o *CurrentUserOrganizationResponse) SetPeople(v int32)`

SetPeople sets People field to given value.

### HasPeople

`func (o *CurrentUserOrganizationResponse) HasPeople() bool`

HasPeople returns a boolean if a field has been set.

### GetPlan

`func (o *CurrentUserOrganizationResponse) GetPlan() OrganizationPlanDTO`

GetPlan returns the Plan field if non-nil, zero value otherwise.

### GetPlanOk

`func (o *CurrentUserOrganizationResponse) GetPlanOk() (*OrganizationPlanDTO, bool)`

GetPlanOk returns a tuple with the Plan field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlan

`func (o *CurrentUserOrganizationResponse) SetPlan(v OrganizationPlanDTO)`

SetPlan sets Plan field to given value.

### HasPlan

`func (o *CurrentUserOrganizationResponse) HasPlan() bool`

HasPlan returns a boolean if a field has been set.

### GetSlug

`func (o *CurrentUserOrganizationResponse) GetSlug() string`

GetSlug returns the Slug field if non-nil, zero value otherwise.

### GetSlugOk

`func (o *CurrentUserOrganizationResponse) GetSlugOk() (*string, bool)`

GetSlugOk returns a tuple with the Slug field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSlug

`func (o *CurrentUserOrganizationResponse) SetSlug(v string)`

SetSlug sets Slug field to given value.

### HasSlug

`func (o *CurrentUserOrganizationResponse) HasSlug() bool`

HasSlug returns a boolean if a field has been set.

### GetUrl

`func (o *CurrentUserOrganizationResponse) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *CurrentUserOrganizationResponse) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *CurrentUserOrganizationResponse) SetUrl(v string)`

SetUrl sets Url field to given value.

### HasUrl

`func (o *CurrentUserOrganizationResponse) HasUrl() bool`

HasUrl returns a boolean if a field has been set.

### GetUsage

`func (o *CurrentUserOrganizationResponse) GetUsage() int32`

GetUsage returns the Usage field if non-nil, zero value otherwise.

### GetUsageOk

`func (o *CurrentUserOrganizationResponse) GetUsageOk() (*int32, bool)`

GetUsageOk returns a tuple with the Usage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsage

`func (o *CurrentUserOrganizationResponse) SetUsage(v int32)`

SetUsage sets Usage field to given value.

### HasUsage

`func (o *CurrentUserOrganizationResponse) HasUsage() bool`

HasUsage returns a boolean if a field has been set.

### GetUsageDetail

`func (o *CurrentUserOrganizationResponse) GetUsageDetail() OrganizationUsageDTO`

GetUsageDetail returns the UsageDetail field if non-nil, zero value otherwise.

### GetUsageDetailOk

`func (o *CurrentUserOrganizationResponse) GetUsageDetailOk() (*OrganizationUsageDTO, bool)`

GetUsageDetailOk returns a tuple with the UsageDetail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsageDetail

`func (o *CurrentUserOrganizationResponse) SetUsageDetail(v OrganizationUsageDTO)`

SetUsageDetail sets UsageDetail field to given value.

### HasUsageDetail

`func (o *CurrentUserOrganizationResponse) HasUsageDetail() bool`

HasUsageDetail returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


