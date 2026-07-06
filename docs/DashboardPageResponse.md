# DashboardPageResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Rows** | Pointer to [**[]DashboardRowResponse**](DashboardRowResponse.md) |  | [optional] 
**Total** | Pointer to **int32** |  | [optional] 

## Methods

### NewDashboardPageResponse

`func NewDashboardPageResponse() *DashboardPageResponse`

NewDashboardPageResponse instantiates a new DashboardPageResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDashboardPageResponseWithDefaults

`func NewDashboardPageResponseWithDefaults() *DashboardPageResponse`

NewDashboardPageResponseWithDefaults instantiates a new DashboardPageResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetRows

`func (o *DashboardPageResponse) GetRows() []DashboardRowResponse`

GetRows returns the Rows field if non-nil, zero value otherwise.

### GetRowsOk

`func (o *DashboardPageResponse) GetRowsOk() (*[]DashboardRowResponse, bool)`

GetRowsOk returns a tuple with the Rows field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRows

`func (o *DashboardPageResponse) SetRows(v []DashboardRowResponse)`

SetRows sets Rows field to given value.

### HasRows

`func (o *DashboardPageResponse) HasRows() bool`

HasRows returns a boolean if a field has been set.

### GetTotal

`func (o *DashboardPageResponse) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *DashboardPageResponse) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *DashboardPageResponse) SetTotal(v int32)`

SetTotal sets Total field to given value.

### HasTotal

`func (o *DashboardPageResponse) HasTotal() bool`

HasTotal returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


