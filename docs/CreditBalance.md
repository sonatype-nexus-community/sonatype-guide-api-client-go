# CreditBalance

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CreditsRemaining** | Pointer to **int32** |  | [optional] 
**CreditsUsed** | Pointer to **int32** |  | [optional] 
**PeriodEnd** | Pointer to **string** |  | [optional] 
**PeriodStart** | Pointer to **string** |  | [optional] 
**PlanTier** | Pointer to **string** |  | [optional] 
**ResetDate** | Pointer to **string** |  | [optional] 
**Status** | Pointer to **string** |  | [optional] 
**TotalCredits** | Pointer to **int32** |  | [optional] 
**UsagePercentage** | Pointer to **int32** |  | [optional] 

## Methods

### NewCreditBalance

`func NewCreditBalance() *CreditBalance`

NewCreditBalance instantiates a new CreditBalance object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreditBalanceWithDefaults

`func NewCreditBalanceWithDefaults() *CreditBalance`

NewCreditBalanceWithDefaults instantiates a new CreditBalance object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCreditsRemaining

`func (o *CreditBalance) GetCreditsRemaining() int32`

GetCreditsRemaining returns the CreditsRemaining field if non-nil, zero value otherwise.

### GetCreditsRemainingOk

`func (o *CreditBalance) GetCreditsRemainingOk() (*int32, bool)`

GetCreditsRemainingOk returns a tuple with the CreditsRemaining field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreditsRemaining

`func (o *CreditBalance) SetCreditsRemaining(v int32)`

SetCreditsRemaining sets CreditsRemaining field to given value.

### HasCreditsRemaining

`func (o *CreditBalance) HasCreditsRemaining() bool`

HasCreditsRemaining returns a boolean if a field has been set.

### GetCreditsUsed

`func (o *CreditBalance) GetCreditsUsed() int32`

GetCreditsUsed returns the CreditsUsed field if non-nil, zero value otherwise.

### GetCreditsUsedOk

`func (o *CreditBalance) GetCreditsUsedOk() (*int32, bool)`

GetCreditsUsedOk returns a tuple with the CreditsUsed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreditsUsed

`func (o *CreditBalance) SetCreditsUsed(v int32)`

SetCreditsUsed sets CreditsUsed field to given value.

### HasCreditsUsed

`func (o *CreditBalance) HasCreditsUsed() bool`

HasCreditsUsed returns a boolean if a field has been set.

### GetPeriodEnd

`func (o *CreditBalance) GetPeriodEnd() string`

GetPeriodEnd returns the PeriodEnd field if non-nil, zero value otherwise.

### GetPeriodEndOk

`func (o *CreditBalance) GetPeriodEndOk() (*string, bool)`

GetPeriodEndOk returns a tuple with the PeriodEnd field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeriodEnd

`func (o *CreditBalance) SetPeriodEnd(v string)`

SetPeriodEnd sets PeriodEnd field to given value.

### HasPeriodEnd

`func (o *CreditBalance) HasPeriodEnd() bool`

HasPeriodEnd returns a boolean if a field has been set.

### GetPeriodStart

`func (o *CreditBalance) GetPeriodStart() string`

GetPeriodStart returns the PeriodStart field if non-nil, zero value otherwise.

### GetPeriodStartOk

`func (o *CreditBalance) GetPeriodStartOk() (*string, bool)`

GetPeriodStartOk returns a tuple with the PeriodStart field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeriodStart

`func (o *CreditBalance) SetPeriodStart(v string)`

SetPeriodStart sets PeriodStart field to given value.

### HasPeriodStart

`func (o *CreditBalance) HasPeriodStart() bool`

HasPeriodStart returns a boolean if a field has been set.

### GetPlanTier

`func (o *CreditBalance) GetPlanTier() string`

GetPlanTier returns the PlanTier field if non-nil, zero value otherwise.

### GetPlanTierOk

`func (o *CreditBalance) GetPlanTierOk() (*string, bool)`

GetPlanTierOk returns a tuple with the PlanTier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlanTier

`func (o *CreditBalance) SetPlanTier(v string)`

SetPlanTier sets PlanTier field to given value.

### HasPlanTier

`func (o *CreditBalance) HasPlanTier() bool`

HasPlanTier returns a boolean if a field has been set.

### GetResetDate

`func (o *CreditBalance) GetResetDate() string`

GetResetDate returns the ResetDate field if non-nil, zero value otherwise.

### GetResetDateOk

`func (o *CreditBalance) GetResetDateOk() (*string, bool)`

GetResetDateOk returns a tuple with the ResetDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResetDate

`func (o *CreditBalance) SetResetDate(v string)`

SetResetDate sets ResetDate field to given value.

### HasResetDate

`func (o *CreditBalance) HasResetDate() bool`

HasResetDate returns a boolean if a field has been set.

### GetStatus

`func (o *CreditBalance) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *CreditBalance) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *CreditBalance) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *CreditBalance) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetTotalCredits

`func (o *CreditBalance) GetTotalCredits() int32`

GetTotalCredits returns the TotalCredits field if non-nil, zero value otherwise.

### GetTotalCreditsOk

`func (o *CreditBalance) GetTotalCreditsOk() (*int32, bool)`

GetTotalCreditsOk returns a tuple with the TotalCredits field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalCredits

`func (o *CreditBalance) SetTotalCredits(v int32)`

SetTotalCredits sets TotalCredits field to given value.

### HasTotalCredits

`func (o *CreditBalance) HasTotalCredits() bool`

HasTotalCredits returns a boolean if a field has been set.

### GetUsagePercentage

`func (o *CreditBalance) GetUsagePercentage() int32`

GetUsagePercentage returns the UsagePercentage field if non-nil, zero value otherwise.

### GetUsagePercentageOk

`func (o *CreditBalance) GetUsagePercentageOk() (*int32, bool)`

GetUsagePercentageOk returns a tuple with the UsagePercentage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsagePercentage

`func (o *CreditBalance) SetUsagePercentage(v int32)`

SetUsagePercentage sets UsagePercentage field to given value.

### HasUsagePercentage

`func (o *CreditBalance) HasUsagePercentage() bool`

HasUsagePercentage returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


