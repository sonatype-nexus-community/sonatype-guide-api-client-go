# \VulnerabilitiesAPI

All URIs are relative to *https://api.guide.sonatype.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetVulnerabilityAffectedComponents**](VulnerabilitiesAPI.md#GetVulnerabilityAffectedComponents) | **Get** /vulnerabilities/{id}/components | Get affected components for a vulnerability
[**GetVulnerabilityByRefId**](VulnerabilitiesAPI.md#GetVulnerabilityByRefId) | **Get** /vulnerabilities/{id} | Get vulnerability by ID



## GetVulnerabilityAffectedComponents

> ApiSearchResponse GetVulnerabilityAffectedComponents(ctx, id).Query(query).Offset(offset).Limit(limit).SortField(sortField).SortOrder(sortOrder).Execute()

Get affected components for a vulnerability



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
	id := "id_example" // string | Vulnerability ID (e.g., CVE-2021-44228, GHSA-xxxx-yyyy-zzzz)
	query := "query_example" // string | Text search query (filters ecosystem, namespace, package, version fields) (optional)
	offset := int32(56) // int32 | Pagination offset (default: 0) (optional)
	limit := int32(56) // int32 | Pagination limit (default: 50) (optional)
	sortField := "sortField_example" // string | Field to sort by: ecosystem, package (fullPackageName), version (default: package) (optional)
	sortOrder := "sortOrder_example" // string | Sort order: asc or desc (default: asc) (optional)

	configuration := sonatypeguide.NewConfiguration()
	apiClient := sonatypeguide.NewAPIClient(configuration)
	resp, r, err := apiClient.VulnerabilitiesAPI.GetVulnerabilityAffectedComponents(context.Background(), id).Query(query).Offset(offset).Limit(limit).SortField(sortField).SortOrder(sortOrder).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `VulnerabilitiesAPI.GetVulnerabilityAffectedComponents``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetVulnerabilityAffectedComponents`: ApiSearchResponse
	fmt.Fprintf(os.Stdout, "Response from `VulnerabilitiesAPI.GetVulnerabilityAffectedComponents`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | Vulnerability ID (e.g., CVE-2021-44228, GHSA-xxxx-yyyy-zzzz) | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetVulnerabilityAffectedComponentsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **query** | **string** | Text search query (filters ecosystem, namespace, package, version fields) | 
 **offset** | **int32** | Pagination offset (default: 0) | 
 **limit** | **int32** | Pagination limit (default: 50) | 
 **sortField** | **string** | Field to sort by: ecosystem, package (fullPackageName), version (default: package) | 
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


## GetVulnerabilityByRefId

> VulnerabilityDetailDocument GetVulnerabilityByRefId(ctx, id).Execute()

Get vulnerability by ID



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
	id := "id_example" // string | Vulnerability ID (e.g., CVE-2021-44228, GHSA-xxxx-yyyy-zzzz)

	configuration := sonatypeguide.NewConfiguration()
	apiClient := sonatypeguide.NewAPIClient(configuration)
	resp, r, err := apiClient.VulnerabilitiesAPI.GetVulnerabilityByRefId(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `VulnerabilitiesAPI.GetVulnerabilityByRefId``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetVulnerabilityByRefId`: VulnerabilityDetailDocument
	fmt.Fprintf(os.Stdout, "Response from `VulnerabilitiesAPI.GetVulnerabilityByRefId`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | Vulnerability ID (e.g., CVE-2021-44228, GHSA-xxxx-yyyy-zzzz) | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetVulnerabilityByRefIdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**VulnerabilityDetailDocument**](VulnerabilityDetailDocument.md)

### Authorization

[bearer-jwt](../README.md#bearer-jwt)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

