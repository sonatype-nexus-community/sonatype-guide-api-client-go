# OssiUsageHistoryDTO

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**IsEstimate** | Pointer to **bool** |  | [optional] 
**Months** | Pointer to [**[]OssiMonthlyUsage**](OssiMonthlyUsage.md) |  | [optional] 
**Summary** | Pointer to [**OssiUsageSummary**](OssiUsageSummary.md) |  | [optional] 

## Methods

### NewOssiUsageHistoryDTO

`func NewOssiUsageHistoryDTO() *OssiUsageHistoryDTO`

NewOssiUsageHistoryDTO instantiates a new OssiUsageHistoryDTO object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOssiUsageHistoryDTOWithDefaults

`func NewOssiUsageHistoryDTOWithDefaults() *OssiUsageHistoryDTO`

NewOssiUsageHistoryDTOWithDefaults instantiates a new OssiUsageHistoryDTO object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIsEstimate

`func (o *OssiUsageHistoryDTO) GetIsEstimate() bool`

GetIsEstimate returns the IsEstimate field if non-nil, zero value otherwise.

### GetIsEstimateOk

`func (o *OssiUsageHistoryDTO) GetIsEstimateOk() (*bool, bool)`

GetIsEstimateOk returns a tuple with the IsEstimate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsEstimate

`func (o *OssiUsageHistoryDTO) SetIsEstimate(v bool)`

SetIsEstimate sets IsEstimate field to given value.

### HasIsEstimate

`func (o *OssiUsageHistoryDTO) HasIsEstimate() bool`

HasIsEstimate returns a boolean if a field has been set.

### GetMonths

`func (o *OssiUsageHistoryDTO) GetMonths() []OssiMonthlyUsage`

GetMonths returns the Months field if non-nil, zero value otherwise.

### GetMonthsOk

`func (o *OssiUsageHistoryDTO) GetMonthsOk() (*[]OssiMonthlyUsage, bool)`

GetMonthsOk returns a tuple with the Months field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMonths

`func (o *OssiUsageHistoryDTO) SetMonths(v []OssiMonthlyUsage)`

SetMonths sets Months field to given value.

### HasMonths

`func (o *OssiUsageHistoryDTO) HasMonths() bool`

HasMonths returns a boolean if a field has been set.

### GetSummary

`func (o *OssiUsageHistoryDTO) GetSummary() OssiUsageSummary`

GetSummary returns the Summary field if non-nil, zero value otherwise.

### GetSummaryOk

`func (o *OssiUsageHistoryDTO) GetSummaryOk() (*OssiUsageSummary, bool)`

GetSummaryOk returns a tuple with the Summary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSummary

`func (o *OssiUsageHistoryDTO) SetSummary(v OssiUsageSummary)`

SetSummary sets Summary field to given value.

### HasSummary

`func (o *OssiUsageHistoryDTO) HasSummary() bool`

HasSummary returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


