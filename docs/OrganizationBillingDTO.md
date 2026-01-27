# OrganizationBillingDTO

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**MonthlyCost** | Pointer to **float64** |  | [optional] 
**NextBilling** | Pointer to **string** |  | [optional] 
**PaymentMethod** | Pointer to **string** |  | [optional] 

## Methods

### NewOrganizationBillingDTO

`func NewOrganizationBillingDTO() *OrganizationBillingDTO`

NewOrganizationBillingDTO instantiates a new OrganizationBillingDTO object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOrganizationBillingDTOWithDefaults

`func NewOrganizationBillingDTOWithDefaults() *OrganizationBillingDTO`

NewOrganizationBillingDTOWithDefaults instantiates a new OrganizationBillingDTO object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMonthlyCost

`func (o *OrganizationBillingDTO) GetMonthlyCost() float64`

GetMonthlyCost returns the MonthlyCost field if non-nil, zero value otherwise.

### GetMonthlyCostOk

`func (o *OrganizationBillingDTO) GetMonthlyCostOk() (*float64, bool)`

GetMonthlyCostOk returns a tuple with the MonthlyCost field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMonthlyCost

`func (o *OrganizationBillingDTO) SetMonthlyCost(v float64)`

SetMonthlyCost sets MonthlyCost field to given value.

### HasMonthlyCost

`func (o *OrganizationBillingDTO) HasMonthlyCost() bool`

HasMonthlyCost returns a boolean if a field has been set.

### GetNextBilling

`func (o *OrganizationBillingDTO) GetNextBilling() string`

GetNextBilling returns the NextBilling field if non-nil, zero value otherwise.

### GetNextBillingOk

`func (o *OrganizationBillingDTO) GetNextBillingOk() (*string, bool)`

GetNextBillingOk returns a tuple with the NextBilling field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextBilling

`func (o *OrganizationBillingDTO) SetNextBilling(v string)`

SetNextBilling sets NextBilling field to given value.

### HasNextBilling

`func (o *OrganizationBillingDTO) HasNextBilling() bool`

HasNextBilling returns a boolean if a field has been set.

### GetPaymentMethod

`func (o *OrganizationBillingDTO) GetPaymentMethod() string`

GetPaymentMethod returns the PaymentMethod field if non-nil, zero value otherwise.

### GetPaymentMethodOk

`func (o *OrganizationBillingDTO) GetPaymentMethodOk() (*string, bool)`

GetPaymentMethodOk returns a tuple with the PaymentMethod field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaymentMethod

`func (o *OrganizationBillingDTO) SetPaymentMethod(v string)`

SetPaymentMethod sets PaymentMethod field to given value.

### HasPaymentMethod

`func (o *OrganizationBillingDTO) HasPaymentMethod() bool`

HasPaymentMethod returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


