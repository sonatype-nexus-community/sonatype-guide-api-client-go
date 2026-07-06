# \AGPBulkOnboardingAPI

All URIs are relative to *https://api.guide.sonatype.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**Active**](AGPBulkOnboardingAPI.md#Active) | **Get** /api/agp/onboarding/bulk/active | Get the caller&#39;s currently-running bulk onboarding job, if any
[**OrgActivity**](AGPBulkOnboardingAPI.md#OrgActivity) | **Get** /api/agp/onboarding/bulk/org-activity | Whether another org member currently has a bulk onboarding job in flight
[**Progress**](AGPBulkOnboardingAPI.md#Progress) | **Get** /api/agp/onboarding/bulk/{jobId} | Get bulk onboarding job progress
[**Start**](AGPBulkOnboardingAPI.md#Start) | **Post** /api/agp/onboarding/bulk | Start bulk onboarding for selected repositories



## Active

> JobProgress Active(ctx).Execute()

Get the caller's currently-running bulk onboarding job, if any

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
	resp, r, err := apiClient.AGPBulkOnboardingAPI.Active(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AGPBulkOnboardingAPI.Active``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `Active`: JobProgress
	fmt.Fprintf(os.Stdout, "Response from `AGPBulkOnboardingAPI.Active`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiActiveRequest struct via the builder pattern


### Return type

[**JobProgress**](JobProgress.md)

### Authorization

[bearer-jwt](../README.md#bearer-jwt)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OrgActivity

> OrgOnboardingActivity OrgActivity(ctx).Execute()

Whether another org member currently has a bulk onboarding job in flight

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
	resp, r, err := apiClient.AGPBulkOnboardingAPI.OrgActivity(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AGPBulkOnboardingAPI.OrgActivity``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OrgActivity`: OrgOnboardingActivity
	fmt.Fprintf(os.Stdout, "Response from `AGPBulkOnboardingAPI.OrgActivity`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiOrgActivityRequest struct via the builder pattern


### Return type

[**OrgOnboardingActivity**](OrgOnboardingActivity.md)

### Authorization

[bearer-jwt](../README.md#bearer-jwt)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## Progress

> JobProgress Progress(ctx, jobId).Execute()

Get bulk onboarding job progress

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
	jobId := int64(789) // int64 | 

	configuration := sonatypeguide.NewConfiguration()
	apiClient := sonatypeguide.NewAPIClient(configuration)
	resp, r, err := apiClient.AGPBulkOnboardingAPI.Progress(context.Background(), jobId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AGPBulkOnboardingAPI.Progress``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `Progress`: JobProgress
	fmt.Fprintf(os.Stdout, "Response from `AGPBulkOnboardingAPI.Progress`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**jobId** | **int64** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiProgressRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**JobProgress**](JobProgress.md)

### Authorization

[bearer-jwt](../README.md#bearer-jwt)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## Start

> BulkOnboardResponse Start(ctx).BulkOnboardRequest(bulkOnboardRequest).Execute()

Start bulk onboarding for selected repositories

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
	bulkOnboardRequest := *sonatypeguide.NewBulkOnboardRequest([]int64{int64(123)}) // BulkOnboardRequest | 

	configuration := sonatypeguide.NewConfiguration()
	apiClient := sonatypeguide.NewAPIClient(configuration)
	resp, r, err := apiClient.AGPBulkOnboardingAPI.Start(context.Background()).BulkOnboardRequest(bulkOnboardRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AGPBulkOnboardingAPI.Start``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `Start`: BulkOnboardResponse
	fmt.Fprintf(os.Stdout, "Response from `AGPBulkOnboardingAPI.Start`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiStartRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **bulkOnboardRequest** | [**BulkOnboardRequest**](BulkOnboardRequest.md) |  | 

### Return type

[**BulkOnboardResponse**](BulkOnboardResponse.md)

### Authorization

[bearer-jwt](../README.md#bearer-jwt)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

