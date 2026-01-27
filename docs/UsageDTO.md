# UsageDTO

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CreditsTotal** | Pointer to **int32** |  | [optional] 
**CreditsUsed** | Pointer to **int32** |  | [optional] 
**CurrentPeriod** | Pointer to [**PeriodDTO**](PeriodDTO.md) |  | [optional] 

## Methods

### NewUsageDTO

`func NewUsageDTO() *UsageDTO`

NewUsageDTO instantiates a new UsageDTO object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUsageDTOWithDefaults

`func NewUsageDTOWithDefaults() *UsageDTO`

NewUsageDTOWithDefaults instantiates a new UsageDTO object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCreditsTotal

`func (o *UsageDTO) GetCreditsTotal() int32`

GetCreditsTotal returns the CreditsTotal field if non-nil, zero value otherwise.

### GetCreditsTotalOk

`func (o *UsageDTO) GetCreditsTotalOk() (*int32, bool)`

GetCreditsTotalOk returns a tuple with the CreditsTotal field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreditsTotal

`func (o *UsageDTO) SetCreditsTotal(v int32)`

SetCreditsTotal sets CreditsTotal field to given value.

### HasCreditsTotal

`func (o *UsageDTO) HasCreditsTotal() bool`

HasCreditsTotal returns a boolean if a field has been set.

### GetCreditsUsed

`func (o *UsageDTO) GetCreditsUsed() int32`

GetCreditsUsed returns the CreditsUsed field if non-nil, zero value otherwise.

### GetCreditsUsedOk

`func (o *UsageDTO) GetCreditsUsedOk() (*int32, bool)`

GetCreditsUsedOk returns a tuple with the CreditsUsed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreditsUsed

`func (o *UsageDTO) SetCreditsUsed(v int32)`

SetCreditsUsed sets CreditsUsed field to given value.

### HasCreditsUsed

`func (o *UsageDTO) HasCreditsUsed() bool`

HasCreditsUsed returns a boolean if a field has been set.

### GetCurrentPeriod

`func (o *UsageDTO) GetCurrentPeriod() PeriodDTO`

GetCurrentPeriod returns the CurrentPeriod field if non-nil, zero value otherwise.

### GetCurrentPeriodOk

`func (o *UsageDTO) GetCurrentPeriodOk() (*PeriodDTO, bool)`

GetCurrentPeriodOk returns a tuple with the CurrentPeriod field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrentPeriod

`func (o *UsageDTO) SetCurrentPeriod(v PeriodDTO)`

SetCurrentPeriod sets CurrentPeriod field to given value.

### HasCurrentPeriod

`func (o *UsageDTO) HasCurrentPeriod() bool`

HasCurrentPeriod returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


