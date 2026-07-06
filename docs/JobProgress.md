# JobProgress

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Delivered** | Pointer to **int32** |  | [optional] 
**Failed** | Pointer to **int32** |  | [optional] 
**Items** | Pointer to [**[]ItemProgress**](ItemProgress.md) |  | [optional] 
**JobId** | Pointer to **int64** |  | [optional] 
**Skipped** | Pointer to **int32** |  | [optional] 
**Status** | Pointer to **string** |  | [optional] 
**Total** | Pointer to **int32** |  | [optional] 

## Methods

### NewJobProgress

`func NewJobProgress() *JobProgress`

NewJobProgress instantiates a new JobProgress object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewJobProgressWithDefaults

`func NewJobProgressWithDefaults() *JobProgress`

NewJobProgressWithDefaults instantiates a new JobProgress object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDelivered

`func (o *JobProgress) GetDelivered() int32`

GetDelivered returns the Delivered field if non-nil, zero value otherwise.

### GetDeliveredOk

`func (o *JobProgress) GetDeliveredOk() (*int32, bool)`

GetDeliveredOk returns a tuple with the Delivered field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDelivered

`func (o *JobProgress) SetDelivered(v int32)`

SetDelivered sets Delivered field to given value.

### HasDelivered

`func (o *JobProgress) HasDelivered() bool`

HasDelivered returns a boolean if a field has been set.

### GetFailed

`func (o *JobProgress) GetFailed() int32`

GetFailed returns the Failed field if non-nil, zero value otherwise.

### GetFailedOk

`func (o *JobProgress) GetFailedOk() (*int32, bool)`

GetFailedOk returns a tuple with the Failed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFailed

`func (o *JobProgress) SetFailed(v int32)`

SetFailed sets Failed field to given value.

### HasFailed

`func (o *JobProgress) HasFailed() bool`

HasFailed returns a boolean if a field has been set.

### GetItems

`func (o *JobProgress) GetItems() []ItemProgress`

GetItems returns the Items field if non-nil, zero value otherwise.

### GetItemsOk

`func (o *JobProgress) GetItemsOk() (*[]ItemProgress, bool)`

GetItemsOk returns a tuple with the Items field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItems

`func (o *JobProgress) SetItems(v []ItemProgress)`

SetItems sets Items field to given value.

### HasItems

`func (o *JobProgress) HasItems() bool`

HasItems returns a boolean if a field has been set.

### GetJobId

`func (o *JobProgress) GetJobId() int64`

GetJobId returns the JobId field if non-nil, zero value otherwise.

### GetJobIdOk

`func (o *JobProgress) GetJobIdOk() (*int64, bool)`

GetJobIdOk returns a tuple with the JobId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJobId

`func (o *JobProgress) SetJobId(v int64)`

SetJobId sets JobId field to given value.

### HasJobId

`func (o *JobProgress) HasJobId() bool`

HasJobId returns a boolean if a field has been set.

### GetSkipped

`func (o *JobProgress) GetSkipped() int32`

GetSkipped returns the Skipped field if non-nil, zero value otherwise.

### GetSkippedOk

`func (o *JobProgress) GetSkippedOk() (*int32, bool)`

GetSkippedOk returns a tuple with the Skipped field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSkipped

`func (o *JobProgress) SetSkipped(v int32)`

SetSkipped sets Skipped field to given value.

### HasSkipped

`func (o *JobProgress) HasSkipped() bool`

HasSkipped returns a boolean if a field has been set.

### GetStatus

`func (o *JobProgress) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *JobProgress) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *JobProgress) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *JobProgress) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetTotal

`func (o *JobProgress) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *JobProgress) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *JobProgress) SetTotal(v int32)`

SetTotal sets Total field to given value.

### HasTotal

`func (o *JobProgress) HasTotal() bool`

HasTotal returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


