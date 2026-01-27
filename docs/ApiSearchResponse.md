# ApiSearchResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Aggregations** | Pointer to **map[string]map[string]int64** |  | [optional] 
**Hits** | Pointer to **[]interface{}** |  | [optional] 
**Limit** | Pointer to **int32** |  | [optional] 
**Offset** | Pointer to **int32** |  | [optional] 
**Total** | Pointer to **int64** |  | [optional] 

## Methods

### NewApiSearchResponse

`func NewApiSearchResponse() *ApiSearchResponse`

NewApiSearchResponse instantiates a new ApiSearchResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewApiSearchResponseWithDefaults

`func NewApiSearchResponseWithDefaults() *ApiSearchResponse`

NewApiSearchResponseWithDefaults instantiates a new ApiSearchResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAggregations

`func (o *ApiSearchResponse) GetAggregations() map[string]map[string]int64`

GetAggregations returns the Aggregations field if non-nil, zero value otherwise.

### GetAggregationsOk

`func (o *ApiSearchResponse) GetAggregationsOk() (*map[string]map[string]int64, bool)`

GetAggregationsOk returns a tuple with the Aggregations field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAggregations

`func (o *ApiSearchResponse) SetAggregations(v map[string]map[string]int64)`

SetAggregations sets Aggregations field to given value.

### HasAggregations

`func (o *ApiSearchResponse) HasAggregations() bool`

HasAggregations returns a boolean if a field has been set.

### GetHits

`func (o *ApiSearchResponse) GetHits() []interface{}`

GetHits returns the Hits field if non-nil, zero value otherwise.

### GetHitsOk

`func (o *ApiSearchResponse) GetHitsOk() (*[]interface{}, bool)`

GetHitsOk returns a tuple with the Hits field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHits

`func (o *ApiSearchResponse) SetHits(v []interface{})`

SetHits sets Hits field to given value.

### HasHits

`func (o *ApiSearchResponse) HasHits() bool`

HasHits returns a boolean if a field has been set.

### GetLimit

`func (o *ApiSearchResponse) GetLimit() int32`

GetLimit returns the Limit field if non-nil, zero value otherwise.

### GetLimitOk

`func (o *ApiSearchResponse) GetLimitOk() (*int32, bool)`

GetLimitOk returns a tuple with the Limit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLimit

`func (o *ApiSearchResponse) SetLimit(v int32)`

SetLimit sets Limit field to given value.

### HasLimit

`func (o *ApiSearchResponse) HasLimit() bool`

HasLimit returns a boolean if a field has been set.

### GetOffset

`func (o *ApiSearchResponse) GetOffset() int32`

GetOffset returns the Offset field if non-nil, zero value otherwise.

### GetOffsetOk

`func (o *ApiSearchResponse) GetOffsetOk() (*int32, bool)`

GetOffsetOk returns a tuple with the Offset field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOffset

`func (o *ApiSearchResponse) SetOffset(v int32)`

SetOffset sets Offset field to given value.

### HasOffset

`func (o *ApiSearchResponse) HasOffset() bool`

HasOffset returns a boolean if a field has been set.

### GetTotal

`func (o *ApiSearchResponse) GetTotal() int64`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *ApiSearchResponse) GetTotalOk() (*int64, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *ApiSearchResponse) SetTotal(v int64)`

SetTotal sets Total field to given value.

### HasTotal

`func (o *ApiSearchResponse) HasTotal() bool`

HasTotal returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


