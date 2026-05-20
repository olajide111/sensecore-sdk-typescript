# CMSPageBuilderApi

All URIs are relative to *https://api.sensecoreai.com*

|Method | HTTP request | Description|
|------------- | ------------- | -------------|
|[**addSectionApiV1AdminCmsPagesBuilderPageSectionsPost**](#addsectionapiv1admincmspagesbuilderpagesectionspost) | **POST** /api/v1/admin/cms/pages-builder/{page}/sections | Add Section|
|[**addSectionApiV1AdminCmsPagesBuilderPageSectionsPost_0**](#addsectionapiv1admincmspagesbuilderpagesectionspost_0) | **POST** /api/v1/admin/cms/pages-builder/{page}/sections | Add Section|
|[**listSectionsApiV1AdminCmsPagesBuilderPageSectionsGet**](#listsectionsapiv1admincmspagesbuilderpagesectionsget) | **GET** /api/v1/admin/cms/pages-builder/{page}/sections | List Sections|
|[**listSectionsApiV1AdminCmsPagesBuilderPageSectionsGet_0**](#listsectionsapiv1admincmspagesbuilderpagesectionsget_0) | **GET** /api/v1/admin/cms/pages-builder/{page}/sections | List Sections|
|[**reorderSectionsApiV1AdminCmsPagesBuilderPageReorderPut**](#reordersectionsapiv1admincmspagesbuilderpagereorderput) | **PUT** /api/v1/admin/cms/pages-builder/{page}/reorder | Reorder Sections|
|[**reorderSectionsApiV1AdminCmsPagesBuilderPageReorderPut_0**](#reordersectionsapiv1admincmspagesbuilderpagereorderput_0) | **PUT** /api/v1/admin/cms/pages-builder/{page}/reorder | Reorder Sections|

# **addSectionApiV1AdminCmsPagesBuilderPageSectionsPost**
> any addSectionApiV1AdminCmsPagesBuilderPageSectionsPost(body)

Body:   {     \"section\":      \"hero_v2\",   (required, unique per page)     \"section_type\": \"hero\",      (required, picks the editor in admin)     \"content\":      {...},        (optional, default {})     \"title\":        \"Hero v2\",   (optional, friendly label)     \"is_published\": true,         (optional, default true)     \"sort_order\":   null          (optional, default = max+1)   }

### Example

```typescript
import {
    CMSPageBuilderApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new CMSPageBuilderApi(configuration);

let page: string; // (default to undefined)
let body: object; //

const { status, data } = await apiInstance.addSectionApiV1AdminCmsPagesBuilderPageSectionsPost(
    page,
    body
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **body** | **object**|  | |
| **page** | [**string**] |  | defaults to undefined|


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

# **addSectionApiV1AdminCmsPagesBuilderPageSectionsPost_0**
> any addSectionApiV1AdminCmsPagesBuilderPageSectionsPost_0(body)

Body:   {     \"section\":      \"hero_v2\",   (required, unique per page)     \"section_type\": \"hero\",      (required, picks the editor in admin)     \"content\":      {...},        (optional, default {})     \"title\":        \"Hero v2\",   (optional, friendly label)     \"is_published\": true,         (optional, default true)     \"sort_order\":   null          (optional, default = max+1)   }

### Example

```typescript
import {
    CMSPageBuilderApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new CMSPageBuilderApi(configuration);

let page: string; // (default to undefined)
let body: object; //

const { status, data } = await apiInstance.addSectionApiV1AdminCmsPagesBuilderPageSectionsPost_0(
    page,
    body
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **body** | **object**|  | |
| **page** | [**string**] |  | defaults to undefined|


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

# **listSectionsApiV1AdminCmsPagesBuilderPageSectionsGet**
> any listSectionsApiV1AdminCmsPagesBuilderPageSectionsGet()

Return all sections for a page, ordered by sort_order.

### Example

```typescript
import {
    CMSPageBuilderApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new CMSPageBuilderApi(configuration);

let page: string; // (default to undefined)

const { status, data } = await apiInstance.listSectionsApiV1AdminCmsPagesBuilderPageSectionsGet(
    page
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **page** | [**string**] |  | defaults to undefined|


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

# **listSectionsApiV1AdminCmsPagesBuilderPageSectionsGet_0**
> any listSectionsApiV1AdminCmsPagesBuilderPageSectionsGet_0()

Return all sections for a page, ordered by sort_order.

### Example

```typescript
import {
    CMSPageBuilderApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new CMSPageBuilderApi(configuration);

let page: string; // (default to undefined)

const { status, data } = await apiInstance.listSectionsApiV1AdminCmsPagesBuilderPageSectionsGet_0(
    page
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **page** | [**string**] |  | defaults to undefined|


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

# **reorderSectionsApiV1AdminCmsPagesBuilderPageReorderPut**
> any reorderSectionsApiV1AdminCmsPagesBuilderPageReorderPut(body)

Body: { \"order\": [\"hero\", \"stats\", \"cta\", ...] } Position in the array becomes the new sort_order (0-indexed). Sections not listed are left alone.

### Example

```typescript
import {
    CMSPageBuilderApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new CMSPageBuilderApi(configuration);

let page: string; // (default to undefined)
let body: object; //

const { status, data } = await apiInstance.reorderSectionsApiV1AdminCmsPagesBuilderPageReorderPut(
    page,
    body
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **body** | **object**|  | |
| **page** | [**string**] |  | defaults to undefined|


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

# **reorderSectionsApiV1AdminCmsPagesBuilderPageReorderPut_0**
> any reorderSectionsApiV1AdminCmsPagesBuilderPageReorderPut_0(body)

Body: { \"order\": [\"hero\", \"stats\", \"cta\", ...] } Position in the array becomes the new sort_order (0-indexed). Sections not listed are left alone.

### Example

```typescript
import {
    CMSPageBuilderApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new CMSPageBuilderApi(configuration);

let page: string; // (default to undefined)
let body: object; //

const { status, data } = await apiInstance.reorderSectionsApiV1AdminCmsPagesBuilderPageReorderPut_0(
    page,
    body
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **body** | **object**|  | |
| **page** | [**string**] |  | defaults to undefined|


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

