# APIKeysApi

All URIs are relative to *https://api.sensecoreai.com*

|Method | HTTP request | Description|
|------------- | ------------- | -------------|
|[**createApiKeyApiV1ApiKeysPost**](#createapikeyapiv1apikeyspost) | **POST** /api/v1/api-keys | Create Api Key|
|[**listApiKeysApiV1ApiKeysGet**](#listapikeysapiv1apikeysget) | **GET** /api/v1/api-keys | List Api Keys|
|[**revokeApiKeyApiV1ApiKeysKeyIdDelete**](#revokeapikeyapiv1apikeyskeyiddelete) | **DELETE** /api/v1/api-keys/{key_id} | Revoke Api Key|
|[**rotateApiKeyApiV1ApiKeysKeyIdRotatePost**](#rotateapikeyapiv1apikeyskeyidrotatepost) | **POST** /api/v1/api-keys/{key_id}/rotate | Rotate Api Key|
|[**whoamiApiV1ApiKeysWhoamiGet**](#whoamiapiv1apikeyswhoamiget) | **GET** /api/v1/api-keys/whoami | Whoami|

# **createApiKeyApiV1ApiKeysPost**
> APIKeyCreatedResponse createApiKeyApiV1ApiKeysPost(createAPIKeyRequest)

Create a new API key. Plaintext returned ONCE in `full_key` — store it now.

### Example

```typescript
import {
    APIKeysApi,
    Configuration,
    CreateAPIKeyRequest
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new APIKeysApi(configuration);

let createAPIKeyRequest: CreateAPIKeyRequest; //

const { status, data } = await apiInstance.createApiKeyApiV1ApiKeysPost(
    createAPIKeyRequest
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **createAPIKeyRequest** | **CreateAPIKeyRequest**|  | |


### Return type

**APIKeyCreatedResponse**

### Authorization

[OAuth2PasswordBearer](../README.md#OAuth2PasswordBearer)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**201** | Successful Response |  -  |
|**422** | Validation Error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **listApiKeysApiV1ApiKeysGet**
> Array<APIKeyResponse> listApiKeysApiV1ApiKeysGet()

List API keys for the caller\'s org. Never returns plaintext or hashes.

### Example

```typescript
import {
    APIKeysApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new APIKeysApi(configuration);

let includeRevoked: boolean; // (optional) (default to false)

const { status, data } = await apiInstance.listApiKeysApiV1ApiKeysGet(
    includeRevoked
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **includeRevoked** | [**boolean**] |  | (optional) defaults to false|


### Return type

**Array<APIKeyResponse>**

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

# **revokeApiKeyApiV1ApiKeysKeyIdDelete**
> revokeApiKeyApiV1ApiKeysKeyIdDelete()

Revoke a key. Soft-delete — revoked_at set, row preserved for audit.

### Example

```typescript
import {
    APIKeysApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new APIKeysApi(configuration);

let keyId: string; // (default to undefined)

const { status, data } = await apiInstance.revokeApiKeyApiV1ApiKeysKeyIdDelete(
    keyId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **keyId** | [**string**] |  | defaults to undefined|


### Return type

void (empty response body)

### Authorization

[OAuth2PasswordBearer](../README.md#OAuth2PasswordBearer)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**204** | Successful Response |  -  |
|**422** | Validation Error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **rotateApiKeyApiV1ApiKeysKeyIdRotatePost**
> APIKeyCreatedResponse rotateApiKeyApiV1ApiKeysKeyIdRotatePost()

Atomic revoke + reissue. Old key invalidated immediately, name preserved. New plaintext returned ONCE — store it now.

### Example

```typescript
import {
    APIKeysApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new APIKeysApi(configuration);

let keyId: string; // (default to undefined)

const { status, data } = await apiInstance.rotateApiKeyApiV1ApiKeysKeyIdRotatePost(
    keyId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **keyId** | [**string**] |  | defaults to undefined|


### Return type

**APIKeyCreatedResponse**

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

# **whoamiApiV1ApiKeysWhoamiGet**
> object whoamiApiV1ApiKeysWhoamiGet()

Return how the system sees the current caller.  Accepts JWT (Authorization: Bearer) OR X-API-Key. Useful for confirming a key works without making a real data-plane call, and for debugging auth flows. Unlike the other routes in this module, this endpoint deliberately uses the hybrid dep — so an API-key holder can verify their own key by hitting /whoami before relying on it elsewhere.

### Example

```typescript
import {
    APIKeysApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new APIKeysApi(configuration);

let xAPIKey: string; // (optional) (default to undefined)

const { status, data } = await apiInstance.whoamiApiV1ApiKeysWhoamiGet(
    xAPIKey
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **xAPIKey** | [**string**] |  | (optional) defaults to undefined|


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
|**422** | Validation Error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

