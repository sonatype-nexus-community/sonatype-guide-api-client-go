# \RecommendationsAPI

All URIs are relative to *https://api.guide.sonatype.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetRecommendations**](RecommendationsAPI.md#GetRecommendations) | **Post** /recommendations | Get version upgrade recommendations



## GetRecommendations

> RecommendationResponse GetRecommendations(ctx).RecommendationRequest(recommendationRequest).Execute()

Get version upgrade recommendations



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
	recommendationRequest := *sonatypeguide.NewRecommendationRequest() // RecommendationRequest | 

	configuration := sonatypeguide.NewConfiguration()
	apiClient := sonatypeguide.NewAPIClient(configuration)
	resp, r, err := apiClient.RecommendationsAPI.GetRecommendations(context.Background()).RecommendationRequest(recommendationRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `RecommendationsAPI.GetRecommendations``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetRecommendations`: RecommendationResponse
	fmt.Fprintf(os.Stdout, "Response from `RecommendationsAPI.GetRecommendations`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetRecommendationsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **recommendationRequest** | [**RecommendationRequest**](RecommendationRequest.md) |  | 

### Return type

[**RecommendationResponse**](RecommendationResponse.md)

### Authorization

[bearer-jwt](../README.md#bearer-jwt)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

