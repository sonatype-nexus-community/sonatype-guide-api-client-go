# \AGPDashboardAPI

All URIs are relative to *https://api.guide.sonatype.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CandidateIds**](AGPDashboardAPI.md#CandidateIds) | **Get** /api/agp/dashboard/candidate-ids | Ids of all onboarding-candidate repositories matching the name filter
[**Dashboard**](AGPDashboardAPI.md#Dashboard) | **Get** /api/agp/dashboard | List connected repositories with status (search, filter &amp; paging)
[**OnboardingAccess**](AGPDashboardAPI.md#OnboardingAccess) | **Get** /api/agp/dashboard/onboarding-access | Whether the caller may onboard repositories



## CandidateIds

> []int64 CandidateIds(ctx).Q(q).Search(search).Execute()

Ids of all onboarding-candidate repositories matching the name filter

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	sonatypeguide "github.com/sonatype-nexus-community/sonatype-guide-api-client-go"
)

func main() {
	q := "q_example" // string |  (optional)
	search := "search_example" // string |  (optional)

	configuration := sonatypeguide.NewConfiguration()
	apiClient := sonatypeguide.NewAPIClient(configuration)
	resp, r, err := apiClient.AGPDashboardAPI.CandidateIds(context.Background()).Q(q).Search(search).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AGPDashboardAPI.CandidateIds``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CandidateIds`: []int64
	fmt.Fprintf(os.Stdout, "Response from `AGPDashboardAPI.CandidateIds`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCandidateIdsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **q** | **string** |  | 
 **search** | **string** |  | 

### Return type

**[]int64**

### Authorization

[bearer-jwt](../README.md#bearer-jwt)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## Dashboard

> DashboardPageResponse Dashboard(ctx).Q(q).Search(search).Status(status).Sort(sort).Page(page).PageSize(pageSize).Execute()

List connected repositories with status (search, filter & paging)

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	sonatypeguide "github.com/sonatype-nexus-community/sonatype-guide-api-client-go"
)

func main() {
	q := "q_example" // string | Name filter (canonical). Takes precedence over the deprecated `search`. (optional)
	search := "search_example" // string | Deprecated alias for `q`; ignored when `q` is also provided. (optional)
	status := "status_example" // string |  (optional)
	sort := "sort_example" // string |  (optional) (default to "asc")
	page := int32(56) // int32 |  (optional) (default to 0)
	pageSize := int32(56) // int32 |  (optional) (default to 25)

	configuration := sonatypeguide.NewConfiguration()
	apiClient := sonatypeguide.NewAPIClient(configuration)
	resp, r, err := apiClient.AGPDashboardAPI.Dashboard(context.Background()).Q(q).Search(search).Status(status).Sort(sort).Page(page).PageSize(pageSize).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AGPDashboardAPI.Dashboard``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `Dashboard`: DashboardPageResponse
	fmt.Fprintf(os.Stdout, "Response from `AGPDashboardAPI.Dashboard`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiDashboardRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **q** | **string** | Name filter (canonical). Takes precedence over the deprecated &#x60;search&#x60;. | 
 **search** | **string** | Deprecated alias for &#x60;q&#x60;; ignored when &#x60;q&#x60; is also provided. | 
 **status** | **string** |  | 
 **sort** | **string** |  | [default to &quot;asc&quot;]
 **page** | **int32** |  | [default to 0]
 **pageSize** | **int32** |  | [default to 25]

### Return type

[**DashboardPageResponse**](DashboardPageResponse.md)

### Authorization

[bearer-jwt](../README.md#bearer-jwt)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OnboardingAccess

> OnboardingAccessResponse OnboardingAccess(ctx).Execute()

Whether the caller may onboard repositories

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	sonatypeguide "github.com/sonatype-nexus-community/sonatype-guide-api-client-go"
)

func main() {

	configuration := sonatypeguide.NewConfiguration()
	apiClient := sonatypeguide.NewAPIClient(configuration)
	resp, r, err := apiClient.AGPDashboardAPI.OnboardingAccess(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AGPDashboardAPI.OnboardingAccess``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OnboardingAccess`: OnboardingAccessResponse
	fmt.Fprintf(os.Stdout, "Response from `AGPDashboardAPI.OnboardingAccess`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiOnboardingAccessRequest struct via the builder pattern


### Return type

[**OnboardingAccessResponse**](OnboardingAccessResponse.md)

### Authorization

[bearer-jwt](../README.md#bearer-jwt)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

