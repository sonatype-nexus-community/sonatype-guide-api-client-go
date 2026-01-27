# ComponentArtifact

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Classifier** | Pointer to **string** |  | [optional] 
**Extension** | Pointer to **string** |  | [optional] 
**PublishedDate** | Pointer to **time.Time** |  | [optional] 
**Refids** | Pointer to [**[]Refid**](Refid.md) |  | [optional] 
**Sha1** | Pointer to **string** |  | [optional] 

## Methods

### NewComponentArtifact

`func NewComponentArtifact() *ComponentArtifact`

NewComponentArtifact instantiates a new ComponentArtifact object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewComponentArtifactWithDefaults

`func NewComponentArtifactWithDefaults() *ComponentArtifact`

NewComponentArtifactWithDefaults instantiates a new ComponentArtifact object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetClassifier

`func (o *ComponentArtifact) GetClassifier() string`

GetClassifier returns the Classifier field if non-nil, zero value otherwise.

### GetClassifierOk

`func (o *ComponentArtifact) GetClassifierOk() (*string, bool)`

GetClassifierOk returns a tuple with the Classifier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClassifier

`func (o *ComponentArtifact) SetClassifier(v string)`

SetClassifier sets Classifier field to given value.

### HasClassifier

`func (o *ComponentArtifact) HasClassifier() bool`

HasClassifier returns a boolean if a field has been set.

### GetExtension

`func (o *ComponentArtifact) GetExtension() string`

GetExtension returns the Extension field if non-nil, zero value otherwise.

### GetExtensionOk

`func (o *ComponentArtifact) GetExtensionOk() (*string, bool)`

GetExtensionOk returns a tuple with the Extension field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExtension

`func (o *ComponentArtifact) SetExtension(v string)`

SetExtension sets Extension field to given value.

### HasExtension

`func (o *ComponentArtifact) HasExtension() bool`

HasExtension returns a boolean if a field has been set.

### GetPublishedDate

`func (o *ComponentArtifact) GetPublishedDate() time.Time`

GetPublishedDate returns the PublishedDate field if non-nil, zero value otherwise.

### GetPublishedDateOk

`func (o *ComponentArtifact) GetPublishedDateOk() (*time.Time, bool)`

GetPublishedDateOk returns a tuple with the PublishedDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublishedDate

`func (o *ComponentArtifact) SetPublishedDate(v time.Time)`

SetPublishedDate sets PublishedDate field to given value.

### HasPublishedDate

`func (o *ComponentArtifact) HasPublishedDate() bool`

HasPublishedDate returns a boolean if a field has been set.

### GetRefids

`func (o *ComponentArtifact) GetRefids() []Refid`

GetRefids returns the Refids field if non-nil, zero value otherwise.

### GetRefidsOk

`func (o *ComponentArtifact) GetRefidsOk() (*[]Refid, bool)`

GetRefidsOk returns a tuple with the Refids field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRefids

`func (o *ComponentArtifact) SetRefids(v []Refid)`

SetRefids sets Refids field to given value.

### HasRefids

`func (o *ComponentArtifact) HasRefids() bool`

HasRefids returns a boolean if a field has been set.

### GetSha1

`func (o *ComponentArtifact) GetSha1() string`

GetSha1 returns the Sha1 field if non-nil, zero value otherwise.

### GetSha1Ok

`func (o *ComponentArtifact) GetSha1Ok() (*string, bool)`

GetSha1Ok returns a tuple with the Sha1 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSha1

`func (o *ComponentArtifact) SetSha1(v string)`

SetSha1 sets Sha1 field to given value.

### HasSha1

`func (o *ComponentArtifact) HasSha1() bool`

HasSha1 returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


