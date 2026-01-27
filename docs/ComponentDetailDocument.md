# ComponentDetailDocument

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Categories** | Pointer to **[]string** |  | [optional] 
**Components** | Pointer to [**[]ComponentArtifact**](ComponentArtifact.md) |  | [optional] 
**DirectDependencies** | Pointer to **[]string** |  | [optional] 
**Format** | Pointer to **string** |  | [optional] 
**IsMalware** | Pointer to **bool** |  | [optional] 
**LatestStable** | Pointer to **bool** |  | [optional] 
**Licenses** | Pointer to [**[]ComponentLicense**](ComponentLicense.md) |  | [optional] 
**MaxCvss** | Pointer to **float64** |  | [optional] 
**Name** | Pointer to **string** |  | [optional] 
**Namespace** | Pointer to **string** |  | [optional] 
**OriginId** | Pointer to **string** |  | [optional] 
**PublishedDate** | Pointer to **time.Time** |  | [optional] 
**RegistryLink** | Pointer to **string** |  | [optional] 
**Version** | Pointer to **string** |  | [optional] 
**VersionScore** | Pointer to **int32** |  | [optional] 

## Methods

### NewComponentDetailDocument

`func NewComponentDetailDocument() *ComponentDetailDocument`

NewComponentDetailDocument instantiates a new ComponentDetailDocument object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewComponentDetailDocumentWithDefaults

`func NewComponentDetailDocumentWithDefaults() *ComponentDetailDocument`

NewComponentDetailDocumentWithDefaults instantiates a new ComponentDetailDocument object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCategories

`func (o *ComponentDetailDocument) GetCategories() []string`

GetCategories returns the Categories field if non-nil, zero value otherwise.

### GetCategoriesOk

`func (o *ComponentDetailDocument) GetCategoriesOk() (*[]string, bool)`

GetCategoriesOk returns a tuple with the Categories field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategories

`func (o *ComponentDetailDocument) SetCategories(v []string)`

SetCategories sets Categories field to given value.

### HasCategories

`func (o *ComponentDetailDocument) HasCategories() bool`

HasCategories returns a boolean if a field has been set.

### GetComponents

`func (o *ComponentDetailDocument) GetComponents() []ComponentArtifact`

GetComponents returns the Components field if non-nil, zero value otherwise.

### GetComponentsOk

`func (o *ComponentDetailDocument) GetComponentsOk() (*[]ComponentArtifact, bool)`

GetComponentsOk returns a tuple with the Components field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComponents

`func (o *ComponentDetailDocument) SetComponents(v []ComponentArtifact)`

SetComponents sets Components field to given value.

### HasComponents

`func (o *ComponentDetailDocument) HasComponents() bool`

HasComponents returns a boolean if a field has been set.

### GetDirectDependencies

`func (o *ComponentDetailDocument) GetDirectDependencies() []string`

GetDirectDependencies returns the DirectDependencies field if non-nil, zero value otherwise.

### GetDirectDependenciesOk

`func (o *ComponentDetailDocument) GetDirectDependenciesOk() (*[]string, bool)`

GetDirectDependenciesOk returns a tuple with the DirectDependencies field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDirectDependencies

`func (o *ComponentDetailDocument) SetDirectDependencies(v []string)`

SetDirectDependencies sets DirectDependencies field to given value.

### HasDirectDependencies

`func (o *ComponentDetailDocument) HasDirectDependencies() bool`

HasDirectDependencies returns a boolean if a field has been set.

### GetFormat

`func (o *ComponentDetailDocument) GetFormat() string`

GetFormat returns the Format field if non-nil, zero value otherwise.

### GetFormatOk

`func (o *ComponentDetailDocument) GetFormatOk() (*string, bool)`

GetFormatOk returns a tuple with the Format field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFormat

`func (o *ComponentDetailDocument) SetFormat(v string)`

SetFormat sets Format field to given value.

### HasFormat

`func (o *ComponentDetailDocument) HasFormat() bool`

HasFormat returns a boolean if a field has been set.

### GetIsMalware

`func (o *ComponentDetailDocument) GetIsMalware() bool`

GetIsMalware returns the IsMalware field if non-nil, zero value otherwise.

### GetIsMalwareOk

`func (o *ComponentDetailDocument) GetIsMalwareOk() (*bool, bool)`

GetIsMalwareOk returns a tuple with the IsMalware field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsMalware

`func (o *ComponentDetailDocument) SetIsMalware(v bool)`

SetIsMalware sets IsMalware field to given value.

### HasIsMalware

`func (o *ComponentDetailDocument) HasIsMalware() bool`

HasIsMalware returns a boolean if a field has been set.

### GetLatestStable

`func (o *ComponentDetailDocument) GetLatestStable() bool`

GetLatestStable returns the LatestStable field if non-nil, zero value otherwise.

### GetLatestStableOk

`func (o *ComponentDetailDocument) GetLatestStableOk() (*bool, bool)`

GetLatestStableOk returns a tuple with the LatestStable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLatestStable

`func (o *ComponentDetailDocument) SetLatestStable(v bool)`

SetLatestStable sets LatestStable field to given value.

### HasLatestStable

`func (o *ComponentDetailDocument) HasLatestStable() bool`

HasLatestStable returns a boolean if a field has been set.

### GetLicenses

`func (o *ComponentDetailDocument) GetLicenses() []ComponentLicense`

GetLicenses returns the Licenses field if non-nil, zero value otherwise.

### GetLicensesOk

`func (o *ComponentDetailDocument) GetLicensesOk() (*[]ComponentLicense, bool)`

GetLicensesOk returns a tuple with the Licenses field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLicenses

`func (o *ComponentDetailDocument) SetLicenses(v []ComponentLicense)`

SetLicenses sets Licenses field to given value.

### HasLicenses

`func (o *ComponentDetailDocument) HasLicenses() bool`

HasLicenses returns a boolean if a field has been set.

### GetMaxCvss

`func (o *ComponentDetailDocument) GetMaxCvss() float64`

GetMaxCvss returns the MaxCvss field if non-nil, zero value otherwise.

### GetMaxCvssOk

`func (o *ComponentDetailDocument) GetMaxCvssOk() (*float64, bool)`

GetMaxCvssOk returns a tuple with the MaxCvss field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxCvss

`func (o *ComponentDetailDocument) SetMaxCvss(v float64)`

SetMaxCvss sets MaxCvss field to given value.

### HasMaxCvss

`func (o *ComponentDetailDocument) HasMaxCvss() bool`

HasMaxCvss returns a boolean if a field has been set.

### GetName

`func (o *ComponentDetailDocument) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ComponentDetailDocument) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ComponentDetailDocument) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *ComponentDetailDocument) HasName() bool`

HasName returns a boolean if a field has been set.

### GetNamespace

`func (o *ComponentDetailDocument) GetNamespace() string`

GetNamespace returns the Namespace field if non-nil, zero value otherwise.

### GetNamespaceOk

`func (o *ComponentDetailDocument) GetNamespaceOk() (*string, bool)`

GetNamespaceOk returns a tuple with the Namespace field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNamespace

`func (o *ComponentDetailDocument) SetNamespace(v string)`

SetNamespace sets Namespace field to given value.

### HasNamespace

`func (o *ComponentDetailDocument) HasNamespace() bool`

HasNamespace returns a boolean if a field has been set.

### GetOriginId

`func (o *ComponentDetailDocument) GetOriginId() string`

GetOriginId returns the OriginId field if non-nil, zero value otherwise.

### GetOriginIdOk

`func (o *ComponentDetailDocument) GetOriginIdOk() (*string, bool)`

GetOriginIdOk returns a tuple with the OriginId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOriginId

`func (o *ComponentDetailDocument) SetOriginId(v string)`

SetOriginId sets OriginId field to given value.

### HasOriginId

`func (o *ComponentDetailDocument) HasOriginId() bool`

HasOriginId returns a boolean if a field has been set.

### GetPublishedDate

`func (o *ComponentDetailDocument) GetPublishedDate() time.Time`

GetPublishedDate returns the PublishedDate field if non-nil, zero value otherwise.

### GetPublishedDateOk

`func (o *ComponentDetailDocument) GetPublishedDateOk() (*time.Time, bool)`

GetPublishedDateOk returns a tuple with the PublishedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublishedDate

`func (o *ComponentDetailDocument) SetPublishedDate(v time.Time)`

SetPublishedDate sets PublishedDate field to given value.

### HasPublishedDate

`func (o *ComponentDetailDocument) HasPublishedDate() bool`

HasPublishedDate returns a boolean if a field has been set.

### GetRegistryLink

`func (o *ComponentDetailDocument) GetRegistryLink() string`

GetRegistryLink returns the RegistryLink field if non-nil, zero value otherwise.

### GetRegistryLinkOk

`func (o *ComponentDetailDocument) GetRegistryLinkOk() (*string, bool)`

GetRegistryLinkOk returns a tuple with the RegistryLink field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRegistryLink

`func (o *ComponentDetailDocument) SetRegistryLink(v string)`

SetRegistryLink sets RegistryLink field to given value.

### HasRegistryLink

`func (o *ComponentDetailDocument) HasRegistryLink() bool`

HasRegistryLink returns a boolean if a field has been set.

### GetVersion

`func (o *ComponentDetailDocument) GetVersion() string`

GetVersion returns the Version field if non-nil, zero value otherwise.

### GetVersionOk

`func (o *ComponentDetailDocument) GetVersionOk() (*string, bool)`

GetVersionOk returns a tuple with the Version field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersion

`func (o *ComponentDetailDocument) SetVersion(v string)`

SetVersion sets Version field to given value.

### HasVersion

`func (o *ComponentDetailDocument) HasVersion() bool`

HasVersion returns a boolean if a field has been set.

### GetVersionScore

`func (o *ComponentDetailDocument) GetVersionScore() int32`

GetVersionScore returns the VersionScore field if non-nil, zero value otherwise.

### GetVersionScoreOk

`func (o *ComponentDetailDocument) GetVersionScoreOk() (*int32, bool)`

GetVersionScoreOk returns a tuple with the VersionScore field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersionScore

`func (o *ComponentDetailDocument) SetVersionScore(v int32)`

SetVersionScore sets VersionScore field to given value.

### HasVersionScore

`func (o *ComponentDetailDocument) HasVersionScore() bool`

HasVersionScore returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


