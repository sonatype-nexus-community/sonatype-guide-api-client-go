# RecommendationResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**FromVersion** | Pointer to [**FromVersion**](FromVersion.md) |  | [optional] 
**Outcome** | Pointer to **string** |  | [optional] 
**ToVersions** | Pointer to [**[]RecommendedVersion**](RecommendedVersion.md) |  | [optional] 

## Methods

### NewRecommendationResponse

`func NewRecommendationResponse() *RecommendationResponse`

NewRecommendationResponse instantiates a new RecommendationResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRecommendationResponseWithDefaults

`func NewRecommendationResponseWithDefaults() *RecommendationResponse`

NewRecommendationResponseWithDefaults instantiates a new RecommendationResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetFromVersion

`func (o *RecommendationResponse) GetFromVersion() FromVersion`

GetFromVersion returns the FromVersion field if non-nil, zero value otherwise.

### GetFromVersionOk

`func (o *RecommendationResponse) GetFromVersionOk() (*FromVersion, bool)`

GetFromVersionOk returns a tuple with the FromVersion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFromVersion

`func (o *RecommendationResponse) SetFromVersion(v FromVersion)`

SetFromVersion sets FromVersion field to given value.

### HasFromVersion

`func (o *RecommendationResponse) HasFromVersion() bool`

HasFromVersion returns a boolean if a field has been set.

### GetOutcome

`func (o *RecommendationResponse) GetOutcome() string`

GetOutcome returns the Outcome field if non-nil, zero value otherwise.

### GetOutcomeOk

`func (o *RecommendationResponse) GetOutcomeOk() (*string, bool)`

GetOutcomeOk returns a tuple with the Outcome field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutcome

`func (o *RecommendationResponse) SetOutcome(v string)`

SetOutcome sets Outcome field to given value.

### HasOutcome

`func (o *RecommendationResponse) HasOutcome() bool`

HasOutcome returns a boolean if a field has been set.

### GetToVersions

`func (o *RecommendationResponse) GetToVersions() []RecommendedVersion`

GetToVersions returns the ToVersions field if non-nil, zero value otherwise.

### GetToVersionsOk

`func (o *RecommendationResponse) GetToVersionsOk() (*[]RecommendedVersion, bool)`

GetToVersionsOk returns a tuple with the ToVersions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetToVersions

`func (o *RecommendationResponse) SetToVersions(v []RecommendedVersion)`

SetToVersions sets ToVersions field to given value.

### HasToVersions

`func (o *RecommendationResponse) HasToVersions() bool`

HasToVersions returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


