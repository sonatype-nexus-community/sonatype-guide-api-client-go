# \ActivityLogAPI

All URIs are relative to *https://api.guide.sonatype.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetActivityLog**](ActivityLogAPI.md#GetActivityLog) | **Get** /users/me/organization/activity-log | Get organization activity log



## GetActivityLog

> OrgActivityLogResponse GetActivityLog(ctx).Category(category).FromDate(fromDate).ToDate(toDate).Page(page).PageSize(pageSize).Execute()

Get organization activity log



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	sonatypeguide "github.com/sonatype-nexus-community/sonatype-guide-api-client-go"
)

func main() {
	category := "category_example" // string | Filter by category (TOKEN, ORGANIZATION, BILLING, SUPPORT) (optional)
	fromDate := time.Now() // string | Start date (YYYY-MM-DD) (optional)
	toDate := time.Now() // string | End date (YYYY-MM-DD) (optional)
	page := int32(0) // int32 | Page number (0-indexed) (optional) (default to 0)
	pageSize := int32(50) // int32 | Page size (max 100) (optional) (default to 50)

	configuration := sonatypeguide.NewConfiguration()
	apiClient := sonatypeguide.NewAPIClient(configuration)
	resp, r, err := apiClient.ActivityLogAPI.GetActivityLog(context.Background()).Category(category).FromDate(fromDate).ToDate(toDate).Page(page).PageSize(pageSize).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ActivityLogAPI.GetActivityLog``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetActivityLog`: OrgActivityLogResponse
	fmt.Fprintf(os.Stdout, "Response from `ActivityLogAPI.GetActivityLog`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetActivityLogRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **category** | **string** | Filter by category (TOKEN, ORGANIZATION, BILLING, SUPPORT) | 
 **fromDate** | **string** | Start date (YYYY-MM-DD) | 
 **toDate** | **string** | End date (YYYY-MM-DD) | 
 **page** | **int32** | Page number (0-indexed) | [default to 0]
 **pageSize** | **int32** | Page size (max 100) | [default to 50]

### Return type

[**OrgActivityLogResponse**](OrgActivityLogResponse.md)

### Authorization

[bearer-jwt](../README.md#bearer-jwt)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

