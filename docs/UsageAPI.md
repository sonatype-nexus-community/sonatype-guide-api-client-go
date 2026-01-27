# \UsageAPI

All URIs are relative to *http://api.guide.sonatype.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetBillingPeriods**](UsageAPI.md#GetBillingPeriods) | **Get** /usage/billing-periods | Get billing periods for user
[**GetCreditBalance**](UsageAPI.md#GetCreditBalance) | **Get** /usage | Get credit balance
[**GetCreditPeriodsV2**](UsageAPI.md#GetCreditPeriodsV2) | **Get** /usage/v2/credit-periods | Get credit periods (v2)
[**GetCumulativeUsage**](UsageAPI.md#GetCumulativeUsage) | **Get** /usage/cumulative | Get cumulative credit usage for a billing period
[**GetUsageV2**](UsageAPI.md#GetUsageV2) | **Get** /usage/v2 | Get usage information (v2)



## GetBillingPeriods

> GetBillingPeriods(ctx).Execute()

Get billing periods for user



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	sonatypeguide "github.com/sonatype-nexus-community/sonatype-guide-api-client-go/v1"
)

func main() {

	configuration := sonatypeguide.NewConfiguration()
	apiClient := sonatypeguide.NewAPIClient(configuration)
	r, err := apiClient.UsageAPI.GetBillingPeriods(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UsageAPI.GetBillingPeriods``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetBillingPeriodsRequest struct via the builder pattern


### Return type

 (empty response body)

### Authorization

[bearer-jwt](../README.md#bearer-jwt)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetCreditBalance

> CreditBalance GetCreditBalance(ctx).Execute()

Get credit balance



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	sonatypeguide "github.com/sonatype-nexus-community/sonatype-guide-api-client-go/v1"
)

func main() {

	configuration := sonatypeguide.NewConfiguration()
	apiClient := sonatypeguide.NewAPIClient(configuration)
	resp, r, err := apiClient.UsageAPI.GetCreditBalance(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UsageAPI.GetCreditBalance``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetCreditBalance`: CreditBalance
	fmt.Fprintf(os.Stdout, "Response from `UsageAPI.GetCreditBalance`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetCreditBalanceRequest struct via the builder pattern


### Return type

[**CreditBalance**](CreditBalance.md)

### Authorization

[bearer-jwt](../README.md#bearer-jwt)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetCreditPeriodsV2

> []PeriodDTO GetCreditPeriodsV2(ctx).Execute()

Get credit periods (v2)



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	sonatypeguide "github.com/sonatype-nexus-community/sonatype-guide-api-client-go/v1"
)

func main() {

	configuration := sonatypeguide.NewConfiguration()
	apiClient := sonatypeguide.NewAPIClient(configuration)
	resp, r, err := apiClient.UsageAPI.GetCreditPeriodsV2(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UsageAPI.GetCreditPeriodsV2``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetCreditPeriodsV2`: []PeriodDTO
	fmt.Fprintf(os.Stdout, "Response from `UsageAPI.GetCreditPeriodsV2`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetCreditPeriodsV2Request struct via the builder pattern


### Return type

[**[]PeriodDTO**](PeriodDTO.md)

### Authorization

[bearer-jwt](../README.md#bearer-jwt)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetCumulativeUsage

> GetCumulativeUsage(ctx).StartDate(startDate).EndDate(endDate).Execute()

Get cumulative credit usage for a billing period



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	sonatypeguide "github.com/sonatype-nexus-community/sonatype-guide-api-client-go/v1"
)

func main() {
	startDate := time.Now() // string | Start date (YYYY-MM-DD)
	endDate := time.Now() // string | End date (YYYY-MM-DD)

	configuration := sonatypeguide.NewConfiguration()
	apiClient := sonatypeguide.NewAPIClient(configuration)
	r, err := apiClient.UsageAPI.GetCumulativeUsage(context.Background()).StartDate(startDate).EndDate(endDate).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UsageAPI.GetCumulativeUsage``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetCumulativeUsageRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **startDate** | **string** | Start date (YYYY-MM-DD) | 
 **endDate** | **string** | End date (YYYY-MM-DD) | 

### Return type

 (empty response body)

### Authorization

[bearer-jwt](../README.md#bearer-jwt)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetUsageV2

> UsageDTO GetUsageV2(ctx).Execute()

Get usage information (v2)



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	sonatypeguide "github.com/sonatype-nexus-community/sonatype-guide-api-client-go/v1"
)

func main() {

	configuration := sonatypeguide.NewConfiguration()
	apiClient := sonatypeguide.NewAPIClient(configuration)
	resp, r, err := apiClient.UsageAPI.GetUsageV2(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UsageAPI.GetUsageV2``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetUsageV2`: UsageDTO
	fmt.Fprintf(os.Stdout, "Response from `UsageAPI.GetUsageV2`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetUsageV2Request struct via the builder pattern


### Return type

[**UsageDTO**](UsageDTO.md)

### Authorization

[bearer-jwt](../README.md#bearer-jwt)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

