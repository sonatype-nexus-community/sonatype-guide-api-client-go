# ComponentReportGet

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Coordinates** | Pointer to **string** |  | [optional] 
**Description** | Pointer to **string** |  | [optional] 
**Reference** | Pointer to **string** |  | [optional] 
**SonatypeOssiScore** | Pointer to **float64** |  | [optional] 
**Vulnerabilities** | Pointer to [**[]OssiVulnerabilityPost**](OssiVulnerabilityPost.md) |  | [optional] 

## Methods

### NewComponentReportGet

`func NewComponentReportGet() *ComponentReportGet`

NewComponentReportGet instantiates a new ComponentReportGet object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewComponentReportGetWithDefaults

`func NewComponentReportGetWithDefaults() *ComponentReportGet`

NewComponentReportGetWithDefaults instantiates a new ComponentReportGet object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCoordinates

`func (o *ComponentReportGet) GetCoordinates() string`

GetCoordinates returns the Coordinates field if non-nil, zero value otherwise.

### GetCoordinatesOk

`func (o *ComponentReportGet) GetCoordinatesOk() (*string, bool)`

GetCoordinatesOk returns a tuple with the Coordinates field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCoordinates

`func (o *ComponentReportGet) SetCoordinates(v string)`

SetCoordinates sets Coordinates field to given value.

### HasCoordinates

`func (o *ComponentReportGet) HasCoordinates() bool`

HasCoordinates returns a boolean if a field has been set.

### GetDescription

`func (o *ComponentReportGet) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *ComponentReportGet) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *ComponentReportGet) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *ComponentReportGet) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetReference

`func (o *ComponentReportGet) GetReference() string`

GetReference returns the Reference field if non-nil, zero value otherwise.

### GetReferenceOk

`func (o *ComponentReportGet) GetReferenceOk() (*string, bool)`

GetReferenceOk returns a tuple with the Reference field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReference

`func (o *ComponentReportGet) SetReference(v string)`

SetReference sets Reference field to given value.

### HasReference

`func (o *ComponentReportGet) HasReference() bool`

HasReference returns a boolean if a field has been set.

### GetSonatypeOssiScore

`func (o *ComponentReportGet) GetSonatypeOssiScore() float64`

GetSonatypeOssiScore returns the SonatypeOssiScore field if non-nil, zero value otherwise.

### GetSonatypeOssiScoreOk

`func (o *ComponentReportGet) GetSonatypeOssiScoreOk() (*float64, bool)`

GetSonatypeOssiScoreOk returns a tuple with the SonatypeOssiScore field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSonatypeOssiScore

`func (o *ComponentReportGet) SetSonatypeOssiScore(v float64)`

SetSonatypeOssiScore sets SonatypeOssiScore field to given value.

### HasSonatypeOssiScore

`func (o *ComponentReportGet) HasSonatypeOssiScore() bool`

HasSonatypeOssiScore returns a boolean if a field has been set.

### GetVulnerabilities

`func (o *ComponentReportGet) GetVulnerabilities() []OssiVulnerabilityPost`

GetVulnerabilities returns the Vulnerabilities field if non-nil, zero value otherwise.

### GetVulnerabilitiesOk

`func (o *ComponentReportGet) GetVulnerabilitiesOk() (*[]OssiVulnerabilityPost, bool)`

GetVulnerabilitiesOk returns a tuple with the Vulnerabilities field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVulnerabilities

`func (o *ComponentReportGet) SetVulnerabilities(v []OssiVulnerabilityPost)`

SetVulnerabilities sets Vulnerabilities field to given value.

### HasVulnerabilities

`func (o *ComponentReportGet) HasVulnerabilities() bool`

HasVulnerabilities returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


