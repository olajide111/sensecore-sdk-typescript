# CMSPageBuilderPublicApi

All URIs are relative to *https://api.sensecoreai.com*

|Method | HTTP request | Description|
|------------- | ------------- | -------------|
|[**publicListSectionsApiV1CmsPageSectionsPageGet**](#publiclistsectionsapiv1cmspagesectionspageget) | **GET** /api/v1/cms/page-sections/{page} | Public List Sections|
|[**publicListSectionsApiV1CmsPageSectionsPageGet_0**](#publiclistsectionsapiv1cmspagesectionspageget_0) | **GET** /api/v1/cms/page-sections/{page} | Public List Sections|

# **publicListSectionsApiV1CmsPageSectionsPageGet**
> any publicListSectionsApiV1CmsPageSectionsPageGet()

Public list of published sections for a page, ordered by sort_order.

### Example

```typescript
import {
    CMSPageBuilderPublicApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new CMSPageBuilderPublicApi(configuration);

let page: string; // (default to undefined)

const { status, data } = await apiInstance.publicListSectionsApiV1CmsPageSectionsPageGet(
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

# **publicListSectionsApiV1CmsPageSectionsPageGet_0**
> any publicListSectionsApiV1CmsPageSectionsPageGet_0()

Public list of published sections for a page, ordered by sort_order.

### Example

```typescript
import {
    CMSPageBuilderPublicApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new CMSPageBuilderPublicApi(configuration);

let page: string; // (default to undefined)

const { status, data } = await apiInstance.publicListSectionsApiV1CmsPageSectionsPageGet_0(
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

