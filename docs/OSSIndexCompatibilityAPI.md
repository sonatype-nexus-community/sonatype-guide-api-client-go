# \OSSIndexCompatibilityAPI

All URIs are relative to *https://api.guide.sonatype.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetComponentReport**](OSSIndexCompatibilityAPI.md#GetComponentReport) | **Get** /api/v3/authorized/component-report/** | Get component report by PURL
[**GetComponentReport1**](OSSIndexCompatibilityAPI.md#GetComponentReport1) | **Get** /api/v3/component-report/** | Get component report by PURL
[**GetComponentReports**](OSSIndexCompatibilityAPI.md#GetComponentReports) | **Post** /api/v3/component-report | Get component reports for multiple PURLs
[**GetComponentReports1**](OSSIndexCompatibilityAPI.md#GetComponentReports1) | **Post** /api/v3/authorized/component-report | Get component reports for multiple PURLs
[**GetVersion**](OSSIndexCompatibilityAPI.md#GetVersion) | **Get** /api/v3/version | Get API version



## GetComponentReport

> ComponentReportGet GetComponentReport(ctx).UserAgent(userAgent).Execute()

Get component report by PURL



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
	userAgent := "userAgent_example" // string |  (optional)

	configuration := sonatypeguide.NewConfiguration()
	apiClient := sonatypeguide.NewAPIClient(configuration)
	resp, r, err := apiClient.OSSIndexCompatibilityAPI.GetComponentReport(context.Background()).UserAgent(userAgent).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OSSIndexCompatibilityAPI.GetComponentReport``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetComponentReport`: ComponentReportGet
	fmt.Fprintf(os.Stdout, "Response from `OSSIndexCompatibilityAPI.GetComponentReport`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetComponentReportRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **userAgent** | **string** |  | 

### Return type

[**ComponentReportGet**](ComponentReportGet.md)

### Authorization

[ossi-basic-auth](../README.md#ossi-basic-auth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/vnd.ossindex.component-report.v1+json, application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetComponentReport1

> ComponentReportGet GetComponentReport1(ctx).UserAgent(userAgent).Execute()

Get component report by PURL



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
	userAgent := "userAgent_example" // string |  (optional)

	configuration := sonatypeguide.NewConfiguration()
	apiClient := sonatypeguide.NewAPIClient(configuration)
	resp, r, err := apiClient.OSSIndexCompatibilityAPI.GetComponentReport1(context.Background()).UserAgent(userAgent).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OSSIndexCompatibilityAPI.GetComponentReport1``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetComponentReport1`: ComponentReportGet
	fmt.Fprintf(os.Stdout, "Response from `OSSIndexCompatibilityAPI.GetComponentReport1`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetComponentReport1Request struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **userAgent** | **string** |  | 

### Return type

[**ComponentReportGet**](ComponentReportGet.md)

### Authorization

[ossi-basic-auth](../README.md#ossi-basic-auth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/vnd.ossindex.component-report.v1+json, application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetComponentReports

> []ComponentReportPost GetComponentReports(ctx).PurlRequestPost(purlRequestPost).UserAgent(userAgent).Execute()

Get component reports for multiple PURLs



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
	purlRequestPost := *sonatypeguide.NewPurlRequestPost([]string{"Coordinates_example"}) // PurlRequestPost | 
	userAgent := "userAgent_example" // string |  (optional)

	configuration := sonatypeguide.NewConfiguration()
	apiClient := sonatypeguide.NewAPIClient(configuration)
	resp, r, err := apiClient.OSSIndexCompatibilityAPI.GetComponentReports(context.Background()).PurlRequestPost(purlRequestPost).UserAgent(userAgent).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OSSIndexCompatibilityAPI.GetComponentReports``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetComponentReports`: []ComponentReportPost
	fmt.Fprintf(os.Stdout, "Response from `OSSIndexCompatibilityAPI.GetComponentReports`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetComponentReportsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **purlRequestPost** | [**PurlRequestPost**](PurlRequestPost.md) |  | 
 **userAgent** | **string** |  | 

### Return type

[**[]ComponentReportPost**](ComponentReportPost.md)

### Authorization

[ossi-basic-auth](../README.md#ossi-basic-auth)

### HTTP request headers

- **Content-Type**: application/json, application/vnd.ossindex.component-report-request.v1+json
- **Accept**: application/vnd.ossindex.component-report.v1+json, application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetComponentReports1

> []ComponentReportPost GetComponentReports1(ctx).PurlRequestPost(purlRequestPost).UserAgent(userAgent).Execute()

Get component reports for multiple PURLs



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
	purlRequestPost := *sonatypeguide.NewPurlRequestPost([]string{"Coordinates_example"}) // PurlRequestPost | 
	userAgent := "userAgent_example" // string |  (optional)

	configuration := sonatypeguide.NewConfiguration()
	apiClient := sonatypeguide.NewAPIClient(configuration)
	resp, r, err := apiClient.OSSIndexCompatibilityAPI.GetComponentReports1(context.Background()).PurlRequestPost(purlRequestPost).UserAgent(userAgent).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OSSIndexCompatibilityAPI.GetComponentReports1``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetComponentReports1`: []ComponentReportPost
	fmt.Fprintf(os.Stdout, "Response from `OSSIndexCompatibilityAPI.GetComponentReports1`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetComponentReports1Request struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **purlRequestPost** | [**PurlRequestPost**](PurlRequestPost.md) |  | 
 **userAgent** | **string** |  | 

### Return type

[**[]ComponentReportPost**](ComponentReportPost.md)

### Authorization

[ossi-basic-auth](../README.md#ossi-basic-auth)

### HTTP request headers

- **Content-Type**: application/json, application/vnd.ossindex.component-report-request.v1+json
- **Accept**: application/vnd.ossindex.component-report.v1+json, application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetVersion

> string GetVersion(ctx).Execute()

Get API version



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
	resp, r, err := apiClient.OSSIndexCompatibilityAPI.GetVersion(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OSSIndexCompatibilityAPI.GetVersion``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetVersion`: string
	fmt.Fprintf(os.Stdout, "Response from `OSSIndexCompatibilityAPI.GetVersion`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetVersionRequest struct via the builder pattern


### Return type

**string**

### Authorization

[ossi-basic-auth](../README.md#ossi-basic-auth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

