# CumulativeCreditUsage

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CreditLimit** | Pointer to **float32** |  | [optional] 
**DailyAverage** | Pointer to **float32** |  | [optional] 
**DailyUsage** | Pointer to [**[]DailyCreditUsage**](DailyCreditUsage.md) |  | [optional] 
**PeakDay** | Pointer to **float32** |  | [optional] 
**TotalCreditsUsed** | Pointer to **float32** |  | [optional] 

## Methods

### NewCumulativeCreditUsage

`func NewCumulativeCreditUsage() *CumulativeCreditUsage`

NewCumulativeCreditUsage instantiates a new CumulativeCreditUsage object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCumulativeCreditUsageWithDefaults

`func NewCumulativeCreditUsageWithDefaults() *CumulativeCreditUsage`

NewCumulativeCreditUsageWithDefaults instantiates a new CumulativeCreditUsage object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCreditLimit

`func (o *CumulativeCreditUsage) GetCreditLimit() float32`

GetCreditLimit returns the CreditLimit field if non-nil, zero value otherwise.

### GetCreditLimitOk

`func (o *CumulativeCreditUsage) GetCreditLimitOk() (*float32, bool)`

GetCreditLimitOk returns a tuple with the CreditLimit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreditLimit

`func (o *CumulativeCreditUsage) SetCreditLimit(v float32)`

SetCreditLimit sets CreditLimit field to given value.

### HasCreditLimit

`func (o *CumulativeCreditUsage) HasCreditLimit() bool`

HasCreditLimit returns a boolean if a field has been set.

### GetDailyAverage

`func (o *CumulativeCreditUsage) GetDailyAverage() float32`

GetDailyAverage returns the DailyAverage field if non-nil, zero value otherwise.

### GetDailyAverageOk

`func (o *CumulativeCreditUsage) GetDailyAverageOk() (*float32, bool)`

GetDailyAverageOk returns a tuple with the DailyAverage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDailyAverage

`func (o *CumulativeCreditUsage) SetDailyAverage(v float32)`

SetDailyAverage sets DailyAverage field to given value.

### HasDailyAverage

`func (o *CumulativeCreditUsage) HasDailyAverage() bool`

HasDailyAverage returns a boolean if a field has been set.

### GetDailyUsage

`func (o *CumulativeCreditUsage) GetDailyUsage() []DailyCreditUsage`

GetDailyUsage returns the DailyUsage field if non-nil, zero value otherwise.

### GetDailyUsageOk

`func (o *CumulativeCreditUsage) GetDailyUsageOk() (*[]DailyCreditUsage, bool)`

GetDailyUsageOk returns a tuple with the DailyUsage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDailyUsage

`func (o *CumulativeCreditUsage) SetDailyUsage(v []DailyCreditUsage)`

SetDailyUsage sets DailyUsage field to given value.

### HasDailyUsage

`func (o *CumulativeCreditUsage) HasDailyUsage() bool`

HasDailyUsage returns a boolean if a field has been set.

### GetPeakDay

`func (o *CumulativeCreditUsage) GetPeakDay() float32`

GetPeakDay returns the PeakDay field if non-nil, zero value otherwise.

### GetPeakDayOk

`func (o *CumulativeCreditUsage) GetPeakDayOk() (*float32, bool)`

GetPeakDayOk returns a tuple with the PeakDay field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeakDay

`func (o *CumulativeCreditUsage) SetPeakDay(v float32)`

SetPeakDay sets PeakDay field to given value.

### HasPeakDay

`func (o *CumulativeCreditUsage) HasPeakDay() bool`

HasPeakDay returns a boolean if a field has been set.

### GetTotalCreditsUsed

`func (o *CumulativeCreditUsage) GetTotalCreditsUsed() float32`

GetTotalCreditsUsed returns the TotalCreditsUsed field if non-nil, zero value otherwise.

### GetTotalCreditsUsedOk

`func (o *CumulativeCreditUsage) GetTotalCreditsUsedOk() (*float32, bool)`

GetTotalCreditsUsedOk returns a tuple with the TotalCreditsUsed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalCreditsUsed

`func (o *CumulativeCreditUsage) SetTotalCreditsUsed(v float32)`

SetTotalCreditsUsed sets TotalCreditsUsed field to given value.

### HasTotalCreditsUsed

`func (o *CumulativeCreditUsage) HasTotalCreditsUsed() bool`

HasTotalCreditsUsed returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


