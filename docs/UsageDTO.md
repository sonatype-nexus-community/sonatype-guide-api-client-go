# UsageDTO

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CreditsTotal** | Pointer to **float32** |  | [optional] 
**CreditsUsed** | Pointer to **float32** |  | [optional] 
**CurrentPeriod** | Pointer to [**PeriodDTO**](PeriodDTO.md) |  | [optional] 
**IsOssiOrigin** | Pointer to **bool** |  | [optional] 

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

`func (o *UsageDTO) GetCreditsTotal() float32`

GetCreditsTotal returns the CreditsTotal field if non-nil, zero value otherwise.

### GetCreditsTotalOk

`func (o *UsageDTO) GetCreditsTotalOk() (*float32, bool)`

GetCreditsTotalOk returns a tuple with the CreditsTotal field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreditsTotal

`func (o *UsageDTO) SetCreditsTotal(v float32)`

SetCreditsTotal sets CreditsTotal field to given value.

### HasCreditsTotal

`func (o *UsageDTO) HasCreditsTotal() bool`

HasCreditsTotal returns a boolean if a field has been set.

### GetCreditsUsed

`func (o *UsageDTO) GetCreditsUsed() float32`

GetCreditsUsed returns the CreditsUsed field if non-nil, zero value otherwise.

### GetCreditsUsedOk

`func (o *UsageDTO) GetCreditsUsedOk() (*float32, bool)`

GetCreditsUsedOk returns a tuple with the CreditsUsed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreditsUsed

`func (o *UsageDTO) SetCreditsUsed(v float32)`

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

### GetIsOssiOrigin

`func (o *UsageDTO) GetIsOssiOrigin() bool`

GetIsOssiOrigin returns the IsOssiOrigin field if non-nil, zero value otherwise.

### GetIsOssiOriginOk

`func (o *UsageDTO) GetIsOssiOriginOk() (*bool, bool)`

GetIsOssiOriginOk returns a tuple with the IsOssiOrigin field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsOssiOrigin

`func (o *UsageDTO) SetIsOssiOrigin(v bool)`

SetIsOssiOrigin sets IsOssiOrigin field to given value.

### HasIsOssiOrigin

`func (o *UsageDTO) HasIsOssiOrigin() bool`

HasIsOssiOrigin returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


