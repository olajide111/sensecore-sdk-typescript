# AuthApi

All URIs are relative to *https://api.sensecoreai.com*

|Method | HTTP request | Description|
|------------- | ------------- | -------------|
|[**getMeApiV1AuthMeGet**](#getmeapiv1authmeget) | **GET** /api/v1/auth/me | Get Me|
|[**loginApiV1AuthLoginPost**](#loginapiv1authloginpost) | **POST** /api/v1/auth/login | Get access token|
|[**myPermissionsApiV1MePermissionsGet**](#mypermissionsapiv1mepermissionsget) | **GET** /api/v1/me/permissions | My Permissions|
|[**registerApiV1AuthRegisterPost**](#registerapiv1authregisterpost) | **POST** /api/v1/auth/register | Register|
|[**resetPasswordApiV1AuthResetPasswordPost**](#resetpasswordapiv1authresetpasswordpost) | **POST** /api/v1/auth/reset-password | Reset Password|
|[**verifyApiV1AuthVerifyGet**](#verifyapiv1authverifyget) | **GET** /api/v1/auth/verify | Verify|

# **getMeApiV1AuthMeGet**
> object getMeApiV1AuthMeGet()


### Example

```typescript
import {
    AuthApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new AuthApi(configuration);

const { status, data } = await apiInstance.getMeApiV1AuthMeGet();
```

### Parameters
This endpoint does not have any parameters.


### Return type

**object**

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

# **loginApiV1AuthLoginPost**
> any loginApiV1AuthLoginPost()

Exchange email + password for a JWT access token. Include token in all requests: `Authorization: Bearer <token>`

### Example

```typescript
import {
    AuthApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new AuthApi(configuration);

let username: string; // (default to undefined)
let password: string; // (default to undefined)
let grantType: string; // (optional) (default to undefined)
let scope: string; // (optional) (default to '')
let clientId: string; // (optional) (default to undefined)
let clientSecret: string; // (optional) (default to undefined)

const { status, data } = await apiInstance.loginApiV1AuthLoginPost(
    username,
    password,
    grantType,
    scope,
    clientId,
    clientSecret
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **username** | [**string**] |  | defaults to undefined|
| **password** | [**string**] |  | defaults to undefined|
| **grantType** | [**string**] |  | (optional) defaults to undefined|
| **scope** | [**string**] |  | (optional) defaults to ''|
| **clientId** | [**string**] |  | (optional) defaults to undefined|
| **clientSecret** | [**string**] |  | (optional) defaults to undefined|


### Return type

**any**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/x-www-form-urlencoded
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | Successful Response |  -  |
|**422** | Validation Error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **myPermissionsApiV1MePermissionsGet**
> any myPermissionsApiV1MePermissionsGet()

Return current user role and permissions for frontend gating.

### Example

```typescript
import {
    AuthApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new AuthApi(configuration);

const { status, data } = await apiInstance.myPermissionsApiV1MePermissionsGet();
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

# **registerApiV1AuthRegisterPost**
> { [key: string]: string | null; } registerApiV1AuthRegisterPost(registerRequest)


### Example

```typescript
import {
    AuthApi,
    Configuration,
    RegisterRequest
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new AuthApi(configuration);

let registerRequest: RegisterRequest; //

const { status, data } = await apiInstance.registerApiV1AuthRegisterPost(
    registerRequest
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **registerRequest** | **RegisterRequest**|  | |


### Return type

**{ [key: string]: string | null; }**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | Successful Response |  -  |
|**422** | Validation Error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **resetPasswordApiV1AuthResetPasswordPost**
> { [key: string]: string | null; } resetPasswordApiV1AuthResetPasswordPost(resetRequest)


### Example

```typescript
import {
    AuthApi,
    Configuration,
    ResetRequest
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new AuthApi(configuration);

let resetRequest: ResetRequest; //

const { status, data } = await apiInstance.resetPasswordApiV1AuthResetPasswordPost(
    resetRequest
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **resetRequest** | **ResetRequest**|  | |


### Return type

**{ [key: string]: string | null; }**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | Successful Response |  -  |
|**422** | Validation Error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **verifyApiV1AuthVerifyGet**
> { [key: string]: string | null; } verifyApiV1AuthVerifyGet()


### Example

```typescript
import {
    AuthApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new AuthApi(configuration);

let token: string; //Email verification token (default to undefined)

const { status, data } = await apiInstance.verifyApiV1AuthVerifyGet(
    token
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **token** | [**string**] | Email verification token | defaults to undefined|


### Return type

**{ [key: string]: string | null; }**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | Successful Response |  -  |
|**422** | Validation Error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

