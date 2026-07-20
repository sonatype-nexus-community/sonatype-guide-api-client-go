# RecommendationRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Classifier** | Pointer to **string** |  | [optional] 
**Extension** | Pointer to **string** |  | [optional] 
**Purl** | Pointer to **string** |  | [optional] 

## Methods

### NewRecommendationRequest

`func NewRecommendationRequest() *RecommendationRequest`

NewRecommendationRequest instantiates a new RecommendationRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRecommendationRequestWithDefaults

`func NewRecommendationRequestWithDefaults() *RecommendationRequest`

NewRecommendationRequestWithDefaults instantiates a new RecommendationRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetClassifier

`func (o *RecommendationRequest) GetClassifier() string`

GetClassifier returns the Classifier field if non-nil, zero value otherwise.

### GetClassifierOk

`func (o *RecommendationRequest) GetClassifierOk() (*string, bool)`

GetClassifierOk returns a tuple with the Classifier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClassifier

`func (o *RecommendationRequest) SetClassifier(v string)`

SetClassifier sets Classifier field to given value.

### HasClassifier

`func (o *RecommendationRequest) HasClassifier() bool`

HasClassifier returns a boolean if a field has been set.

### GetExtension

`func (o *RecommendationRequest) GetExtension() string`

GetExtension returns the Extension field if non-nil, zero value otherwise.

### GetExtensionOk

`func (o *RecommendationRequest) GetExtensionOk() (*string, bool)`

GetExtensionOk returns a tuple with the Extension field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExtension

`func (o *RecommendationRequest) SetExtension(v string)`

SetExtension sets Extension field to given value.

### HasExtension

`func (o *RecommendationRequest) HasExtension() bool`

HasExtension returns a boolean if a field has been set.

### GetPurl

`func (o *RecommendationRequest) GetPurl() string`

GetPurl returns the Purl field if non-nil, zero value otherwise.

### GetPurlOk

`func (o *RecommendationRequest) GetPurlOk() (*string, bool)`

GetPurlOk returns a tuple with the Purl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPurl

`func (o *RecommendationRequest) SetPurl(v string)`

SetPurl sets Purl field to given value.

### HasPurl

`func (o *RecommendationRequest) HasPurl() bool`

HasPurl returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


