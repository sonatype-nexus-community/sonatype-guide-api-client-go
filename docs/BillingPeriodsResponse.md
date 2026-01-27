# BillingPeriodsResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CurrentPeriod** | Pointer to [**BillingPeriod**](BillingPeriod.md) |  | [optional] 
**Periods** | Pointer to [**[]BillingPeriod**](BillingPeriod.md) |  | [optional] 

## Methods

### NewBillingPeriodsResponse

`func NewBillingPeriodsResponse() *BillingPeriodsResponse`

NewBillingPeriodsResponse instantiates a new BillingPeriodsResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBillingPeriodsResponseWithDefaults

`func NewBillingPeriodsResponseWithDefaults() *BillingPeriodsResponse`

NewBillingPeriodsResponseWithDefaults instantiates a new BillingPeriodsResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCurrentPeriod

`func (o *BillingPeriodsResponse) GetCurrentPeriod() BillingPeriod`

GetCurrentPeriod returns the CurrentPeriod field if non-nil, zero value otherwise.

### GetCurrentPeriodOk

`func (o *BillingPeriodsResponse) GetCurrentPeriodOk() (*BillingPeriod, bool)`

GetCurrentPeriodOk returns a tuple with the CurrentPeriod field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrentPeriod

`func (o *BillingPeriodsResponse) SetCurrentPeriod(v BillingPeriod)`

SetCurrentPeriod sets CurrentPeriod field to given value.

### HasCurrentPeriod

`func (o *BillingPeriodsResponse) HasCurrentPeriod() bool`

HasCurrentPeriod returns a boolean if a field has been set.

### GetPeriods

`func (o *BillingPeriodsResponse) GetPeriods() []BillingPeriod`

GetPeriods returns the Periods field if non-nil, zero value otherwise.

### GetPeriodsOk

`func (o *BillingPeriodsResponse) GetPeriodsOk() (*[]BillingPeriod, bool)`

GetPeriodsOk returns a tuple with the Periods field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeriods

`func (o *BillingPeriodsResponse) SetPeriods(v []BillingPeriod)`

SetPeriods sets Periods field to given value.

### HasPeriods

`func (o *BillingPeriodsResponse) HasPeriods() bool`

HasPeriods returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


