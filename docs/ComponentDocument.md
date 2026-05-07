# ComponentDocument

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Categories** | Pointer to **[]string** |  | [optional] 
**Dts** | Pointer to [**DtsDimensions**](DtsDimensions.md) |  | [optional] 
**Format** | Pointer to **string** |  | [optional] 
**IsMalware** | Pointer to **bool** |  | [optional] 
**LatestStable** | Pointer to **bool** |  | [optional] 
**Licenses** | Pointer to [**[]ComponentLicense**](ComponentLicense.md) |  | [optional] 
**MaxCvss** | Pointer to **float64** |  | [optional] 
**Name** | Pointer to **string** |  | [optional] 
**Namespace** | Pointer to **string** |  | [optional] 
**OriginId** | Pointer to **string** |  | [optional] 
**PolicyCompliance** | Pointer to [**PolicyComplianceResult**](PolicyComplianceResult.md) |  | [optional] 
**PublishedDate** | Pointer to **time.Time** |  | [optional] 
**RegistryLink** | Pointer to **string** |  | [optional] 
**Version** | Pointer to **string** |  | [optional] 
**VersionScore** | Pointer to **int32** |  | [optional] 

## Methods

### NewComponentDocument

`func NewComponentDocument() *ComponentDocument`

NewComponentDocument instantiates a new ComponentDocument object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewComponentDocumentWithDefaults

`func NewComponentDocumentWithDefaults() *ComponentDocument`

NewComponentDocumentWithDefaults instantiates a new ComponentDocument object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCategories

`func (o *ComponentDocument) GetCategories() []string`

GetCategories returns the Categories field if non-nil, zero value otherwise.

### GetCategoriesOk

`func (o *ComponentDocument) GetCategoriesOk() (*[]string, bool)`

GetCategoriesOk returns a tuple with the Categories field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategories

`func (o *ComponentDocument) SetCategories(v []string)`

SetCategories sets Categories field to given value.

### HasCategories

`func (o *ComponentDocument) HasCategories() bool`

HasCategories returns a boolean if a field has been set.

### GetDts

`func (o *ComponentDocument) GetDts() DtsDimensions`

GetDts returns the Dts field if non-nil, zero value otherwise.

### GetDtsOk

`func (o *ComponentDocument) GetDtsOk() (*DtsDimensions, bool)`

GetDtsOk returns a tuple with the Dts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDts

`func (o *ComponentDocument) SetDts(v DtsDimensions)`

SetDts sets Dts field to given value.

### HasDts

`func (o *ComponentDocument) HasDts() bool`

HasDts returns a boolean if a field has been set.

### GetFormat

`func (o *ComponentDocument) GetFormat() string`

GetFormat returns the Format field if non-nil, zero value otherwise.

### GetFormatOk

`func (o *ComponentDocument) GetFormatOk() (*string, bool)`

GetFormatOk returns a tuple with the Format field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFormat

`func (o *ComponentDocument) SetFormat(v string)`

SetFormat sets Format field to given value.

### HasFormat

`func (o *ComponentDocument) HasFormat() bool`

HasFormat returns a boolean if a field has been set.

### GetIsMalware

`func (o *ComponentDocument) GetIsMalware() bool`

GetIsMalware returns the IsMalware field if non-nil, zero value otherwise.

### GetIsMalwareOk

`func (o *ComponentDocument) GetIsMalwareOk() (*bool, bool)`

GetIsMalwareOk returns a tuple with the IsMalware field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsMalware

`func (o *ComponentDocument) SetIsMalware(v bool)`

SetIsMalware sets IsMalware field to given value.

### HasIsMalware

`func (o *ComponentDocument) HasIsMalware() bool`

HasIsMalware returns a boolean if a field has been set.

### GetLatestStable

`func (o *ComponentDocument) GetLatestStable() bool`

GetLatestStable returns the LatestStable field if non-nil, zero value otherwise.

### GetLatestStableOk

`func (o *ComponentDocument) GetLatestStableOk() (*bool, bool)`

GetLatestStableOk returns a tuple with the LatestStable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLatestStable

`func (o *ComponentDocument) SetLatestStable(v bool)`

SetLatestStable sets LatestStable field to given value.

### HasLatestStable

`func (o *ComponentDocument) HasLatestStable() bool`

HasLatestStable returns a boolean if a field has been set.

### GetLicenses

`func (o *ComponentDocument) GetLicenses() []ComponentLicense`

GetLicenses returns the Licenses field if non-nil, zero value otherwise.

### GetLicensesOk

`func (o *ComponentDocument) GetLicensesOk() (*[]ComponentLicense, bool)`

GetLicensesOk returns a tuple with the Licenses field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLicenses

`func (o *ComponentDocument) SetLicenses(v []ComponentLicense)`

SetLicenses sets Licenses field to given value.

### HasLicenses

`func (o *ComponentDocument) HasLicenses() bool`

HasLicenses returns a boolean if a field has been set.

### GetMaxCvss

`func (o *ComponentDocument) GetMaxCvss() float64`

GetMaxCvss returns the MaxCvss field if non-nil, zero value otherwise.

### GetMaxCvssOk

`func (o *ComponentDocument) GetMaxCvssOk() (*float64, bool)`

GetMaxCvssOk returns a tuple with the MaxCvss field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxCvss

`func (o *ComponentDocument) SetMaxCvss(v float64)`

SetMaxCvss sets MaxCvss field to given value.

### HasMaxCvss

`func (o *ComponentDocument) HasMaxCvss() bool`

HasMaxCvss returns a boolean if a field has been set.

### GetName

`func (o *ComponentDocument) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ComponentDocument) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ComponentDocument) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *ComponentDocument) HasName() bool`

HasName returns a boolean if a field has been set.

### GetNamespace

`func (o *ComponentDocument) GetNamespace() string`

GetNamespace returns the Namespace field if non-nil, zero value otherwise.

### GetNamespaceOk

`func (o *ComponentDocument) GetNamespaceOk() (*string, bool)`

GetNamespaceOk returns a tuple with the Namespace field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNamespace

`func (o *ComponentDocument) SetNamespace(v string)`

SetNamespace sets Namespace field to given value.

### HasNamespace

`func (o *ComponentDocument) HasNamespace() bool`

HasNamespace returns a boolean if a field has been set.

### GetOriginId

`func (o *ComponentDocument) GetOriginId() string`

GetOriginId returns the OriginId field if non-nil, zero value otherwise.

### GetOriginIdOk

`func (o *ComponentDocument) GetOriginIdOk() (*string, bool)`

GetOriginIdOk returns a tuple with the OriginId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOriginId

`func (o *ComponentDocument) SetOriginId(v string)`

SetOriginId sets OriginId field to given value.

### HasOriginId

`func (o *ComponentDocument) HasOriginId() bool`

HasOriginId returns a boolean if a field has been set.

### GetPolicyCompliance

`func (o *ComponentDocument) GetPolicyCompliance() PolicyComplianceResult`

GetPolicyCompliance returns the PolicyCompliance field if non-nil, zero value otherwise.

### GetPolicyComplianceOk

`func (o *ComponentDocument) GetPolicyComplianceOk() (*PolicyComplianceResult, bool)`

GetPolicyComplianceOk returns a tuple with the PolicyCompliance field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPolicyCompliance

`func (o *ComponentDocument) SetPolicyCompliance(v PolicyComplianceResult)`

SetPolicyCompliance sets PolicyCompliance field to given value.

### HasPolicyCompliance

`func (o *ComponentDocument) HasPolicyCompliance() bool`

HasPolicyCompliance returns a boolean if a field has been set.

### GetPublishedDate

`func (o *ComponentDocument) GetPublishedDate() time.Time`

GetPublishedDate returns the PublishedDate field if non-nil, zero value otherwise.

### GetPublishedDateOk

`func (o *ComponentDocument) GetPublishedDateOk() (*time.Time, bool)`

GetPublishedDateOk returns a tuple with the PublishedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublishedDate

`func (o *ComponentDocument) SetPublishedDate(v time.Time)`

SetPublishedDate sets PublishedDate field to given value.

### HasPublishedDate

`func (o *ComponentDocument) HasPublishedDate() bool`

HasPublishedDate returns a boolean if a field has been set.

### GetRegistryLink

`func (o *ComponentDocument) GetRegistryLink() string`

GetRegistryLink returns the RegistryLink field if non-nil, zero value otherwise.

### GetRegistryLinkOk

`func (o *ComponentDocument) GetRegistryLinkOk() (*string, bool)`

GetRegistryLinkOk returns a tuple with the RegistryLink field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRegistryLink

`func (o *ComponentDocument) SetRegistryLink(v string)`

SetRegistryLink sets RegistryLink field to given value.

### HasRegistryLink

`func (o *ComponentDocument) HasRegistryLink() bool`

HasRegistryLink returns a boolean if a field has been set.

### GetVersion

`func (o *ComponentDocument) GetVersion() string`

GetVersion returns the Version field if non-nil, zero value otherwise.

### GetVersionOk

`func (o *ComponentDocument) GetVersionOk() (*string, bool)`

GetVersionOk returns a tuple with the Version field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersion

`func (o *ComponentDocument) SetVersion(v string)`

SetVersion sets Version field to given value.

### HasVersion

`func (o *ComponentDocument) HasVersion() bool`

HasVersion returns a boolean if a field has been set.

### GetVersionScore

`func (o *ComponentDocument) GetVersionScore() int32`

GetVersionScore returns the VersionScore field if non-nil, zero value otherwise.

### GetVersionScoreOk

`func (o *ComponentDocument) GetVersionScoreOk() (*int32, bool)`

GetVersionScoreOk returns a tuple with the VersionScore field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersionScore

`func (o *ComponentDocument) SetVersionScore(v int32)`

SetVersionScore sets VersionScore field to given value.

### HasVersionScore

`func (o *ComponentDocument) HasVersionScore() bool`

HasVersionScore returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


