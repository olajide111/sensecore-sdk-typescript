# EmailTemplatesApi

All URIs are relative to *https://api.sensecoreai.com*

|Method | HTTP request | Description|
|------------- | ------------- | -------------|
|[**getTemplateApiV1AdminEmailTemplatesKeyGet**](#gettemplateapiv1adminemailtemplateskeyget) | **GET** /api/v1/admin/email-templates/{key} | Get Template|
|[**getTemplateApiV1AdminEmailTemplatesKeyGet_0**](#gettemplateapiv1adminemailtemplateskeyget_0) | **GET** /api/v1/admin/email-templates/{key} | Get Template|
|[**listTemplatesApiV1AdminEmailTemplatesGet**](#listtemplatesapiv1adminemailtemplatesget) | **GET** /api/v1/admin/email-templates | List Templates|
|[**listTemplatesApiV1AdminEmailTemplatesGet_0**](#listtemplatesapiv1adminemailtemplatesget_0) | **GET** /api/v1/admin/email-templates | List Templates|
|[**previewTemplateApiV1AdminEmailTemplatesKeyPreviewPost**](#previewtemplateapiv1adminemailtemplateskeypreviewpost) | **POST** /api/v1/admin/email-templates/{key}/preview | Preview Template|
|[**previewTemplateApiV1AdminEmailTemplatesKeyPreviewPost_0**](#previewtemplateapiv1adminemailtemplateskeypreviewpost_0) | **POST** /api/v1/admin/email-templates/{key}/preview | Preview Template|
|[**resetTemplateApiV1AdminEmailTemplatesKeyResetPost**](#resettemplateapiv1adminemailtemplateskeyresetpost) | **POST** /api/v1/admin/email-templates/{key}/reset | Reset Template|
|[**resetTemplateApiV1AdminEmailTemplatesKeyResetPost_0**](#resettemplateapiv1adminemailtemplateskeyresetpost_0) | **POST** /api/v1/admin/email-templates/{key}/reset | Reset Template|
|[**sendTestApiV1AdminEmailTemplatesKeySendTestPost**](#sendtestapiv1adminemailtemplateskeysendtestpost) | **POST** /api/v1/admin/email-templates/{key}/send-test | Send Test|
|[**sendTestApiV1AdminEmailTemplatesKeySendTestPost_0**](#sendtestapiv1adminemailtemplateskeysendtestpost_0) | **POST** /api/v1/admin/email-templates/{key}/send-test | Send Test|
|[**updateTemplateApiV1AdminEmailTemplatesKeyPut**](#updatetemplateapiv1adminemailtemplateskeyput) | **PUT** /api/v1/admin/email-templates/{key} | Update Template|
|[**updateTemplateApiV1AdminEmailTemplatesKeyPut_0**](#updatetemplateapiv1adminemailtemplateskeyput_0) | **PUT** /api/v1/admin/email-templates/{key} | Update Template|

# **getTemplateApiV1AdminEmailTemplatesKeyGet**
> any getTemplateApiV1AdminEmailTemplatesKeyGet()


### Example

```typescript
import {
    EmailTemplatesApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new EmailTemplatesApi(configuration);

let key: string; // (default to undefined)

const { status, data } = await apiInstance.getTemplateApiV1AdminEmailTemplatesKeyGet(
    key
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **key** | [**string**] |  | defaults to undefined|


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

# **getTemplateApiV1AdminEmailTemplatesKeyGet_0**
> any getTemplateApiV1AdminEmailTemplatesKeyGet_0()


### Example

```typescript
import {
    EmailTemplatesApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new EmailTemplatesApi(configuration);

let key: string; // (default to undefined)

const { status, data } = await apiInstance.getTemplateApiV1AdminEmailTemplatesKeyGet_0(
    key
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **key** | [**string**] |  | defaults to undefined|


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

# **listTemplatesApiV1AdminEmailTemplatesGet**
> any listTemplatesApiV1AdminEmailTemplatesGet()


### Example

```typescript
import {
    EmailTemplatesApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new EmailTemplatesApi(configuration);

const { status, data } = await apiInstance.listTemplatesApiV1AdminEmailTemplatesGet();
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

# **listTemplatesApiV1AdminEmailTemplatesGet_0**
> any listTemplatesApiV1AdminEmailTemplatesGet_0()


### Example

```typescript
import {
    EmailTemplatesApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new EmailTemplatesApi(configuration);

const { status, data } = await apiInstance.listTemplatesApiV1AdminEmailTemplatesGet_0();
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

# **previewTemplateApiV1AdminEmailTemplatesKeyPreviewPost**
> any previewTemplateApiV1AdminEmailTemplatesKeyPreviewPost()


### Example

```typescript
import {
    EmailTemplatesApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new EmailTemplatesApi(configuration);

let key: string; // (default to undefined)
let body: object; // (optional)

const { status, data } = await apiInstance.previewTemplateApiV1AdminEmailTemplatesKeyPreviewPost(
    key,
    body
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **body** | **object**|  | |
| **key** | [**string**] |  | defaults to undefined|


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

# **previewTemplateApiV1AdminEmailTemplatesKeyPreviewPost_0**
> any previewTemplateApiV1AdminEmailTemplatesKeyPreviewPost_0()


### Example

```typescript
import {
    EmailTemplatesApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new EmailTemplatesApi(configuration);

let key: string; // (default to undefined)
let body: object; // (optional)

const { status, data } = await apiInstance.previewTemplateApiV1AdminEmailTemplatesKeyPreviewPost_0(
    key,
    body
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **body** | **object**|  | |
| **key** | [**string**] |  | defaults to undefined|


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

# **resetTemplateApiV1AdminEmailTemplatesKeyResetPost**
> any resetTemplateApiV1AdminEmailTemplatesKeyResetPost()

For now, reset = re-run migration script for that template. User-friendly reset is to manually paste the default and save.

### Example

```typescript
import {
    EmailTemplatesApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new EmailTemplatesApi(configuration);

let key: string; // (default to undefined)

const { status, data } = await apiInstance.resetTemplateApiV1AdminEmailTemplatesKeyResetPost(
    key
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **key** | [**string**] |  | defaults to undefined|


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

# **resetTemplateApiV1AdminEmailTemplatesKeyResetPost_0**
> any resetTemplateApiV1AdminEmailTemplatesKeyResetPost_0()

For now, reset = re-run migration script for that template. User-friendly reset is to manually paste the default and save.

### Example

```typescript
import {
    EmailTemplatesApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new EmailTemplatesApi(configuration);

let key: string; // (default to undefined)

const { status, data } = await apiInstance.resetTemplateApiV1AdminEmailTemplatesKeyResetPost_0(
    key
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **key** | [**string**] |  | defaults to undefined|


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

# **sendTestApiV1AdminEmailTemplatesKeySendTestPost**
> any sendTestApiV1AdminEmailTemplatesKeySendTestPost(body)

Body: {   \"to_email\": \"your@email\",   \"provider_key\": \"sendgrid\"  // optional. Default: active provider. }

### Example

```typescript
import {
    EmailTemplatesApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new EmailTemplatesApi(configuration);

let key: string; // (default to undefined)
let body: object; //

const { status, data } = await apiInstance.sendTestApiV1AdminEmailTemplatesKeySendTestPost(
    key,
    body
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **body** | **object**|  | |
| **key** | [**string**] |  | defaults to undefined|


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

# **sendTestApiV1AdminEmailTemplatesKeySendTestPost_0**
> any sendTestApiV1AdminEmailTemplatesKeySendTestPost_0(body)

Body: {   \"to_email\": \"your@email\",   \"provider_key\": \"sendgrid\"  // optional. Default: active provider. }

### Example

```typescript
import {
    EmailTemplatesApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new EmailTemplatesApi(configuration);

let key: string; // (default to undefined)
let body: object; //

const { status, data } = await apiInstance.sendTestApiV1AdminEmailTemplatesKeySendTestPost_0(
    key,
    body
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **body** | **object**|  | |
| **key** | [**string**] |  | defaults to undefined|


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

# **updateTemplateApiV1AdminEmailTemplatesKeyPut**
> any updateTemplateApiV1AdminEmailTemplatesKeyPut(body)

Body: {   \"subject\", \"body_markdown\", \"button_label\", \"button_link\",   \"is_enabled\" (bool), \"note\" (optional) }

### Example

```typescript
import {
    EmailTemplatesApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new EmailTemplatesApi(configuration);

let key: string; // (default to undefined)
let body: object; //

const { status, data } = await apiInstance.updateTemplateApiV1AdminEmailTemplatesKeyPut(
    key,
    body
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **body** | **object**|  | |
| **key** | [**string**] |  | defaults to undefined|


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

# **updateTemplateApiV1AdminEmailTemplatesKeyPut_0**
> any updateTemplateApiV1AdminEmailTemplatesKeyPut_0(body)

Body: {   \"subject\", \"body_markdown\", \"button_label\", \"button_link\",   \"is_enabled\" (bool), \"note\" (optional) }

### Example

```typescript
import {
    EmailTemplatesApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new EmailTemplatesApi(configuration);

let key: string; // (default to undefined)
let body: object; //

const { status, data } = await apiInstance.updateTemplateApiV1AdminEmailTemplatesKeyPut_0(
    key,
    body
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **body** | **object**|  | |
| **key** | [**string**] |  | defaults to undefined|


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

