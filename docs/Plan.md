# Plan

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Billing** | Pointer to **string** |  | [optional] 
**Credits** | Pointer to **int32** |  | [optional] 
**IsFreePlan** | Pointer to **bool** |  | [optional] 
**Name** | Pointer to **string** |  | [optional] 
**NextBill** | Pointer to **string** |  | [optional] 
**Price** | Pointer to **float64** |  | [optional] 
**Status** | Pointer to **string** |  | [optional] 

## Methods

### NewPlan

`func NewPlan() *Plan`

NewPlan instantiates a new Plan object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPlanWithDefaults

`func NewPlanWithDefaults() *Plan`

NewPlanWithDefaults instantiates a new Plan object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBilling

`func (o *Plan) GetBilling() string`

GetBilling returns the Billing field if non-nil, zero value otherwise.

### GetBillingOk

`func (o *Plan) GetBillingOk() (*string, bool)`

GetBillingOk returns a tuple with the Billing field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBilling

`func (o *Plan) SetBilling(v string)`

SetBilling sets Billing field to given value.

### HasBilling

`func (o *Plan) HasBilling() bool`

HasBilling returns a boolean if a field has been set.

### GetCredits

`func (o *Plan) GetCredits() int32`

GetCredits returns the Credits field if non-nil, zero value otherwise.

### GetCreditsOk

`func (o *Plan) GetCreditsOk() (*int32, bool)`

GetCreditsOk returns a tuple with the Credits field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCredits

`func (o *Plan) SetCredits(v int32)`

SetCredits sets Credits field to given value.

### HasCredits

`func (o *Plan) HasCredits() bool`

HasCredits returns a boolean if a field has been set.

### GetIsFreePlan

`func (o *Plan) GetIsFreePlan() bool`

GetIsFreePlan returns the IsFreePlan field if non-nil, zero value otherwise.

### GetIsFreePlanOk

`func (o *Plan) GetIsFreePlanOk() (*bool, bool)`

GetIsFreePlanOk returns a tuple with the IsFreePlan field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsFreePlan

`func (o *Plan) SetIsFreePlan(v bool)`

SetIsFreePlan sets IsFreePlan field to given value.

### HasIsFreePlan

`func (o *Plan) HasIsFreePlan() bool`

HasIsFreePlan returns a boolean if a field has been set.

### GetName

`func (o *Plan) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *Plan) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *Plan) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *Plan) HasName() bool`

HasName returns a boolean if a field has been set.

### GetNextBill

`func (o *Plan) GetNextBill() string`

GetNextBill returns the NextBill field if non-nil, zero value otherwise.

### GetNextBillOk

`func (o *Plan) GetNextBillOk() (*string, bool)`

GetNextBillOk returns a tuple with the NextBill field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextBill

`func (o *Plan) SetNextBill(v string)`

SetNextBill sets NextBill field to given value.

### HasNextBill

`func (o *Plan) HasNextBill() bool`

HasNextBill returns a boolean if a field has been set.

### GetPrice

`func (o *Plan) GetPrice() float64`

GetPrice returns the Price field if non-nil, zero value otherwise.

### GetPriceOk

`func (o *Plan) GetPriceOk() (*float64, bool)`

GetPriceOk returns a tuple with the Price field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrice

`func (o *Plan) SetPrice(v float64)`

SetPrice sets Price field to given value.

### HasPrice

`func (o *Plan) HasPrice() bool`

HasPrice returns a boolean if a field has been set.

### GetStatus

`func (o *Plan) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *Plan) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *Plan) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *Plan) HasStatus() bool`

HasStatus returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


