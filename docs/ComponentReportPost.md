# ComponentReportPost

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Coordinates** | Pointer to **string** |  | [optional] 
**Description** | Pointer to **string** |  | [optional] 
**Reference** | Pointer to **string** |  | [optional] 
**Vulnerabilities** | Pointer to [**[]OssiVulnerabilityPost**](OssiVulnerabilityPost.md) |  | [optional] 

## Methods

### NewComponentReportPost

`func NewComponentReportPost() *ComponentReportPost`

NewComponentReportPost instantiates a new ComponentReportPost object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewComponentReportPostWithDefaults

`func NewComponentReportPostWithDefaults() *ComponentReportPost`

NewComponentReportPostWithDefaults instantiates a new ComponentReportPost object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCoordinates

`func (o *ComponentReportPost) GetCoordinates() string`

GetCoordinates returns the Coordinates field if non-nil, zero value otherwise.

### GetCoordinatesOk

`func (o *ComponentReportPost) GetCoordinatesOk() (*string, bool)`

GetCoordinatesOk returns a tuple with the Coordinates field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCoordinates

`func (o *ComponentReportPost) SetCoordinates(v string)`

SetCoordinates sets Coordinates field to given value.

### HasCoordinates

`func (o *ComponentReportPost) HasCoordinates() bool`

HasCoordinates returns a boolean if a field has been set.

### GetDescription

`func (o *ComponentReportPost) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *ComponentReportPost) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *ComponentReportPost) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *ComponentReportPost) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetReference

`func (o *ComponentReportPost) GetReference() string`

GetReference returns the Reference field if non-nil, zero value otherwise.

### GetReferenceOk

`func (o *ComponentReportPost) GetReferenceOk() (*string, bool)`

GetReferenceOk returns a tuple with the Reference field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReference

`func (o *ComponentReportPost) SetReference(v string)`

SetReference sets Reference field to given value.

### HasReference

`func (o *ComponentReportPost) HasReference() bool`

HasReference returns a boolean if a field has been set.

### GetVulnerabilities

`func (o *ComponentReportPost) GetVulnerabilities() []OssiVulnerabilityPost`

GetVulnerabilities returns the Vulnerabilities field if non-nil, zero value otherwise.

### GetVulnerabilitiesOk

`func (o *ComponentReportPost) GetVulnerabilitiesOk() (*[]OssiVulnerabilityPost, bool)`

GetVulnerabilitiesOk returns a tuple with the Vulnerabilities field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVulnerabilities

`func (o *ComponentReportPost) SetVulnerabilities(v []OssiVulnerabilityPost)`

SetVulnerabilities sets Vulnerabilities field to given value.

### HasVulnerabilities

`func (o *ComponentReportPost) HasVulnerabilities() bool`

HasVulnerabilities returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


