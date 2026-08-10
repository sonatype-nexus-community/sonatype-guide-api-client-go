# \SecurityEventsAPI

All URIs are relative to *https://api.guide.sonatype.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetSecurityEventById**](SecurityEventsAPI.md#GetSecurityEventById) | **Get** /security-events/{id} | Get security event by ID



## GetSecurityEventById

> SecurityEventDetailDocument GetSecurityEventById(ctx, id).Execute()

Get security event by ID



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
	id := "id_example" // string | Security event ID

	configuration := sonatypeguide.NewConfiguration()
	apiClient := sonatypeguide.NewAPIClient(configuration)
	resp, r, err := apiClient.SecurityEventsAPI.GetSecurityEventById(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SecurityEventsAPI.GetSecurityEventById``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetSecurityEventById`: SecurityEventDetailDocument
	fmt.Fprintf(os.Stdout, "Response from `SecurityEventsAPI.GetSecurityEventById`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | Security event ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetSecurityEventByIdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**SecurityEventDetailDocument**](SecurityEventDetailDocument.md)

### Authorization

[bearer-jwt](../README.md#bearer-jwt)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

