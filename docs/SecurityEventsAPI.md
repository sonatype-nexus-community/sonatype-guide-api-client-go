# \SecurityEventsAPI

All URIs are relative to *https://api.guide.sonatype.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetSecurityEventAffectedComponents**](SecurityEventsAPI.md#GetSecurityEventAffectedComponents) | **Get** /security-events/{id}/affected-components | Get affected components for a security event
[**GetSecurityEventById**](SecurityEventsAPI.md#GetSecurityEventById) | **Get** /security-events/{id} | Get security event by ID



## GetSecurityEventAffectedComponents

> ApiSearchResponse GetSecurityEventAffectedComponents(ctx, id).Query(query).Offset(offset).Limit(limit).SortField(sortField).SortOrder(sortOrder).Execute()

Get affected components for a security event



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
	query := "query_example" // string | Text search query over component coordinates (optional)
	offset := int32(56) // int32 | Pagination offset (default: 0) (optional)
	limit := int32(56) // int32 | Pagination limit (default: 50) (optional)
	sortField := "sortField_example" // string | Field to sort by: ecosystem (FULL only), package/packageName, component, version (optional)
	sortOrder := "sortOrder_example" // string | Sort order: asc or desc (default: asc) (optional)

	configuration := sonatypeguide.NewConfiguration()
	apiClient := sonatypeguide.NewAPIClient(configuration)
	resp, r, err := apiClient.SecurityEventsAPI.GetSecurityEventAffectedComponents(context.Background(), id).Query(query).Offset(offset).Limit(limit).SortField(sortField).SortOrder(sortOrder).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SecurityEventsAPI.GetSecurityEventAffectedComponents``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetSecurityEventAffectedComponents`: ApiSearchResponse
	fmt.Fprintf(os.Stdout, "Response from `SecurityEventsAPI.GetSecurityEventAffectedComponents`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | Security event ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetSecurityEventAffectedComponentsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **query** | **string** | Text search query over component coordinates | 
 **offset** | **int32** | Pagination offset (default: 0) | 
 **limit** | **int32** | Pagination limit (default: 50) | 
 **sortField** | **string** | Field to sort by: ecosystem (FULL only), package/packageName, component, version | 
 **sortOrder** | **string** | Sort order: asc or desc (default: asc) | 

### Return type

[**ApiSearchResponse**](ApiSearchResponse.md)

### Authorization

[bearer-jwt](../README.md#bearer-jwt)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


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

