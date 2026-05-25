# PolicyCompliance

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Compliant** | Pointer to **bool** |  | [optional] 
**Conditions** | Pointer to [**[]PolicyConditionResult**](PolicyConditionResult.md) |  | [optional] 

## Methods

### NewPolicyCompliance

`func NewPolicyCompliance() *PolicyCompliance`

NewPolicyCompliance instantiates a new PolicyCompliance object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPolicyComplianceWithDefaults

`func NewPolicyComplianceWithDefaults() *PolicyCompliance`

NewPolicyComplianceWithDefaults instantiates a new PolicyCompliance object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCompliant

`func (o *PolicyCompliance) GetCompliant() bool`

GetCompliant returns the Compliant field if non-nil, zero value otherwise.

### GetCompliantOk

`func (o *PolicyCompliance) GetCompliantOk() (*bool, bool)`

GetCompliantOk returns a tuple with the Compliant field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompliant

`func (o *PolicyCompliance) SetCompliant(v bool)`

SetCompliant sets Compliant field to given value.

### HasCompliant

`func (o *PolicyCompliance) HasCompliant() bool`

HasCompliant returns a boolean if a field has been set.

### GetConditions

`func (o *PolicyCompliance) GetConditions() []PolicyConditionResult`

GetConditions returns the Conditions field if non-nil, zero value otherwise.

### GetConditionsOk

`func (o *PolicyCompliance) GetConditionsOk() (*[]PolicyConditionResult, bool)`

GetConditionsOk returns a tuple with the Conditions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConditions

`func (o *PolicyCompliance) SetConditions(v []PolicyConditionResult)`

SetConditions sets Conditions field to given value.

### HasConditions

`func (o *PolicyCompliance) HasConditions() bool`

HasConditions returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


