# Invoice

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Amount** | Pointer to **float64** |  | [optional] 
**Date** | Pointer to **string** |  | [optional] 
**Description** | Pointer to **string** |  | [optional] 
**Id** | Pointer to **string** |  | [optional] 
**PdfUrl** | Pointer to **string** |  | [optional] 
**Status** | Pointer to **string** |  | [optional] 
**SubscriptionId** | Pointer to **string** |  | [optional] 
**TotalCredits** | Pointer to **float64** |  | [optional] 
**UsedCredits** | Pointer to **float64** |  | [optional] 

## Methods

### NewInvoice

`func NewInvoice() *Invoice`

NewInvoice instantiates a new Invoice object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInvoiceWithDefaults

`func NewInvoiceWithDefaults() *Invoice`

NewInvoiceWithDefaults instantiates a new Invoice object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAmount

`func (o *Invoice) GetAmount() float64`

GetAmount returns the Amount field if non-nil, zero value otherwise.

### GetAmountOk

`func (o *Invoice) GetAmountOk() (*float64, bool)`

GetAmountOk returns a tuple with the Amount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAmount

`func (o *Invoice) SetAmount(v float64)`

SetAmount sets Amount field to given value.

### HasAmount

`func (o *Invoice) HasAmount() bool`

HasAmount returns a boolean if a field has been set.

### GetDate

`func (o *Invoice) GetDate() string`

GetDate returns the Date field if non-nil, zero value otherwise.

### GetDateOk

`func (o *Invoice) GetDateOk() (*string, bool)`

GetDateOk returns a tuple with the Date field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDate

`func (o *Invoice) SetDate(v string)`

SetDate sets Date field to given value.

### HasDate

`func (o *Invoice) HasDate() bool`

HasDate returns a boolean if a field has been set.

### GetDescription

`func (o *Invoice) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *Invoice) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *Invoice) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *Invoice) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetId

`func (o *Invoice) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Invoice) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Invoice) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *Invoice) HasId() bool`

HasId returns a boolean if a field has been set.

### GetPdfUrl

`func (o *Invoice) GetPdfUrl() string`

GetPdfUrl returns the PdfUrl field if non-nil, zero value otherwise.

### GetPdfUrlOk

`func (o *Invoice) GetPdfUrlOk() (*string, bool)`

GetPdfUrlOk returns a tuple with the PdfUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPdfUrl

`func (o *Invoice) SetPdfUrl(v string)`

SetPdfUrl sets PdfUrl field to given value.

### HasPdfUrl

`func (o *Invoice) HasPdfUrl() bool`

HasPdfUrl returns a boolean if a field has been set.

### GetStatus

`func (o *Invoice) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *Invoice) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *Invoice) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *Invoice) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetSubscriptionId

`func (o *Invoice) GetSubscriptionId() string`

GetSubscriptionId returns the SubscriptionId field if non-nil, zero value otherwise.

### GetSubscriptionIdOk

`func (o *Invoice) GetSubscriptionIdOk() (*string, bool)`

GetSubscriptionIdOk returns a tuple with the SubscriptionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubscriptionId

`func (o *Invoice) SetSubscriptionId(v string)`

SetSubscriptionId sets SubscriptionId field to given value.

### HasSubscriptionId

`func (o *Invoice) HasSubscriptionId() bool`

HasSubscriptionId returns a boolean if a field has been set.

### GetTotalCredits

`func (o *Invoice) GetTotalCredits() float64`

GetTotalCredits returns the TotalCredits field if non-nil, zero value otherwise.

### GetTotalCreditsOk

`func (o *Invoice) GetTotalCreditsOk() (*float64, bool)`

GetTotalCreditsOk returns a tuple with the TotalCredits field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalCredits

`func (o *Invoice) SetTotalCredits(v float64)`

SetTotalCredits sets TotalCredits field to given value.

### HasTotalCredits

`func (o *Invoice) HasTotalCredits() bool`

HasTotalCredits returns a boolean if a field has been set.

### GetUsedCredits

`func (o *Invoice) GetUsedCredits() float64`

GetUsedCredits returns the UsedCredits field if non-nil, zero value otherwise.

### GetUsedCreditsOk

`func (o *Invoice) GetUsedCreditsOk() (*float64, bool)`

GetUsedCreditsOk returns a tuple with the UsedCredits field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsedCredits

`func (o *Invoice) SetUsedCredits(v float64)`

SetUsedCredits sets UsedCredits field to given value.

### HasUsedCredits

`func (o *Invoice) HasUsedCredits() bool`

HasUsedCredits returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


