# OrgActivityLogResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Events** | Pointer to [**[]OrgActivityLogEntry**](OrgActivityLogEntry.md) |  | [optional] 
**Page** | Pointer to **int32** |  | [optional] 
**PageSize** | Pointer to **int32** |  | [optional] 
**TotalCount** | Pointer to **int64** |  | [optional] 
**TotalPages** | Pointer to **int32** |  | [optional] 

## Methods

### NewOrgActivityLogResponse

`func NewOrgActivityLogResponse() *OrgActivityLogResponse`

NewOrgActivityLogResponse instantiates a new OrgActivityLogResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOrgActivityLogResponseWithDefaults

`func NewOrgActivityLogResponseWithDefaults() *OrgActivityLogResponse`

NewOrgActivityLogResponseWithDefaults instantiates a new OrgActivityLogResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEvents

`func (o *OrgActivityLogResponse) GetEvents() []OrgActivityLogEntry`

GetEvents returns the Events field if non-nil, zero value otherwise.

### GetEventsOk

`func (o *OrgActivityLogResponse) GetEventsOk() (*[]OrgActivityLogEntry, bool)`

GetEventsOk returns a tuple with the Events field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEvents

`func (o *OrgActivityLogResponse) SetEvents(v []OrgActivityLogEntry)`

SetEvents sets Events field to given value.

### HasEvents

`func (o *OrgActivityLogResponse) HasEvents() bool`

HasEvents returns a boolean if a field has been set.

### GetPage

`func (o *OrgActivityLogResponse) GetPage() int32`

GetPage returns the Page field if non-nil, zero value otherwise.

### GetPageOk

`func (o *OrgActivityLogResponse) GetPageOk() (*int32, bool)`

GetPageOk returns a tuple with the Page field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPage

`func (o *OrgActivityLogResponse) SetPage(v int32)`

SetPage sets Page field to given value.

### HasPage

`func (o *OrgActivityLogResponse) HasPage() bool`

HasPage returns a boolean if a field has been set.

### GetPageSize

`func (o *OrgActivityLogResponse) GetPageSize() int32`

GetPageSize returns the PageSize field if non-nil, zero value otherwise.

### GetPageSizeOk

`func (o *OrgActivityLogResponse) GetPageSizeOk() (*int32, bool)`

GetPageSizeOk returns a tuple with the PageSize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPageSize

`func (o *OrgActivityLogResponse) SetPageSize(v int32)`

SetPageSize sets PageSize field to given value.

### HasPageSize

`func (o *OrgActivityLogResponse) HasPageSize() bool`

HasPageSize returns a boolean if a field has been set.

### GetTotalCount

`func (o *OrgActivityLogResponse) GetTotalCount() int64`

GetTotalCount returns the TotalCount field if non-nil, zero value otherwise.

### GetTotalCountOk

`func (o *OrgActivityLogResponse) GetTotalCountOk() (*int64, bool)`

GetTotalCountOk returns a tuple with the TotalCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalCount

`func (o *OrgActivityLogResponse) SetTotalCount(v int64)`

SetTotalCount sets TotalCount field to given value.

### HasTotalCount

`func (o *OrgActivityLogResponse) HasTotalCount() bool`

HasTotalCount returns a boolean if a field has been set.

### GetTotalPages

`func (o *OrgActivityLogResponse) GetTotalPages() int32`

GetTotalPages returns the TotalPages field if non-nil, zero value otherwise.

### GetTotalPagesOk

`func (o *OrgActivityLogResponse) GetTotalPagesOk() (*int32, bool)`

GetTotalPagesOk returns a tuple with the TotalPages field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalPages

`func (o *OrgActivityLogResponse) SetTotalPages(v int32)`

SetTotalPages sets TotalPages field to given value.

### HasTotalPages

`func (o *OrgActivityLogResponse) HasTotalPages() bool`

HasTotalPages returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


