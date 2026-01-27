# ApiSearchResponseComponentDetailDocument

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Aggregations** | Pointer to **map[string]map[string]int64** |  | [optional] 
**Hits** | Pointer to [**[]ComponentDetailDocument**](ComponentDetailDocument.md) |  | [optional] 
**Limit** | Pointer to **int32** |  | [optional] 
**Offset** | Pointer to **int32** |  | [optional] 
**Total** | Pointer to **int64** |  | [optional] 

## Methods

### NewApiSearchResponseComponentDetailDocument

`func NewApiSearchResponseComponentDetailDocument() *ApiSearchResponseComponentDetailDocument`

NewApiSearchResponseComponentDetailDocument instantiates a new ApiSearchResponseComponentDetailDocument object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewApiSearchResponseComponentDetailDocumentWithDefaults

`func NewApiSearchResponseComponentDetailDocumentWithDefaults() *ApiSearchResponseComponentDetailDocument`

NewApiSearchResponseComponentDetailDocumentWithDefaults instantiates a new ApiSearchResponseComponentDetailDocument object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAggregations

`func (o *ApiSearchResponseComponentDetailDocument) GetAggregations() map[string]map[string]int64`

GetAggregations returns the Aggregations field if non-nil, zero value otherwise.

### GetAggregationsOk

`func (o *ApiSearchResponseComponentDetailDocument) GetAggregationsOk() (*map[string]map[string]int64, bool)`

GetAggregationsOk returns a tuple with the Aggregations field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAggregations

`func (o *ApiSearchResponseComponentDetailDocument) SetAggregations(v map[string]map[string]int64)`

SetAggregations sets Aggregations field to given value.

### HasAggregations

`func (o *ApiSearchResponseComponentDetailDocument) HasAggregations() bool`

HasAggregations returns a boolean if a field has been set.

### GetHits

`func (o *ApiSearchResponseComponentDetailDocument) GetHits() []ComponentDetailDocument`

GetHits returns the Hits field if non-nil, zero value otherwise.

### GetHitsOk

`func (o *ApiSearchResponseComponentDetailDocument) GetHitsOk() (*[]ComponentDetailDocument, bool)`

GetHitsOk returns a tuple with the Hits field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHits

`func (o *ApiSearchResponseComponentDetailDocument) SetHits(v []ComponentDetailDocument)`

SetHits sets Hits field to given value.

### HasHits

`func (o *ApiSearchResponseComponentDetailDocument) HasHits() bool`

HasHits returns a boolean if a field has been set.

### GetLimit

`func (o *ApiSearchResponseComponentDetailDocument) GetLimit() int32`

GetLimit returns the Limit field if non-nil, zero value otherwise.

### GetLimitOk

`func (o *ApiSearchResponseComponentDetailDocument) GetLimitOk() (*int32, bool)`

GetLimitOk returns a tuple with the Limit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLimit

`func (o *ApiSearchResponseComponentDetailDocument) SetLimit(v int32)`

SetLimit sets Limit field to given value.

### HasLimit

`func (o *ApiSearchResponseComponentDetailDocument) HasLimit() bool`

HasLimit returns a boolean if a field has been set.

### GetOffset

`func (o *ApiSearchResponseComponentDetailDocument) GetOffset() int32`

GetOffset returns the Offset field if non-nil, zero value otherwise.

### GetOffsetOk

`func (o *ApiSearchResponseComponentDetailDocument) GetOffsetOk() (*int32, bool)`

GetOffsetOk returns a tuple with the Offset field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOffset

`func (o *ApiSearchResponseComponentDetailDocument) SetOffset(v int32)`

SetOffset sets Offset field to given value.

### HasOffset

`func (o *ApiSearchResponseComponentDetailDocument) HasOffset() bool`

HasOffset returns a boolean if a field has been set.

### GetTotal

`func (o *ApiSearchResponseComponentDetailDocument) GetTotal() int64`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *ApiSearchResponseComponentDetailDocument) GetTotalOk() (*int64, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *ApiSearchResponseComponentDetailDocument) SetTotal(v int64)`

SetTotal sets Total field to given value.

### HasTotal

`func (o *ApiSearchResponseComponentDetailDocument) HasTotal() bool`

HasTotal returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


