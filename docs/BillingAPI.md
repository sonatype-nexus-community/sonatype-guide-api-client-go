# \BillingAPI

All URIs are relative to *https://api.guide.sonatype.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetBilling**](BillingAPI.md#GetBilling) | **Get** /billing | Get billing information
[**GetInvoicePdf**](BillingAPI.md#GetInvoicePdf) | **Get** /billing/invoices/{invoiceId}/pdf | Download invoice PDF
[**GetPlans**](BillingAPI.md#GetPlans) | **Get** /billing/plans | Get all available plans
[**GetUserInvoiceHistory**](BillingAPI.md#GetUserInvoiceHistory) | **Get** /billing/invoices | Get user invoice history



## GetBilling

> BillingDTO GetBilling(ctx).Execute()

Get billing information



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
	resp, r, err := apiClient.BillingAPI.GetBilling(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BillingAPI.GetBilling``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetBilling`: BillingDTO
	fmt.Fprintf(os.Stdout, "Response from `BillingAPI.GetBilling`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetBillingRequest struct via the builder pattern


### Return type

[**BillingDTO**](BillingDTO.md)

### Authorization

[bearer-jwt](../README.md#bearer-jwt)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetInvoicePdf

> GetInvoicePdf(ctx, invoiceId).Execute()

Download invoice PDF



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
	invoiceId := "invoiceId_example" // string | 

	configuration := sonatypeguide.NewConfiguration()
	apiClient := sonatypeguide.NewAPIClient(configuration)
	r, err := apiClient.BillingAPI.GetInvoicePdf(context.Background(), invoiceId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BillingAPI.GetInvoicePdf``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**invoiceId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetInvoicePdfRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

 (empty response body)

### Authorization

[bearer-jwt](../README.md#bearer-jwt)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetPlans

> []PlanDTO GetPlans(ctx).Execute()

Get all available plans



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
	resp, r, err := apiClient.BillingAPI.GetPlans(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BillingAPI.GetPlans``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetPlans`: []PlanDTO
	fmt.Fprintf(os.Stdout, "Response from `BillingAPI.GetPlans`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetPlansRequest struct via the builder pattern


### Return type

[**[]PlanDTO**](PlanDTO.md)

### Authorization

[bearer-jwt](../README.md#bearer-jwt)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetUserInvoiceHistory

> string GetUserInvoiceHistory(ctx).Execute()

Get user invoice history



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
	resp, r, err := apiClient.BillingAPI.GetUserInvoiceHistory(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `BillingAPI.GetUserInvoiceHistory``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetUserInvoiceHistory`: string
	fmt.Fprintf(os.Stdout, "Response from `BillingAPI.GetUserInvoiceHistory`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetUserInvoiceHistoryRequest struct via the builder pattern


### Return type

**string**

### Authorization

[bearer-jwt](../README.md#bearer-jwt)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

