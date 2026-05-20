# EmailProvidersApi

All URIs are relative to *https://api.sensecoreai.com*

|Method | HTTP request | Description|
|------------- | ------------- | -------------|
|[**activateProviderApiV1AdminEmailProvidersKindActivatePost**](#activateproviderapiv1adminemailproviderskindactivatepost) | **POST** /api/v1/admin/email-providers/{kind}/activate | Activate Provider|
|[**activateProviderApiV1AdminEmailProvidersKindActivatePost_0**](#activateproviderapiv1adminemailproviderskindactivatepost_0) | **POST** /api/v1/admin/email-providers/{kind}/activate | Activate Provider|
|[**getProviderApiV1AdminEmailProvidersKindGet**](#getproviderapiv1adminemailproviderskindget) | **GET** /api/v1/admin/email-providers/{kind} | Get Provider|
|[**getProviderApiV1AdminEmailProvidersKindGet_0**](#getproviderapiv1adminemailproviderskindget_0) | **GET** /api/v1/admin/email-providers/{kind} | Get Provider|
|[**getRegistryApiV1AdminEmailProvidersTypesRegistryGet**](#getregistryapiv1adminemailproviderstypesregistryget) | **GET** /api/v1/admin/email-providers/types/registry | Get Registry|
|[**getRegistryApiV1AdminEmailProvidersTypesRegistryGet_0**](#getregistryapiv1adminemailproviderstypesregistryget_0) | **GET** /api/v1/admin/email-providers/types/registry | Get Registry|
|[**listProvidersApiV1AdminEmailProvidersGet**](#listprovidersapiv1adminemailprovidersget) | **GET** /api/v1/admin/email-providers | List Providers|
|[**listProvidersApiV1AdminEmailProvidersGet_0**](#listprovidersapiv1adminemailprovidersget_0) | **GET** /api/v1/admin/email-providers | List Providers|
|[**testProviderApiV1AdminEmailProvidersKindTestPost**](#testproviderapiv1adminemailproviderskindtestpost) | **POST** /api/v1/admin/email-providers/{kind}/test | Test Provider|
|[**testProviderApiV1AdminEmailProvidersKindTestPost_0**](#testproviderapiv1adminemailproviderskindtestpost_0) | **POST** /api/v1/admin/email-providers/{kind}/test | Test Provider|
|[**updateProviderApiV1AdminEmailProvidersKindPut**](#updateproviderapiv1adminemailproviderskindput) | **PUT** /api/v1/admin/email-providers/{kind} | Update Provider|
|[**updateProviderApiV1AdminEmailProvidersKindPut_0**](#updateproviderapiv1adminemailproviderskindput_0) | **PUT** /api/v1/admin/email-providers/{kind} | Update Provider|

# **activateProviderApiV1AdminEmailProvidersKindActivatePost**
> any activateProviderApiV1AdminEmailProvidersKindActivatePost()

Make this provider the active one. Deactivates all others atomically.

### Example

```typescript
import {
    EmailProvidersApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new EmailProvidersApi(configuration);

let kind: string; // (default to undefined)

const { status, data } = await apiInstance.activateProviderApiV1AdminEmailProvidersKindActivatePost(
    kind
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **kind** | [**string**] |  | defaults to undefined|


### Return type

**any**

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

# **activateProviderApiV1AdminEmailProvidersKindActivatePost_0**
> any activateProviderApiV1AdminEmailProvidersKindActivatePost_0()

Make this provider the active one. Deactivates all others atomically.

### Example

```typescript
import {
    EmailProvidersApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new EmailProvidersApi(configuration);

let kind: string; // (default to undefined)

const { status, data } = await apiInstance.activateProviderApiV1AdminEmailProvidersKindActivatePost_0(
    kind
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **kind** | [**string**] |  | defaults to undefined|


### Return type

**any**

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

# **getProviderApiV1AdminEmailProvidersKindGet**
> any getProviderApiV1AdminEmailProvidersKindGet()


### Example

```typescript
import {
    EmailProvidersApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new EmailProvidersApi(configuration);

let kind: string; // (default to undefined)
let redacted: boolean; // (optional) (default to false)

const { status, data } = await apiInstance.getProviderApiV1AdminEmailProvidersKindGet(
    kind,
    redacted
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **kind** | [**string**] |  | defaults to undefined|
| **redacted** | [**boolean**] |  | (optional) defaults to false|


### Return type

**any**

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

# **getProviderApiV1AdminEmailProvidersKindGet_0**
> any getProviderApiV1AdminEmailProvidersKindGet_0()


### Example

```typescript
import {
    EmailProvidersApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new EmailProvidersApi(configuration);

let kind: string; // (default to undefined)
let redacted: boolean; // (optional) (default to false)

const { status, data } = await apiInstance.getProviderApiV1AdminEmailProvidersKindGet_0(
    kind,
    redacted
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **kind** | [**string**] |  | defaults to undefined|
| **redacted** | [**boolean**] |  | (optional) defaults to false|


### Return type

**any**

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

# **getRegistryApiV1AdminEmailProvidersTypesRegistryGet**
> any getRegistryApiV1AdminEmailProvidersTypesRegistryGet()

Returns the provider type schemas. Used by the admin UI to render the correct config form for each provider type.

### Example

```typescript
import {
    EmailProvidersApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new EmailProvidersApi(configuration);

const { status, data } = await apiInstance.getRegistryApiV1AdminEmailProvidersTypesRegistryGet();
```

### Parameters
This endpoint does not have any parameters.


### Return type

**any**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | Successful Response |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getRegistryApiV1AdminEmailProvidersTypesRegistryGet_0**
> any getRegistryApiV1AdminEmailProvidersTypesRegistryGet_0()

Returns the provider type schemas. Used by the admin UI to render the correct config form for each provider type.

### Example

```typescript
import {
    EmailProvidersApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new EmailProvidersApi(configuration);

const { status, data } = await apiInstance.getRegistryApiV1AdminEmailProvidersTypesRegistryGet_0();
```

### Parameters
This endpoint does not have any parameters.


### Return type

**any**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | Successful Response |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **listProvidersApiV1AdminEmailProvidersGet**
> any listProvidersApiV1AdminEmailProvidersGet()


### Example

```typescript
import {
    EmailProvidersApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new EmailProvidersApi(configuration);

const { status, data } = await apiInstance.listProvidersApiV1AdminEmailProvidersGet();
```

### Parameters
This endpoint does not have any parameters.


### Return type

**any**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | Successful Response |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **listProvidersApiV1AdminEmailProvidersGet_0**
> any listProvidersApiV1AdminEmailProvidersGet_0()


### Example

```typescript
import {
    EmailProvidersApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new EmailProvidersApi(configuration);

const { status, data } = await apiInstance.listProvidersApiV1AdminEmailProvidersGet_0();
```

### Parameters
This endpoint does not have any parameters.


### Return type

**any**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | Successful Response |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **testProviderApiV1AdminEmailProvidersKindTestPost**
> any testProviderApiV1AdminEmailProvidersKindTestPost()

Test the provider\'s authentication / reachability without sending an actual email. Body is optional — pass `{\"config\": {...}}` to test UNSAVED config; otherwise tests the saved config.

### Example

```typescript
import {
    EmailProvidersApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new EmailProvidersApi(configuration);

let kind: string; // (default to undefined)
let body: object; // (optional)

const { status, data } = await apiInstance.testProviderApiV1AdminEmailProvidersKindTestPost(
    kind,
    body
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **body** | **object**|  | |
| **kind** | [**string**] |  | defaults to undefined|


### Return type

**any**

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

# **testProviderApiV1AdminEmailProvidersKindTestPost_0**
> any testProviderApiV1AdminEmailProvidersKindTestPost_0()

Test the provider\'s authentication / reachability without sending an actual email. Body is optional — pass `{\"config\": {...}}` to test UNSAVED config; otherwise tests the saved config.

### Example

```typescript
import {
    EmailProvidersApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new EmailProvidersApi(configuration);

let kind: string; // (default to undefined)
let body: object; // (optional)

const { status, data } = await apiInstance.testProviderApiV1AdminEmailProvidersKindTestPost_0(
    kind,
    body
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **body** | **object**|  | |
| **kind** | [**string**] |  | defaults to undefined|


### Return type

**any**

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

# **updateProviderApiV1AdminEmailProvidersKindPut**
> any updateProviderApiV1AdminEmailProvidersKindPut(body)

Body:   {     \"config\": { ... provider-specific ... },     \"notes\":  \"free text\",          # optional     \"name\":   \"Custom name\"          # optional, defaults preserved   }  Sensitive fields that come in masked (••••XXXX) keep their existing value.

### Example

```typescript
import {
    EmailProvidersApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new EmailProvidersApi(configuration);

let kind: string; // (default to undefined)
let body: object; //

const { status, data } = await apiInstance.updateProviderApiV1AdminEmailProvidersKindPut(
    kind,
    body
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **body** | **object**|  | |
| **kind** | [**string**] |  | defaults to undefined|


### Return type

**any**

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

# **updateProviderApiV1AdminEmailProvidersKindPut_0**
> any updateProviderApiV1AdminEmailProvidersKindPut_0(body)

Body:   {     \"config\": { ... provider-specific ... },     \"notes\":  \"free text\",          # optional     \"name\":   \"Custom name\"          # optional, defaults preserved   }  Sensitive fields that come in masked (••••XXXX) keep their existing value.

### Example

```typescript
import {
    EmailProvidersApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new EmailProvidersApi(configuration);

let kind: string; // (default to undefined)
let body: object; //

const { status, data } = await apiInstance.updateProviderApiV1AdminEmailProvidersKindPut_0(
    kind,
    body
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **body** | **object**|  | |
| **kind** | [**string**] |  | defaults to undefined|


### Return type

**any**

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

