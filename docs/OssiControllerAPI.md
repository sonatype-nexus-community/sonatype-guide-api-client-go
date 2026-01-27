# \OssiControllerAPI

All URIs are relative to *http://api.guide.sonatype.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetComponentReport**](OssiControllerAPI.md#GetComponentReport) | **Get** /api/v3/authorized/component-report/** | 
[**GetComponentReport1**](OssiControllerAPI.md#GetComponentReport1) | **Get** /api/v3/component-report/** | 
[**GetComponentReports**](OssiControllerAPI.md#GetComponentReports) | **Post** /api/v3/component-report | 
[**GetComponentReports1**](OssiControllerAPI.md#GetComponentReports1) | **Post** /api/v3/authorized/component-report | 
[**GetVersion**](OssiControllerAPI.md#GetVersion) | **Get** /api/v3/version | 



## GetComponentReport

> ComponentReportGet GetComponentReport(ctx).UserAgent(userAgent).Execute()



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
	userAgent := "userAgent_example" // string |  (optional)

	configuration := sonatypeguide.NewConfiguration()
	apiClient := sonatypeguide.NewAPIClient(configuration)
	resp, r, err := apiClient.OssiControllerAPI.GetComponentReport(context.Background()).UserAgent(userAgent).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OssiControllerAPI.GetComponentReport``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetComponentReport`: ComponentReportGet
	fmt.Fprintf(os.Stdout, "Response from `OssiControllerAPI.GetComponentReport`: %v\n", resp)
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

[bearer-jwt](../README.md#bearer-jwt)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json, application/vnd.ossindex.component-report.v1+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetComponentReport1

> ComponentReportGet GetComponentReport1(ctx).UserAgent(userAgent).Execute()



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
	userAgent := "userAgent_example" // string |  (optional)

	configuration := sonatypeguide.NewConfiguration()
	apiClient := sonatypeguide.NewAPIClient(configuration)
	resp, r, err := apiClient.OssiControllerAPI.GetComponentReport1(context.Background()).UserAgent(userAgent).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OssiControllerAPI.GetComponentReport1``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetComponentReport1`: ComponentReportGet
	fmt.Fprintf(os.Stdout, "Response from `OssiControllerAPI.GetComponentReport1`: %v\n", resp)
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

[bearer-jwt](../README.md#bearer-jwt)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json, application/vnd.ossindex.component-report.v1+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetComponentReports

> []ComponentReportPost GetComponentReports(ctx).PurlRequestPost(purlRequestPost).UserAgent(userAgent).Execute()



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
	purlRequestPost := *sonatypeguide.NewPurlRequestPost([]string{"Coordinates_example"}) // PurlRequestPost | 
	userAgent := "userAgent_example" // string |  (optional)

	configuration := sonatypeguide.NewConfiguration()
	apiClient := sonatypeguide.NewAPIClient(configuration)
	resp, r, err := apiClient.OssiControllerAPI.GetComponentReports(context.Background()).PurlRequestPost(purlRequestPost).UserAgent(userAgent).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OssiControllerAPI.GetComponentReports``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetComponentReports`: []ComponentReportPost
	fmt.Fprintf(os.Stdout, "Response from `OssiControllerAPI.GetComponentReports`: %v\n", resp)
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

[bearer-jwt](../README.md#bearer-jwt)

### HTTP request headers

- **Content-Type**: application/json, application/vnd.ossindex.component-report-request.v1+json
- **Accept**: application/json, application/vnd.ossindex.component-report.v1+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetComponentReports1

> []ComponentReportPost GetComponentReports1(ctx).PurlRequestPost(purlRequestPost).UserAgent(userAgent).Execute()



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
	purlRequestPost := *sonatypeguide.NewPurlRequestPost([]string{"Coordinates_example"}) // PurlRequestPost | 
	userAgent := "userAgent_example" // string |  (optional)

	configuration := sonatypeguide.NewConfiguration()
	apiClient := sonatypeguide.NewAPIClient(configuration)
	resp, r, err := apiClient.OssiControllerAPI.GetComponentReports1(context.Background()).PurlRequestPost(purlRequestPost).UserAgent(userAgent).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OssiControllerAPI.GetComponentReports1``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetComponentReports1`: []ComponentReportPost
	fmt.Fprintf(os.Stdout, "Response from `OssiControllerAPI.GetComponentReports1`: %v\n", resp)
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

[bearer-jwt](../README.md#bearer-jwt)

### HTTP request headers

- **Content-Type**: application/json, application/vnd.ossindex.component-report-request.v1+json
- **Accept**: application/json, application/vnd.ossindex.component-report.v1+json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetVersion

> string GetVersion(ctx).Execute()



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
	resp, r, err := apiClient.OssiControllerAPI.GetVersion(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `OssiControllerAPI.GetVersion``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetVersion`: string
	fmt.Fprintf(os.Stdout, "Response from `OssiControllerAPI.GetVersion`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetVersionRequest struct via the builder pattern


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

