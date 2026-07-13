# \AGPGovernanceAPI

All URIs are relative to *https://api.guide.sonatype.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**AgenticModeAccess**](AGPGovernanceAPI.md#AgenticModeAccess) | **Get** /api/agp/agentic-mode-access | Whether the caller&#39;s org is registered for AgentP agentic mode (org-scoped; gates the AI Fix toggle + AI agent config in the UI)
[**DeleteRepoConfig**](AGPGovernanceAPI.md#DeleteRepoConfig) | **Delete** /api/agp/repos/{installationRepoId}/config | Reset a repo to the Default Configuration by clearing its config overrides (any org member)
[**GetOrgConfig**](AGPGovernanceAPI.md#GetOrgConfig) | **Get** /api/agp/org/config | Get the AgentP Default Configuration (read: any org member)
[**GetOrgEffectiveConfig**](AGPGovernanceAPI.md#GetOrgEffectiveConfig) | **Get** /api/agp/org/effective-config | Get the rendered Default Configuration agp.yml (defaults + org) (Owner-only)
[**GetRepoConfig**](AGPGovernanceAPI.md#GetRepoConfig) | **Get** /api/agp/repos/{installationRepoId}/config | Get a repo&#39;s AgentP config overrides + inherited Default Configuration + version (any org member)
[**GetRepoEffectiveConfig**](AGPGovernanceAPI.md#GetRepoEffectiveConfig) | **Get** /api/agp/repos/{installationRepoId}/effective-config | Get the rendered effective agp.yml for a repo (defaults + org + overrides) (any org member)
[**OpenRemovalPr**](AGPGovernanceAPI.md#OpenRemovalPr) | **Post** /api/agp/repos/{installationRepoId}/removal-pr | Open (and optionally merge) a PR removing the AgentP workflow file from a repository (any org member)
[**Pause**](AGPGovernanceAPI.md#Pause) | **Post** /api/agp/repos/{installationRepoId}/pause | Pause AgentP for a repository (any org member)
[**Resume**](AGPGovernanceAPI.md#Resume) | **Post** /api/agp/repos/{installationRepoId}/resume | Resume AgentP for a repository (any org member)
[**UpdateOrgConfig**](AGPGovernanceAPI.md#UpdateOrgConfig) | **Put** /api/agp/org/config | Set the AgentP Default Configuration + developer-access flag (Owner-only)
[**UpdateRepoConfig**](AGPGovernanceAPI.md#UpdateRepoConfig) | **Put** /api/agp/repos/{installationRepoId}/config | Set per-repo AgentP config overrides (any org member)



## AgenticModeAccess

> AgenticModeAccessResponse AgenticModeAccess(ctx).Execute()

Whether the caller's org is registered for AgentP agentic mode (org-scoped; gates the AI Fix toggle + AI agent config in the UI)

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
	resp, r, err := apiClient.AGPGovernanceAPI.AgenticModeAccess(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AGPGovernanceAPI.AgenticModeAccess``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `AgenticModeAccess`: AgenticModeAccessResponse
	fmt.Fprintf(os.Stdout, "Response from `AGPGovernanceAPI.AgenticModeAccess`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiAgenticModeAccessRequest struct via the builder pattern


### Return type

[**AgenticModeAccessResponse**](AgenticModeAccessResponse.md)

### Authorization

[bearer-jwt](../README.md#bearer-jwt)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteRepoConfig

> DeleteRepoConfig(ctx, installationRepoId).ExpectedVersion(expectedVersion).Execute()

Reset a repo to the Default Configuration by clearing its config overrides (any org member)

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
	installationRepoId := int64(789) // int64 | 
	expectedVersion := int64(789) // int64 |  (optional)

	configuration := sonatypeguide.NewConfiguration()
	apiClient := sonatypeguide.NewAPIClient(configuration)
	r, err := apiClient.AGPGovernanceAPI.DeleteRepoConfig(context.Background(), installationRepoId).ExpectedVersion(expectedVersion).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AGPGovernanceAPI.DeleteRepoConfig``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**installationRepoId** | **int64** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteRepoConfigRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **expectedVersion** | **int64** |  | 

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


## GetOrgConfig

> OrgGovernanceView GetOrgConfig(ctx).Execute()

Get the AgentP Default Configuration (read: any org member)

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
	resp, r, err := apiClient.AGPGovernanceAPI.GetOrgConfig(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AGPGovernanceAPI.GetOrgConfig``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetOrgConfig`: OrgGovernanceView
	fmt.Fprintf(os.Stdout, "Response from `AGPGovernanceAPI.GetOrgConfig`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetOrgConfigRequest struct via the builder pattern


### Return type

[**OrgGovernanceView**](OrgGovernanceView.md)

### Authorization

[bearer-jwt](../README.md#bearer-jwt)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetOrgEffectiveConfig

> EffectiveConfigYamlResponse GetOrgEffectiveConfig(ctx).Execute()

Get the rendered Default Configuration agp.yml (defaults + org) (Owner-only)

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
	resp, r, err := apiClient.AGPGovernanceAPI.GetOrgEffectiveConfig(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AGPGovernanceAPI.GetOrgEffectiveConfig``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetOrgEffectiveConfig`: EffectiveConfigYamlResponse
	fmt.Fprintf(os.Stdout, "Response from `AGPGovernanceAPI.GetOrgEffectiveConfig`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetOrgEffectiveConfigRequest struct via the builder pattern


### Return type

[**EffectiveConfigYamlResponse**](EffectiveConfigYamlResponse.md)

### Authorization

[bearer-jwt](../README.md#bearer-jwt)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetRepoConfig

> RepoGovernanceView GetRepoConfig(ctx, installationRepoId).Execute()

Get a repo's AgentP config overrides + inherited Default Configuration + version (any org member)

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
	installationRepoId := int64(789) // int64 | 

	configuration := sonatypeguide.NewConfiguration()
	apiClient := sonatypeguide.NewAPIClient(configuration)
	resp, r, err := apiClient.AGPGovernanceAPI.GetRepoConfig(context.Background(), installationRepoId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AGPGovernanceAPI.GetRepoConfig``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetRepoConfig`: RepoGovernanceView
	fmt.Fprintf(os.Stdout, "Response from `AGPGovernanceAPI.GetRepoConfig`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**installationRepoId** | **int64** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetRepoConfigRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**RepoGovernanceView**](RepoGovernanceView.md)

### Authorization

[bearer-jwt](../README.md#bearer-jwt)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetRepoEffectiveConfig

> EffectiveConfigYamlResponse GetRepoEffectiveConfig(ctx, installationRepoId).Execute()

Get the rendered effective agp.yml for a repo (defaults + org + overrides) (any org member)

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
	installationRepoId := int64(789) // int64 | 

	configuration := sonatypeguide.NewConfiguration()
	apiClient := sonatypeguide.NewAPIClient(configuration)
	resp, r, err := apiClient.AGPGovernanceAPI.GetRepoEffectiveConfig(context.Background(), installationRepoId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AGPGovernanceAPI.GetRepoEffectiveConfig``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetRepoEffectiveConfig`: EffectiveConfigYamlResponse
	fmt.Fprintf(os.Stdout, "Response from `AGPGovernanceAPI.GetRepoEffectiveConfig`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**installationRepoId** | **int64** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetRepoEffectiveConfigRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**EffectiveConfigYamlResponse**](EffectiveConfigYamlResponse.md)

### Authorization

[bearer-jwt](../README.md#bearer-jwt)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## OpenRemovalPr

> RemovalPrResult OpenRemovalPr(ctx, installationRepoId).Merge(merge).Execute()

Open (and optionally merge) a PR removing the AgentP workflow file from a repository (any org member)

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
	installationRepoId := int64(789) // int64 | 
	merge := true // bool |  (optional) (default to false)

	configuration := sonatypeguide.NewConfiguration()
	apiClient := sonatypeguide.NewAPIClient(configuration)
	resp, r, err := apiClient.AGPGovernanceAPI.OpenRemovalPr(context.Background(), installationRepoId).Merge(merge).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AGPGovernanceAPI.OpenRemovalPr``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `OpenRemovalPr`: RemovalPrResult
	fmt.Fprintf(os.Stdout, "Response from `AGPGovernanceAPI.OpenRemovalPr`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**installationRepoId** | **int64** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiOpenRemovalPrRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **merge** | **bool** |  | [default to false]

### Return type

[**RemovalPrResult**](RemovalPrResult.md)

### Authorization

[bearer-jwt](../README.md#bearer-jwt)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## Pause

> Pause(ctx, installationRepoId).Execute()

Pause AgentP for a repository (any org member)

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
	installationRepoId := int64(789) // int64 | 

	configuration := sonatypeguide.NewConfiguration()
	apiClient := sonatypeguide.NewAPIClient(configuration)
	r, err := apiClient.AGPGovernanceAPI.Pause(context.Background(), installationRepoId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AGPGovernanceAPI.Pause``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**installationRepoId** | **int64** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiPauseRequest struct via the builder pattern


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


## Resume

> Resume(ctx, installationRepoId).Execute()

Resume AgentP for a repository (any org member)

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
	installationRepoId := int64(789) // int64 | 

	configuration := sonatypeguide.NewConfiguration()
	apiClient := sonatypeguide.NewAPIClient(configuration)
	r, err := apiClient.AGPGovernanceAPI.Resume(context.Background(), installationRepoId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AGPGovernanceAPI.Resume``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**installationRepoId** | **int64** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiResumeRequest struct via the builder pattern


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


## UpdateOrgConfig

> GovernanceWriteResponse UpdateOrgConfig(ctx).OrgConfigRequest(orgConfigRequest).Execute()

Set the AgentP Default Configuration + developer-access flag (Owner-only)

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
	orgConfigRequest := *sonatypeguide.NewOrgConfigRequest(map[string]interface{}{"key": interface{}(123)}) // OrgConfigRequest | 

	configuration := sonatypeguide.NewConfiguration()
	apiClient := sonatypeguide.NewAPIClient(configuration)
	resp, r, err := apiClient.AGPGovernanceAPI.UpdateOrgConfig(context.Background()).OrgConfigRequest(orgConfigRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AGPGovernanceAPI.UpdateOrgConfig``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateOrgConfig`: GovernanceWriteResponse
	fmt.Fprintf(os.Stdout, "Response from `AGPGovernanceAPI.UpdateOrgConfig`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiUpdateOrgConfigRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **orgConfigRequest** | [**OrgConfigRequest**](OrgConfigRequest.md) |  | 

### Return type

[**GovernanceWriteResponse**](GovernanceWriteResponse.md)

### Authorization

[bearer-jwt](../README.md#bearer-jwt)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateRepoConfig

> GovernanceWriteResponse UpdateRepoConfig(ctx, installationRepoId).RepoConfigRequest(repoConfigRequest).Execute()

Set per-repo AgentP config overrides (any org member)

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
	installationRepoId := int64(789) // int64 | 
	repoConfigRequest := *sonatypeguide.NewRepoConfigRequest(map[string]interface{}{"key": interface{}(123)}) // RepoConfigRequest | 

	configuration := sonatypeguide.NewConfiguration()
	apiClient := sonatypeguide.NewAPIClient(configuration)
	resp, r, err := apiClient.AGPGovernanceAPI.UpdateRepoConfig(context.Background(), installationRepoId).RepoConfigRequest(repoConfigRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AGPGovernanceAPI.UpdateRepoConfig``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateRepoConfig`: GovernanceWriteResponse
	fmt.Fprintf(os.Stdout, "Response from `AGPGovernanceAPI.UpdateRepoConfig`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**installationRepoId** | **int64** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateRepoConfigRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **repoConfigRequest** | [**RepoConfigRequest**](RepoConfigRequest.md) |  | 

### Return type

[**GovernanceWriteResponse**](GovernanceWriteResponse.md)

### Authorization

[bearer-jwt](../README.md#bearer-jwt)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

