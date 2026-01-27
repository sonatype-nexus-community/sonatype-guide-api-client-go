# SubscriptionDetailsResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CreditUsage** | Pointer to [**CreditUsage**](CreditUsage.md) |  | [optional] 
**Plan** | Pointer to [**Plan**](Plan.md) |  | [optional] 

## Methods

### NewSubscriptionDetailsResponse

`func NewSubscriptionDetailsResponse() *SubscriptionDetailsResponse`

NewSubscriptionDetailsResponse instantiates a new SubscriptionDetailsResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSubscriptionDetailsResponseWithDefaults

`func NewSubscriptionDetailsResponseWithDefaults() *SubscriptionDetailsResponse`

NewSubscriptionDetailsResponseWithDefaults instantiates a new SubscriptionDetailsResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCreditUsage

`func (o *SubscriptionDetailsResponse) GetCreditUsage() CreditUsage`

GetCreditUsage returns the CreditUsage field if non-nil, zero value otherwise.

### GetCreditUsageOk

`func (o *SubscriptionDetailsResponse) GetCreditUsageOk() (*CreditUsage, bool)`

GetCreditUsageOk returns a tuple with the CreditUsage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreditUsage

`func (o *SubscriptionDetailsResponse) SetCreditUsage(v CreditUsage)`

SetCreditUsage sets CreditUsage field to given value.

### HasCreditUsage

`func (o *SubscriptionDetailsResponse) HasCreditUsage() bool`

HasCreditUsage returns a boolean if a field has been set.

### GetPlan

`func (o *SubscriptionDetailsResponse) GetPlan() Plan`

GetPlan returns the Plan field if non-nil, zero value otherwise.

### GetPlanOk

`func (o *SubscriptionDetailsResponse) GetPlanOk() (*Plan, bool)`

GetPlanOk returns a tuple with the Plan field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlan

`func (o *SubscriptionDetailsResponse) SetPlan(v Plan)`

SetPlan sets Plan field to given value.

### HasPlan

`func (o *SubscriptionDetailsResponse) HasPlan() bool`

HasPlan returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


