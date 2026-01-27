# FromVersion

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**BreakingChangesCount** | Pointer to **string** |  | [optional] 
**DeveloperTrustScore** | Pointer to **int32** |  | [optional] 
**DirectVulnerabilities** | Pointer to **map[string]float64** |  | [optional] 
**LicenseThreatLevels** | Pointer to **map[string]int32** |  | [optional] 
**MaxSeverity** | Pointer to **float64** |  | [optional] 
**TransitiveVulnerabilities** | Pointer to **map[string]float64** |  | [optional] 
**Version** | Pointer to **string** |  | [optional] 
**VulnerableMethods** | Pointer to [**[]VulnerableMethod**](VulnerableMethod.md) |  | [optional] 

## Methods

### NewFromVersion

`func NewFromVersion() *FromVersion`

NewFromVersion instantiates a new FromVersion object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFromVersionWithDefaults

`func NewFromVersionWithDefaults() *FromVersion`

NewFromVersionWithDefaults instantiates a new FromVersion object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBreakingChangesCount

`func (o *FromVersion) GetBreakingChangesCount() string`

GetBreakingChangesCount returns the BreakingChangesCount field if non-nil, zero value otherwise.

### GetBreakingChangesCountOk

`func (o *FromVersion) GetBreakingChangesCountOk() (*string, bool)`

GetBreakingChangesCountOk returns a tuple with the BreakingChangesCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBreakingChangesCount

`func (o *FromVersion) SetBreakingChangesCount(v string)`

SetBreakingChangesCount sets BreakingChangesCount field to given value.

### HasBreakingChangesCount

`func (o *FromVersion) HasBreakingChangesCount() bool`

HasBreakingChangesCount returns a boolean if a field has been set.

### GetDeveloperTrustScore

`func (o *FromVersion) GetDeveloperTrustScore() int32`

GetDeveloperTrustScore returns the DeveloperTrustScore field if non-nil, zero value otherwise.

### GetDeveloperTrustScoreOk

`func (o *FromVersion) GetDeveloperTrustScoreOk() (*int32, bool)`

GetDeveloperTrustScoreOk returns a tuple with the DeveloperTrustScore field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeveloperTrustScore

`func (o *FromVersion) SetDeveloperTrustScore(v int32)`

SetDeveloperTrustScore sets DeveloperTrustScore field to given value.

### HasDeveloperTrustScore

`func (o *FromVersion) HasDeveloperTrustScore() bool`

HasDeveloperTrustScore returns a boolean if a field has been set.

### GetDirectVulnerabilities

`func (o *FromVersion) GetDirectVulnerabilities() map[string]float64`

GetDirectVulnerabilities returns the DirectVulnerabilities field if non-nil, zero value otherwise.

### GetDirectVulnerabilitiesOk

`func (o *FromVersion) GetDirectVulnerabilitiesOk() (*map[string]float64, bool)`

GetDirectVulnerabilitiesOk returns a tuple with the DirectVulnerabilities field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDirectVulnerabilities

`func (o *FromVersion) SetDirectVulnerabilities(v map[string]float64)`

SetDirectVulnerabilities sets DirectVulnerabilities field to given value.

### HasDirectVulnerabilities

`func (o *FromVersion) HasDirectVulnerabilities() bool`

HasDirectVulnerabilities returns a boolean if a field has been set.

### GetLicenseThreatLevels

`func (o *FromVersion) GetLicenseThreatLevels() map[string]int32`

GetLicenseThreatLevels returns the LicenseThreatLevels field if non-nil, zero value otherwise.

### GetLicenseThreatLevelsOk

`func (o *FromVersion) GetLicenseThreatLevelsOk() (*map[string]int32, bool)`

GetLicenseThreatLevelsOk returns a tuple with the LicenseThreatLevels field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLicenseThreatLevels

`func (o *FromVersion) SetLicenseThreatLevels(v map[string]int32)`

SetLicenseThreatLevels sets LicenseThreatLevels field to given value.

### HasLicenseThreatLevels

`func (o *FromVersion) HasLicenseThreatLevels() bool`

HasLicenseThreatLevels returns a boolean if a field has been set.

### GetMaxSeverity

`func (o *FromVersion) GetMaxSeverity() float64`

GetMaxSeverity returns the MaxSeverity field if non-nil, zero value otherwise.

### GetMaxSeverityOk

`func (o *FromVersion) GetMaxSeverityOk() (*float64, bool)`

GetMaxSeverityOk returns a tuple with the MaxSeverity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxSeverity

`func (o *FromVersion) SetMaxSeverity(v float64)`

SetMaxSeverity sets MaxSeverity field to given value.

### HasMaxSeverity

`func (o *FromVersion) HasMaxSeverity() bool`

HasMaxSeverity returns a boolean if a field has been set.

### GetTransitiveVulnerabilities

`func (o *FromVersion) GetTransitiveVulnerabilities() map[string]float64`

GetTransitiveVulnerabilities returns the TransitiveVulnerabilities field if non-nil, zero value otherwise.

### GetTransitiveVulnerabilitiesOk

`func (o *FromVersion) GetTransitiveVulnerabilitiesOk() (*map[string]float64, bool)`

GetTransitiveVulnerabilitiesOk returns a tuple with the TransitiveVulnerabilities field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransitiveVulnerabilities

`func (o *FromVersion) SetTransitiveVulnerabilities(v map[string]float64)`

SetTransitiveVulnerabilities sets TransitiveVulnerabilities field to given value.

### HasTransitiveVulnerabilities

`func (o *FromVersion) HasTransitiveVulnerabilities() bool`

HasTransitiveVulnerabilities returns a boolean if a field has been set.

### GetVersion

`func (o *FromVersion) GetVersion() string`

GetVersion returns the Version field if non-nil, zero value otherwise.

### GetVersionOk

`func (o *FromVersion) GetVersionOk() (*string, bool)`

GetVersionOk returns a tuple with the Version field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersion

`func (o *FromVersion) SetVersion(v string)`

SetVersion sets Version field to given value.

### HasVersion

`func (o *FromVersion) HasVersion() bool`

HasVersion returns a boolean if a field has been set.

### GetVulnerableMethods

`func (o *FromVersion) GetVulnerableMethods() []VulnerableMethod`

GetVulnerableMethods returns the VulnerableMethods field if non-nil, zero value otherwise.

### GetVulnerableMethodsOk

`func (o *FromVersion) GetVulnerableMethodsOk() (*[]VulnerableMethod, bool)`

GetVulnerableMethodsOk returns a tuple with the VulnerableMethods field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVulnerableMethods

`func (o *FromVersion) SetVulnerableMethods(v []VulnerableMethod)`

SetVulnerableMethods sets VulnerableMethods field to given value.

### HasVulnerableMethods

`func (o *FromVersion) HasVulnerableMethods() bool`

HasVulnerableMethods returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


