# \ComponentsAPI

All URIs are relative to *https://api.guide.sonatype.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetComponentDependenciesByPurlQueryParam**](ComponentsAPI.md#GetComponentDependenciesByPurlQueryParam) | **Get** /components/dependencies | Get dependencies for a component by coordinates (query parameters)
[**GetComponentDetailByPurlQueryParam**](ComponentsAPI.md#GetComponentDetailByPurlQueryParam) | **Get** /components/detail | Get component detail by coordinates (query parameters)
[**GetComponentVersionsByPurlQueryParam**](ComponentsAPI.md#GetComponentVersionsByPurlQueryParam) | **Get** /components/versions | Get all component versions by coordinates (query parameters)
[**GetComponentVulnerabilitiesByPurlQueryParam**](ComponentsAPI.md#GetComponentVulnerabilitiesByPurlQueryParam) | **Get** /components/vulnerabilities | Get vulnerabilities for a component by coordinates (query parameters)
[**GetLatestVersion**](ComponentsAPI.md#GetLatestVersion) | **Post** /components/latest-version | Get latest version of a component



## GetComponentDependenciesByPurlQueryParam

> ApiSearchResponse GetComponentDependenciesByPurlQueryParam(ctx).Purl(purl).Format(format).Name(name).Version(version).Query(query).Offset(offset).Limit(limit).SortField(sortField).SortOrder(sortOrder).Formats(formats).Categories(categories).Severities(severities).MinCvss(minCvss).MaxCvss(maxCvss).MinVersionScore(minVersionScore).MaxVersionScore(maxVersionScore).LicenseFamilies(licenseFamilies).Licenses(licenses).LatestStable(latestStable).Namespace(namespace).Execute()

Get dependencies for a component by coordinates (query parameters)



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	sonatypeguide "github.com/sonatype-nexus-community/sonatype-guide-api-client-go/sonatypeguide"
)

func main() {
	purl := "purl_example" // string | URL-encoded PURL (e.g., pkg%3Amaven%2F...)
	format := "format_example" // string | Package format (e.g., maven, npm, pypi)
	name := "name_example" // string | Package name
	version := "version_example" // string | Package version
	query := "query_example" // string | Text search query (searches name, namespace, refid) (optional)
	offset := int32(56) // int32 | Pagination offset (default: 0) (optional)
	limit := int32(56) // int32 | Pagination limit (default: 20) (optional)
	sortField := "sortField_example" // string | Field to sort by (default: name) (optional)
	sortOrder := "sortOrder_example" // string | Sort order: asc or desc (default: asc) (optional)
	formats := []string{"Inner_example"} // []string | Format filter (e.g., maven, npm, pypi) - repeatable (optional)
	categories := []string{"Inner_example"} // []string | Category filter (e.g., Logging, Framework) - repeatable (optional)
	severities := []string{"Inner_example"} // []string | CVSS severity filter (e.g., critical, high) - repeatable (optional)
	minCvss := float64(1.2) // float64 | Minimum CVSS score (0.0 to 10.0) (optional)
	maxCvss := float64(1.2) // float64 | Maximum CVSS score (0.0 to 10.0) (optional)
	minVersionScore := int32(56) // int32 | Minimum version score (0 to 100) (optional)
	maxVersionScore := int32(56) // int32 | Maximum version score (0 to 100) (optional)
	licenseFamilies := []string{"Inner_example"} // []string | Licence family filter (e.g., Banned, Copyleft) - repeatable (optional)
	licenses := []string{"Inner_example"} // []string | Licence name filter (e.g., MIT, Apache-2.0, GPL-3.0+) - repeatable (optional)
	latestStable := "latestStable_example" // string | Filter by latest stable versions: 'true' for stable only, 'false' for non-stable only, 'all' for no filter (optional)
	namespace := "namespace_example" // string | Package namespace/groupId (optional) (optional)

	configuration := sonatypeguide.NewConfiguration()
	apiClient := sonatypeguide.NewAPIClient(configuration)
	resp, r, err := apiClient.ComponentsAPI.GetComponentDependenciesByPurlQueryParam(context.Background()).Purl(purl).Format(format).Name(name).Version(version).Query(query).Offset(offset).Limit(limit).SortField(sortField).SortOrder(sortOrder).Formats(formats).Categories(categories).Severities(severities).MinCvss(minCvss).MaxCvss(maxCvss).MinVersionScore(minVersionScore).MaxVersionScore(maxVersionScore).LicenseFamilies(licenseFamilies).Licenses(licenses).LatestStable(latestStable).Namespace(namespace).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ComponentsAPI.GetComponentDependenciesByPurlQueryParam``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetComponentDependenciesByPurlQueryParam`: ApiSearchResponse
	fmt.Fprintf(os.Stdout, "Response from `ComponentsAPI.GetComponentDependenciesByPurlQueryParam`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetComponentDependenciesByPurlQueryParamRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **purl** | **string** | URL-encoded PURL (e.g., pkg%3Amaven%2F...) | 
 **format** | **string** | Package format (e.g., maven, npm, pypi) | 
 **name** | **string** | Package name | 
 **version** | **string** | Package version | 
 **query** | **string** | Text search query (searches name, namespace, refid) | 
 **offset** | **int32** | Pagination offset (default: 0) | 
 **limit** | **int32** | Pagination limit (default: 20) | 
 **sortField** | **string** | Field to sort by (default: name) | 
 **sortOrder** | **string** | Sort order: asc or desc (default: asc) | 
 **formats** | **[]string** | Format filter (e.g., maven, npm, pypi) - repeatable | 
 **categories** | **[]string** | Category filter (e.g., Logging, Framework) - repeatable | 
 **severities** | **[]string** | CVSS severity filter (e.g., critical, high) - repeatable | 
 **minCvss** | **float64** | Minimum CVSS score (0.0 to 10.0) | 
 **maxCvss** | **float64** | Maximum CVSS score (0.0 to 10.0) | 
 **minVersionScore** | **int32** | Minimum version score (0 to 100) | 
 **maxVersionScore** | **int32** | Maximum version score (0 to 100) | 
 **licenseFamilies** | **[]string** | Licence family filter (e.g., Banned, Copyleft) - repeatable | 
 **licenses** | **[]string** | Licence name filter (e.g., MIT, Apache-2.0, GPL-3.0+) - repeatable | 
 **latestStable** | **string** | Filter by latest stable versions: &#39;true&#39; for stable only, &#39;false&#39; for non-stable only, &#39;all&#39; for no filter | 
 **namespace** | **string** | Package namespace/groupId (optional) | 

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


## GetComponentDetailByPurlQueryParam

> ComponentDetailDocument GetComponentDetailByPurlQueryParam(ctx).Purl(purl).Format(format).Name(name).Version(version).Namespace(namespace).Execute()

Get component detail by coordinates (query parameters)



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	sonatypeguide "github.com/sonatype-nexus-community/sonatype-guide-api-client-go/sonatypeguide"
)

func main() {
	purl := "purl_example" // string | URL-encoded PURL (e.g., pkg%3Amaven%2F...)
	format := "format_example" // string | Package format (e.g., maven, npm, pypi)
	name := "name_example" // string | Package name
	version := "version_example" // string | Package version
	namespace := "namespace_example" // string | Package namespace/groupId (optional) (optional)

	configuration := sonatypeguide.NewConfiguration()
	apiClient := sonatypeguide.NewAPIClient(configuration)
	resp, r, err := apiClient.ComponentsAPI.GetComponentDetailByPurlQueryParam(context.Background()).Purl(purl).Format(format).Name(name).Version(version).Namespace(namespace).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ComponentsAPI.GetComponentDetailByPurlQueryParam``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetComponentDetailByPurlQueryParam`: ComponentDetailDocument
	fmt.Fprintf(os.Stdout, "Response from `ComponentsAPI.GetComponentDetailByPurlQueryParam`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetComponentDetailByPurlQueryParamRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **purl** | **string** | URL-encoded PURL (e.g., pkg%3Amaven%2F...) | 
 **format** | **string** | Package format (e.g., maven, npm, pypi) | 
 **name** | **string** | Package name | 
 **version** | **string** | Package version | 
 **namespace** | **string** | Package namespace/groupId (optional) | 

### Return type

[**ComponentDetailDocument**](ComponentDetailDocument.md)

### Authorization

[bearer-jwt](../README.md#bearer-jwt)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetComponentVersionsByPurlQueryParam

> ApiSearchResponse GetComponentVersionsByPurlQueryParam(ctx).Purl(purl).Format(format).Name(name).Version(version).Offset(offset).Limit(limit).SortField(sortField).SortOrder(sortOrder).Severities(severities).MinCvss(minCvss).MaxCvss(maxCvss).MinVersionScore(minVersionScore).MaxVersionScore(maxVersionScore).VersionQuery(versionQuery).PublishedWindow(publishedWindow).HasMalware(hasMalware).IsStable(isStable).Namespace(namespace).Execute()

Get all component versions by coordinates (query parameters)



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	sonatypeguide "github.com/sonatype-nexus-community/sonatype-guide-api-client-go/sonatypeguide"
)

func main() {
	purl := "purl_example" // string | URL-encoded PURL (e.g., pkg%3Amaven%2F...)
	format := "format_example" // string | Package format (e.g., maven, npm, pypi)
	name := "name_example" // string | Package name
	version := "version_example" // string | Package version to exclude from results
	offset := int32(56) // int32 | Pagination offset (default: 0) (optional)
	limit := int32(56) // int32 | Pagination limit (default: 20) (optional)
	sortField := "sortField_example" // string | Field to sort by (default: version) (optional)
	sortOrder := "sortOrder_example" // string | Sort order: asc or desc (default: desc) (optional)
	severities := []string{"Inner_example"} // []string | CVSS severity filter (e.g., critical, high) - repeatable (optional)
	minCvss := float64(1.2) // float64 | Minimum CVSS score (0.0 to 10.0) (optional)
	maxCvss := float64(1.2) // float64 | Maximum CVSS score (0.0 to 10.0) (optional)
	minVersionScore := int32(56) // int32 | Minimum version score (0 to 100) (optional)
	maxVersionScore := int32(56) // int32 | Maximum version score (0 to 100) (optional)
	versionQuery := "versionQuery_example" // string | Filter versions by version prefix (e.g., '2.10' matches '2.10.0', '2.10.1', '2.10-RC1') (optional)
	publishedWindow := "publishedWindow_example" // string | Time window for published date (e.g., 7d, 30d, 60d, 90d, 6m, 1y, 2y) (optional)
	hasMalware := true // bool | Malware filter (true=has malware, false=no malware) (optional)
	isStable := true // bool | Stable version filter (true=stable only, false=pre-release only, null=all) (optional)
	namespace := "namespace_example" // string | Package namespace/groupId (optional) (optional)

	configuration := sonatypeguide.NewConfiguration()
	apiClient := sonatypeguide.NewAPIClient(configuration)
	resp, r, err := apiClient.ComponentsAPI.GetComponentVersionsByPurlQueryParam(context.Background()).Purl(purl).Format(format).Name(name).Version(version).Offset(offset).Limit(limit).SortField(sortField).SortOrder(sortOrder).Severities(severities).MinCvss(minCvss).MaxCvss(maxCvss).MinVersionScore(minVersionScore).MaxVersionScore(maxVersionScore).VersionQuery(versionQuery).PublishedWindow(publishedWindow).HasMalware(hasMalware).IsStable(isStable).Namespace(namespace).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ComponentsAPI.GetComponentVersionsByPurlQueryParam``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetComponentVersionsByPurlQueryParam`: ApiSearchResponse
	fmt.Fprintf(os.Stdout, "Response from `ComponentsAPI.GetComponentVersionsByPurlQueryParam`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetComponentVersionsByPurlQueryParamRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **purl** | **string** | URL-encoded PURL (e.g., pkg%3Amaven%2F...) | 
 **format** | **string** | Package format (e.g., maven, npm, pypi) | 
 **name** | **string** | Package name | 
 **version** | **string** | Package version to exclude from results | 
 **offset** | **int32** | Pagination offset (default: 0) | 
 **limit** | **int32** | Pagination limit (default: 20) | 
 **sortField** | **string** | Field to sort by (default: version) | 
 **sortOrder** | **string** | Sort order: asc or desc (default: desc) | 
 **severities** | **[]string** | CVSS severity filter (e.g., critical, high) - repeatable | 
 **minCvss** | **float64** | Minimum CVSS score (0.0 to 10.0) | 
 **maxCvss** | **float64** | Maximum CVSS score (0.0 to 10.0) | 
 **minVersionScore** | **int32** | Minimum version score (0 to 100) | 
 **maxVersionScore** | **int32** | Maximum version score (0 to 100) | 
 **versionQuery** | **string** | Filter versions by version prefix (e.g., &#39;2.10&#39; matches &#39;2.10.0&#39;, &#39;2.10.1&#39;, &#39;2.10-RC1&#39;) | 
 **publishedWindow** | **string** | Time window for published date (e.g., 7d, 30d, 60d, 90d, 6m, 1y, 2y) | 
 **hasMalware** | **bool** | Malware filter (true&#x3D;has malware, false&#x3D;no malware) | 
 **isStable** | **bool** | Stable version filter (true&#x3D;stable only, false&#x3D;pre-release only, null&#x3D;all) | 
 **namespace** | **string** | Package namespace/groupId (optional) | 

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


## GetComponentVulnerabilitiesByPurlQueryParam

> ApiSearchResponse GetComponentVulnerabilitiesByPurlQueryParam(ctx).Purl(purl).Format(format).Name(name).Version(version).Offset(offset).Limit(limit).SortField(sortField).SortOrder(sortOrder).Severities(severities).MinCvss(minCvss).MaxCvss(maxCvss).MinEpss(minEpss).MaxEpss(maxEpss).HasMalware(hasMalware).PatchAvailable(patchAvailable).PolicyCompliant(policyCompliant).Cwes(cwes).ExploitationKnown(exploitationKnown).PublishedWindow(publishedWindow).Namespace(namespace).Execute()

Get vulnerabilities for a component by coordinates (query parameters)



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	sonatypeguide "github.com/sonatype-nexus-community/sonatype-guide-api-client-go/sonatypeguide"
)

func main() {
	purl := "purl_example" // string | URL-encoded PURL (e.g., pkg%3Amaven%2F...)
	format := "format_example" // string | Package format (e.g., maven, npm, pypi)
	name := "name_example" // string | Package name
	version := "version_example" // string | Package version
	offset := int32(56) // int32 | Pagination offset (default: 0) (optional)
	limit := int32(56) // int32 | Pagination limit (default: 20) (optional)
	sortField := "sortField_example" // string | Field to sort by (default: cvssSeverity) (optional)
	sortOrder := "sortOrder_example" // string | Sort order: asc or desc (default: desc) (optional)
	severities := []string{"Inner_example"} // []string | Severity filter (e.g., critical, high) - repeatable (optional)
	minCvss := float64(1.2) // float64 | Minimum CVSS score (0.0 to 10.0) (optional)
	maxCvss := float64(1.2) // float64 | Maximum CVSS score (0.0 to 10.0) (optional)
	minEpss := float64(1.2) // float64 | Minimum EPSS score (0.0 to 1.0) (optional)
	maxEpss := float64(1.2) // float64 | Maximum EPSS score (0.0 to 1.0) (optional)
	hasMalware := true // bool | Malware flag filter (true=has malware, false=no malware) (optional)
	patchAvailable := true // bool | Patch availability filter (true=available, false=not available) (optional)
	policyCompliant := true // bool | Policy compliance filter (true=compliant, false=non-compliant) (optional)
	cwes := []string{"Inner_example"} // []string | CWE filter (e.g., CWE-79, CWE-89) - repeatable (optional)
	exploitationKnown := true // bool | KEV filter - known exploited vulnerability (optional)
	publishedWindow := "publishedWindow_example" // string | Time window for published date (e.g., 30d, 1y) (optional)
	namespace := "namespace_example" // string | Package namespace/groupId (optional) (optional)

	configuration := sonatypeguide.NewConfiguration()
	apiClient := sonatypeguide.NewAPIClient(configuration)
	resp, r, err := apiClient.ComponentsAPI.GetComponentVulnerabilitiesByPurlQueryParam(context.Background()).Purl(purl).Format(format).Name(name).Version(version).Offset(offset).Limit(limit).SortField(sortField).SortOrder(sortOrder).Severities(severities).MinCvss(minCvss).MaxCvss(maxCvss).MinEpss(minEpss).MaxEpss(maxEpss).HasMalware(hasMalware).PatchAvailable(patchAvailable).PolicyCompliant(policyCompliant).Cwes(cwes).ExploitationKnown(exploitationKnown).PublishedWindow(publishedWindow).Namespace(namespace).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ComponentsAPI.GetComponentVulnerabilitiesByPurlQueryParam``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetComponentVulnerabilitiesByPurlQueryParam`: ApiSearchResponse
	fmt.Fprintf(os.Stdout, "Response from `ComponentsAPI.GetComponentVulnerabilitiesByPurlQueryParam`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetComponentVulnerabilitiesByPurlQueryParamRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **purl** | **string** | URL-encoded PURL (e.g., pkg%3Amaven%2F...) | 
 **format** | **string** | Package format (e.g., maven, npm, pypi) | 
 **name** | **string** | Package name | 
 **version** | **string** | Package version | 
 **offset** | **int32** | Pagination offset (default: 0) | 
 **limit** | **int32** | Pagination limit (default: 20) | 
 **sortField** | **string** | Field to sort by (default: cvssSeverity) | 
 **sortOrder** | **string** | Sort order: asc or desc (default: desc) | 
 **severities** | **[]string** | Severity filter (e.g., critical, high) - repeatable | 
 **minCvss** | **float64** | Minimum CVSS score (0.0 to 10.0) | 
 **maxCvss** | **float64** | Maximum CVSS score (0.0 to 10.0) | 
 **minEpss** | **float64** | Minimum EPSS score (0.0 to 1.0) | 
 **maxEpss** | **float64** | Maximum EPSS score (0.0 to 1.0) | 
 **hasMalware** | **bool** | Malware flag filter (true&#x3D;has malware, false&#x3D;no malware) | 
 **patchAvailable** | **bool** | Patch availability filter (true&#x3D;available, false&#x3D;not available) | 
 **policyCompliant** | **bool** | Policy compliance filter (true&#x3D;compliant, false&#x3D;non-compliant) | 
 **cwes** | **[]string** | CWE filter (e.g., CWE-79, CWE-89) - repeatable | 
 **exploitationKnown** | **bool** | KEV filter - known exploited vulnerability | 
 **publishedWindow** | **string** | Time window for published date (e.g., 30d, 1y) | 
 **namespace** | **string** | Package namespace/groupId (optional) | 

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


## GetLatestVersion

> ComponentDetailDocument GetLatestVersion(ctx).LatestVersionRequest(latestVersionRequest).Execute()

Get latest version of a component



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	sonatypeguide "github.com/sonatype-nexus-community/sonatype-guide-api-client-go/sonatypeguide"
)

func main() {
	latestVersionRequest := *sonatypeguide.NewLatestVersionRequest("Purl_example") // LatestVersionRequest | 

	configuration := sonatypeguide.NewConfiguration()
	apiClient := sonatypeguide.NewAPIClient(configuration)
	resp, r, err := apiClient.ComponentsAPI.GetLatestVersion(context.Background()).LatestVersionRequest(latestVersionRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ComponentsAPI.GetLatestVersion``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetLatestVersion`: ComponentDetailDocument
	fmt.Fprintf(os.Stdout, "Response from `ComponentsAPI.GetLatestVersion`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetLatestVersionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **latestVersionRequest** | [**LatestVersionRequest**](LatestVersionRequest.md) |  | 

### Return type

[**ComponentDetailDocument**](ComponentDetailDocument.md)

### Authorization

[bearer-jwt](../README.md#bearer-jwt)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

