# RolesApi

All URIs are relative to *https://api.sensecoreai.com*

|Method | HTTP request | Description|
|------------- | ------------- | -------------|
|[**changeUserRoleApiV1AdminRolesUsersUserIdRolePatch**](#changeuserroleapiv1adminrolesusersuseridrolepatch) | **PATCH** /api/v1/admin/roles/users/{user_id}/role | Change User Role|
|[**changeUserRoleApiV1AdminRolesUsersUserIdRolePatch_0**](#changeuserroleapiv1adminrolesusersuseridrolepatch_0) | **PATCH** /api/v1/admin/roles/users/{user_id}/role | Change User Role|
|[**getMyPermissionsApiV1AdminRolesMyPermissionsGet**](#getmypermissionsapiv1adminrolesmypermissionsget) | **GET** /api/v1/admin/roles/my-permissions | Get My Permissions|
|[**getMyPermissionsApiV1AdminRolesMyPermissionsGet_0**](#getmypermissionsapiv1adminrolesmypermissionsget_0) | **GET** /api/v1/admin/roles/my-permissions | Get My Permissions|
|[**getRoleDefinitionsApiV1AdminRolesDefinitionsGet**](#getroledefinitionsapiv1adminrolesdefinitionsget) | **GET** /api/v1/admin/roles/definitions | Get Role Definitions|
|[**getRoleDefinitionsApiV1AdminRolesDefinitionsGet_0**](#getroledefinitionsapiv1adminrolesdefinitionsget_0) | **GET** /api/v1/admin/roles/definitions | Get Role Definitions|
|[**getUsersWithRolesApiV1AdminRolesUsersGet**](#getuserswithrolesapiv1adminrolesusersget) | **GET** /api/v1/admin/roles/users | Get Users With Roles|
|[**getUsersWithRolesApiV1AdminRolesUsersGet_0**](#getuserswithrolesapiv1adminrolesusersget_0) | **GET** /api/v1/admin/roles/users | Get Users With Roles|
|[**resetPermissionsApiV1AdminRolesUsersUserIdResetPost**](#resetpermissionsapiv1adminrolesusersuseridresetpost) | **POST** /api/v1/admin/roles/users/{user_id}/reset | Reset Permissions|
|[**resetPermissionsApiV1AdminRolesUsersUserIdResetPost_0**](#resetpermissionsapiv1adminrolesusersuseridresetpost_0) | **POST** /api/v1/admin/roles/users/{user_id}/reset | Reset Permissions|
|[**updateUserPermissionsApiV1AdminRolesUsersUserIdPermissionsPatch**](#updateuserpermissionsapiv1adminrolesusersuseridpermissionspatch) | **PATCH** /api/v1/admin/roles/users/{user_id}/permissions | Update User Permissions|
|[**updateUserPermissionsApiV1AdminRolesUsersUserIdPermissionsPatch_0**](#updateuserpermissionsapiv1adminrolesusersuseridpermissionspatch_0) | **PATCH** /api/v1/admin/roles/users/{user_id}/permissions | Update User Permissions|

# **changeUserRoleApiV1AdminRolesUsersUserIdRolePatch**
> any changeUserRoleApiV1AdminRolesUsersUserIdRolePatch(body)

Change a user role and reset permissions to role defaults.

### Example

```typescript
import {
    RolesApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new RolesApi(configuration);

let userId: string; // (default to undefined)
let body: object; //

const { status, data } = await apiInstance.changeUserRoleApiV1AdminRolesUsersUserIdRolePatch(
    userId,
    body
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **body** | **object**|  | |
| **userId** | [**string**] |  | defaults to undefined|


### Return type

**any**

### Authorization

[OAuth2PasswordBearer](../README.md#OAuth2PasswordBearer)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | Successful Response |  -  |
|**422** | Validation Error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **changeUserRoleApiV1AdminRolesUsersUserIdRolePatch_0**
> any changeUserRoleApiV1AdminRolesUsersUserIdRolePatch_0(body)

Change a user role and reset permissions to role defaults.

### Example

```typescript
import {
    RolesApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new RolesApi(configuration);

let userId: string; // (default to undefined)
let body: object; //

const { status, data } = await apiInstance.changeUserRoleApiV1AdminRolesUsersUserIdRolePatch_0(
    userId,
    body
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **body** | **object**|  | |
| **userId** | [**string**] |  | defaults to undefined|


### Return type

**any**

### Authorization

[OAuth2PasswordBearer](../README.md#OAuth2PasswordBearer)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | Successful Response |  -  |
|**422** | Validation Error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getMyPermissionsApiV1AdminRolesMyPermissionsGet**
> any getMyPermissionsApiV1AdminRolesMyPermissionsGet()

Get the current user permissions (for frontend gating).

### Example

```typescript
import {
    RolesApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new RolesApi(configuration);

const { status, data } = await apiInstance.getMyPermissionsApiV1AdminRolesMyPermissionsGet();
```

### Parameters
This endpoint does not have any parameters.


### Return type

**any**

### Authorization

[OAuth2PasswordBearer](../README.md#OAuth2PasswordBearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | Successful Response |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getMyPermissionsApiV1AdminRolesMyPermissionsGet_0**
> any getMyPermissionsApiV1AdminRolesMyPermissionsGet_0()

Get the current user permissions (for frontend gating).

### Example

```typescript
import {
    RolesApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new RolesApi(configuration);

const { status, data } = await apiInstance.getMyPermissionsApiV1AdminRolesMyPermissionsGet_0();
```

### Parameters
This endpoint does not have any parameters.


### Return type

**any**

### Authorization

[OAuth2PasswordBearer](../README.md#OAuth2PasswordBearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | Successful Response |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getRoleDefinitionsApiV1AdminRolesDefinitionsGet**
> any getRoleDefinitionsApiV1AdminRolesDefinitionsGet()

Return all role definitions with their default permissions.

### Example

```typescript
import {
    RolesApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new RolesApi(configuration);

const { status, data } = await apiInstance.getRoleDefinitionsApiV1AdminRolesDefinitionsGet();
```

### Parameters
This endpoint does not have any parameters.


### Return type

**any**

### Authorization

[OAuth2PasswordBearer](../README.md#OAuth2PasswordBearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | Successful Response |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getRoleDefinitionsApiV1AdminRolesDefinitionsGet_0**
> any getRoleDefinitionsApiV1AdminRolesDefinitionsGet_0()

Return all role definitions with their default permissions.

### Example

```typescript
import {
    RolesApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new RolesApi(configuration);

const { status, data } = await apiInstance.getRoleDefinitionsApiV1AdminRolesDefinitionsGet_0();
```

### Parameters
This endpoint does not have any parameters.


### Return type

**any**

### Authorization

[OAuth2PasswordBearer](../README.md#OAuth2PasswordBearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | Successful Response |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getUsersWithRolesApiV1AdminRolesUsersGet**
> any getUsersWithRolesApiV1AdminRolesUsersGet()

List all users with their roles and permission summary.

### Example

```typescript
import {
    RolesApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new RolesApi(configuration);

const { status, data } = await apiInstance.getUsersWithRolesApiV1AdminRolesUsersGet();
```

### Parameters
This endpoint does not have any parameters.


### Return type

**any**

### Authorization

[OAuth2PasswordBearer](../README.md#OAuth2PasswordBearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | Successful Response |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getUsersWithRolesApiV1AdminRolesUsersGet_0**
> any getUsersWithRolesApiV1AdminRolesUsersGet_0()

List all users with their roles and permission summary.

### Example

```typescript
import {
    RolesApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new RolesApi(configuration);

const { status, data } = await apiInstance.getUsersWithRolesApiV1AdminRolesUsersGet_0();
```

### Parameters
This endpoint does not have any parameters.


### Return type

**any**

### Authorization

[OAuth2PasswordBearer](../README.md#OAuth2PasswordBearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | Successful Response |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **resetPermissionsApiV1AdminRolesUsersUserIdResetPost**
> any resetPermissionsApiV1AdminRolesUsersUserIdResetPost()

Reset user permissions back to their role defaults.

### Example

```typescript
import {
    RolesApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new RolesApi(configuration);

let userId: string; // (default to undefined)

const { status, data } = await apiInstance.resetPermissionsApiV1AdminRolesUsersUserIdResetPost(
    userId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **userId** | [**string**] |  | defaults to undefined|


### Return type

**any**

### Authorization

[OAuth2PasswordBearer](../README.md#OAuth2PasswordBearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | Successful Response |  -  |
|**422** | Validation Error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **resetPermissionsApiV1AdminRolesUsersUserIdResetPost_0**
> any resetPermissionsApiV1AdminRolesUsersUserIdResetPost_0()

Reset user permissions back to their role defaults.

### Example

```typescript
import {
    RolesApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new RolesApi(configuration);

let userId: string; // (default to undefined)

const { status, data } = await apiInstance.resetPermissionsApiV1AdminRolesUsersUserIdResetPost_0(
    userId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **userId** | [**string**] |  | defaults to undefined|


### Return type

**any**

### Authorization

[OAuth2PasswordBearer](../README.md#OAuth2PasswordBearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | Successful Response |  -  |
|**422** | Validation Error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **updateUserPermissionsApiV1AdminRolesUsersUserIdPermissionsPatch**
> any updateUserPermissionsApiV1AdminRolesUsersUserIdPermissionsPatch(body)

Update individual permissions for a user (custom override).

### Example

```typescript
import {
    RolesApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new RolesApi(configuration);

let userId: string; // (default to undefined)
let body: object; //

const { status, data } = await apiInstance.updateUserPermissionsApiV1AdminRolesUsersUserIdPermissionsPatch(
    userId,
    body
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **body** | **object**|  | |
| **userId** | [**string**] |  | defaults to undefined|


### Return type

**any**

### Authorization

[OAuth2PasswordBearer](../README.md#OAuth2PasswordBearer)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | Successful Response |  -  |
|**422** | Validation Error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **updateUserPermissionsApiV1AdminRolesUsersUserIdPermissionsPatch_0**
> any updateUserPermissionsApiV1AdminRolesUsersUserIdPermissionsPatch_0(body)

Update individual permissions for a user (custom override).

### Example

```typescript
import {
    RolesApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new RolesApi(configuration);

let userId: string; // (default to undefined)
let body: object; //

const { status, data } = await apiInstance.updateUserPermissionsApiV1AdminRolesUsersUserIdPermissionsPatch_0(
    userId,
    body
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **body** | **object**|  | |
| **userId** | [**string**] |  | defaults to undefined|


### Return type

**any**

### Authorization

[OAuth2PasswordBearer](../README.md#OAuth2PasswordBearer)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | Successful Response |  -  |
|**422** | Validation Error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

