# \CurrentUserOrganizationAPI

All URIs are relative to *https://api.guide.sonatype.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**AcceptInvitation**](CurrentUserOrganizationAPI.md#AcceptInvitation) | **Post** /users/me/organization/invitations/{invitationToken}/accept | Accept organization invitation
[**BulkRemoveMembersOrInvitations**](CurrentUserOrganizationAPI.md#BulkRemoveMembersOrInvitations) | **Delete** /users/me/organization/members | Bulk remove members or invitations from organization
[**GetCurrentUserOrganization**](CurrentUserOrganizationAPI.md#GetCurrentUserOrganization) | **Get** /users/me/organization | Get current user&#39;s organization
[**InviteUsers**](CurrentUserOrganizationAPI.md#InviteUsers) | **Post** /users/me/organization/members/invite | Invite users to current user&#39;s an organization
[**LeaveOrganization**](CurrentUserOrganizationAPI.md#LeaveOrganization) | **Delete** /users/me/organization/membership | Leave organization
[**RemoveMemberOrInvitation**](CurrentUserOrganizationAPI.md#RemoveMemberOrInvitation) | **Delete** /users/me/organization/members/{email} | Remove member or invitation from organization
[**RetrieveOrganizationMembersAsCsv**](CurrentUserOrganizationAPI.md#RetrieveOrganizationMembersAsCsv) | **Get** /users/me/organization/members | Retrieve current user&#39;s organization members and invitees
[**UpdateOrganization**](CurrentUserOrganizationAPI.md#UpdateOrganization) | **Put** /users/me/organization | Update current user&#39;s organization



## AcceptInvitation

> AcceptInvitation(ctx, invitationToken).Execute()

Accept organization invitation



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
	invitationToken := "invitationToken_example" // string | 

	configuration := sonatypeguide.NewConfiguration()
	apiClient := sonatypeguide.NewAPIClient(configuration)
	r, err := apiClient.CurrentUserOrganizationAPI.AcceptInvitation(context.Background(), invitationToken).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CurrentUserOrganizationAPI.AcceptInvitation``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**invitationToken** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiAcceptInvitationRequest struct via the builder pattern


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


## BulkRemoveMembersOrInvitations

> BulkRemoveMembersOrInvitations(ctx).BulkRemoveMembersRequest(bulkRemoveMembersRequest).Execute()

Bulk remove members or invitations from organization



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
	bulkRemoveMembersRequest := *sonatypeguide.NewBulkRemoveMembersRequest([]string{"Emails_example"}) // BulkRemoveMembersRequest | 

	configuration := sonatypeguide.NewConfiguration()
	apiClient := sonatypeguide.NewAPIClient(configuration)
	r, err := apiClient.CurrentUserOrganizationAPI.BulkRemoveMembersOrInvitations(context.Background()).BulkRemoveMembersRequest(bulkRemoveMembersRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CurrentUserOrganizationAPI.BulkRemoveMembersOrInvitations``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiBulkRemoveMembersOrInvitationsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **bulkRemoveMembersRequest** | [**BulkRemoveMembersRequest**](BulkRemoveMembersRequest.md) |  | 

### Return type

 (empty response body)

### Authorization

[bearer-jwt](../README.md#bearer-jwt)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetCurrentUserOrganization

> GetCurrentUserOrganization(ctx).Execute()

Get current user's organization



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
	r, err := apiClient.CurrentUserOrganizationAPI.GetCurrentUserOrganization(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CurrentUserOrganizationAPI.GetCurrentUserOrganization``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetCurrentUserOrganizationRequest struct via the builder pattern


### Return type

 (empty response body)

### Authorization

[bearer-jwt](../README.md#bearer-jwt)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json, */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## InviteUsers

> InviteUsers(ctx).InviteUsersRequest(inviteUsersRequest).Execute()

Invite users to current user's an organization



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
	inviteUsersRequest := *sonatypeguide.NewInviteUsersRequest([]string{"Emails_example"}) // InviteUsersRequest | 

	configuration := sonatypeguide.NewConfiguration()
	apiClient := sonatypeguide.NewAPIClient(configuration)
	r, err := apiClient.CurrentUserOrganizationAPI.InviteUsers(context.Background()).InviteUsersRequest(inviteUsersRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CurrentUserOrganizationAPI.InviteUsers``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiInviteUsersRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **inviteUsersRequest** | [**InviteUsersRequest**](InviteUsersRequest.md) |  | 

### Return type

 (empty response body)

### Authorization

[bearer-jwt](../README.md#bearer-jwt)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json, */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## LeaveOrganization

> LeaveOrganization(ctx).Execute()

Leave organization



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
	r, err := apiClient.CurrentUserOrganizationAPI.LeaveOrganization(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CurrentUserOrganizationAPI.LeaveOrganization``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiLeaveOrganizationRequest struct via the builder pattern


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


## RemoveMemberOrInvitation

> RemoveMemberOrInvitation(ctx, email).Execute()

Remove member or invitation from organization



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
	email := "email_example" // string | 

	configuration := sonatypeguide.NewConfiguration()
	apiClient := sonatypeguide.NewAPIClient(configuration)
	r, err := apiClient.CurrentUserOrganizationAPI.RemoveMemberOrInvitation(context.Background(), email).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CurrentUserOrganizationAPI.RemoveMemberOrInvitation``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**email** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiRemoveMemberOrInvitationRequest struct via the builder pattern


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


## RetrieveOrganizationMembersAsCsv

> RetrieveOrganizationMembersAsCsv(ctx).Execute()

Retrieve current user's organization members and invitees



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
	r, err := apiClient.CurrentUserOrganizationAPI.RetrieveOrganizationMembersAsCsv(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CurrentUserOrganizationAPI.RetrieveOrganizationMembersAsCsv``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiRetrieveOrganizationMembersAsCsvRequest struct via the builder pattern


### Return type

 (empty response body)

### Authorization

[bearer-jwt](../README.md#bearer-jwt)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/csv

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateOrganization

> UpdateOrganization(ctx).UpdateOrganizationRequest(updateOrganizationRequest).Execute()

Update current user's organization



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
	updateOrganizationRequest := *sonatypeguide.NewUpdateOrganizationRequest() // UpdateOrganizationRequest | 

	configuration := sonatypeguide.NewConfiguration()
	apiClient := sonatypeguide.NewAPIClient(configuration)
	r, err := apiClient.CurrentUserOrganizationAPI.UpdateOrganization(context.Background()).UpdateOrganizationRequest(updateOrganizationRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CurrentUserOrganizationAPI.UpdateOrganization``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiUpdateOrganizationRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **updateOrganizationRequest** | [**UpdateOrganizationRequest**](UpdateOrganizationRequest.md) |  | 

### Return type

 (empty response body)

### Authorization

[bearer-jwt](../README.md#bearer-jwt)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json, */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

