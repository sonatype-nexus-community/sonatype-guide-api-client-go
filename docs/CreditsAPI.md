# \CreditsAPI

All URIs are relative to *http://api.guide.sonatype.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetCreditUsageBreakdown**](CreditsAPI.md#GetCreditUsageBreakdown) | **Get** /credits/usage/breakdown | Get credit usage breakdown
[**GetCreditUsageHistory**](CreditsAPI.md#GetCreditUsageHistory) | **Get** /credits/usage/history | Get credit usage history



## GetCreditUsageBreakdown

> string GetCreditUsageBreakdown(ctx).Execute()

Get credit usage breakdown



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
	resp, r, err := apiClient.CreditsAPI.GetCreditUsageBreakdown(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CreditsAPI.GetCreditUsageBreakdown``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetCreditUsageBreakdown`: string
	fmt.Fprintf(os.Stdout, "Response from `CreditsAPI.GetCreditUsageBreakdown`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetCreditUsageBreakdownRequest struct via the builder pattern


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


## GetCreditUsageHistory

> string GetCreditUsageHistory(ctx).Execute()

Get credit usage history



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
	resp, r, err := apiClient.CreditsAPI.GetCreditUsageHistory(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CreditsAPI.GetCreditUsageHistory``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetCreditUsageHistory`: string
	fmt.Fprintf(os.Stdout, "Response from `CreditsAPI.GetCreditUsageHistory`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetCreditUsageHistoryRequest struct via the builder pattern


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

