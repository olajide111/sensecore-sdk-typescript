# CMSPublicApi

All URIs are relative to *https://api.sensecoreai.com*

|Method | HTTP request | Description|
|------------- | ------------- | -------------|
|[**publicAnnouncementApiV1CmsAnnouncementGet**](#publicannouncementapiv1cmsannouncementget) | **GET** /api/v1/cms/announcement | Public Announcement|
|[**publicAnnouncementApiV1CmsAnnouncementGet_0**](#publicannouncementapiv1cmsannouncementget_0) | **GET** /api/v1/cms/announcement | Public Announcement|
|[**publicAssetApiV1CmsAssetAidGet**](#publicassetapiv1cmsassetaidget) | **GET** /api/v1/cms/asset/{aid} | Public Asset|
|[**publicAssetApiV1CmsAssetAidGet_0**](#publicassetapiv1cmsassetaidget_0) | **GET** /api/v1/cms/asset/{aid} | Public Asset|
|[**publicBlogGetApiV1CmsBlogSlugGet**](#publicbloggetapiv1cmsblogslugget) | **GET** /api/v1/cms/blog/{slug} | Public Blog Get|
|[**publicBlogGetApiV1CmsBlogSlugGet_0**](#publicbloggetapiv1cmsblogslugget_0) | **GET** /api/v1/cms/blog/{slug} | Public Blog Get|
|[**publicBlogListApiV1CmsBlogGet**](#publicbloglistapiv1cmsblogget) | **GET** /api/v1/cms/blog | Public Blog List|
|[**publicBlogListApiV1CmsBlogGet_0**](#publicbloglistapiv1cmsblogget_0) | **GET** /api/v1/cms/blog | Public Blog List|
|[**publicBrandingApiV1CmsBrandingGet**](#publicbrandingapiv1cmsbrandingget) | **GET** /api/v1/cms/branding | Public Branding|
|[**publicBrandingApiV1CmsBrandingGet_0**](#publicbrandingapiv1cmsbrandingget_0) | **GET** /api/v1/cms/branding | Public Branding|
|[**publicChangelogApiV1CmsChangelogGet**](#publicchangelogapiv1cmschangelogget) | **GET** /api/v1/cms/changelog | Public Changelog|
|[**publicChangelogApiV1CmsChangelogGet_0**](#publicchangelogapiv1cmschangelogget_0) | **GET** /api/v1/cms/changelog | Public Changelog|
|[**publicGetPageApiV1CmsContentPageGet**](#publicgetpageapiv1cmscontentpageget) | **GET** /api/v1/cms/content/{page} | Public Get Page|
|[**publicGetPageApiV1CmsContentPageGet_0**](#publicgetpageapiv1cmscontentpageget_0) | **GET** /api/v1/cms/content/{page} | Public Get Page|

# **publicAnnouncementApiV1CmsAnnouncementGet**
> any publicAnnouncementApiV1CmsAnnouncementGet()

Public announcement banner.

### Example

```typescript
import {
    CMSPublicApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new CMSPublicApi(configuration);

const { status, data } = await apiInstance.publicAnnouncementApiV1CmsAnnouncementGet();
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

# **publicAnnouncementApiV1CmsAnnouncementGet_0**
> any publicAnnouncementApiV1CmsAnnouncementGet_0()

Public announcement banner.

### Example

```typescript
import {
    CMSPublicApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new CMSPublicApi(configuration);

const { status, data } = await apiInstance.publicAnnouncementApiV1CmsAnnouncementGet_0();
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

# **publicAssetApiV1CmsAssetAidGet**
> any publicAssetApiV1CmsAssetAidGet()

Stream asset binary.

### Example

```typescript
import {
    CMSPublicApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new CMSPublicApi(configuration);

let aid: string; // (default to undefined)

const { status, data } = await apiInstance.publicAssetApiV1CmsAssetAidGet(
    aid
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **aid** | [**string**] |  | defaults to undefined|


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

# **publicAssetApiV1CmsAssetAidGet_0**
> any publicAssetApiV1CmsAssetAidGet_0()

Stream asset binary.

### Example

```typescript
import {
    CMSPublicApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new CMSPublicApi(configuration);

let aid: string; // (default to undefined)

const { status, data } = await apiInstance.publicAssetApiV1CmsAssetAidGet_0(
    aid
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **aid** | [**string**] |  | defaults to undefined|


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

# **publicBlogGetApiV1CmsBlogSlugGet**
> any publicBlogGetApiV1CmsBlogSlugGet()


### Example

```typescript
import {
    CMSPublicApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new CMSPublicApi(configuration);

let slug: string; // (default to undefined)

const { status, data } = await apiInstance.publicBlogGetApiV1CmsBlogSlugGet(
    slug
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **slug** | [**string**] |  | defaults to undefined|


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

# **publicBlogGetApiV1CmsBlogSlugGet_0**
> any publicBlogGetApiV1CmsBlogSlugGet_0()


### Example

```typescript
import {
    CMSPublicApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new CMSPublicApi(configuration);

let slug: string; // (default to undefined)

const { status, data } = await apiInstance.publicBlogGetApiV1CmsBlogSlugGet_0(
    slug
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **slug** | [**string**] |  | defaults to undefined|


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

# **publicBlogListApiV1CmsBlogGet**
> any publicBlogListApiV1CmsBlogGet()

Public blog list.

### Example

```typescript
import {
    CMSPublicApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new CMSPublicApi(configuration);

const { status, data } = await apiInstance.publicBlogListApiV1CmsBlogGet();
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

# **publicBlogListApiV1CmsBlogGet_0**
> any publicBlogListApiV1CmsBlogGet_0()

Public blog list.

### Example

```typescript
import {
    CMSPublicApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new CMSPublicApi(configuration);

const { status, data } = await apiInstance.publicBlogListApiV1CmsBlogGet_0();
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

# **publicBrandingApiV1CmsBrandingGet**
> any publicBrandingApiV1CmsBrandingGet()

Public branding for marketing site.

### Example

```typescript
import {
    CMSPublicApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new CMSPublicApi(configuration);

const { status, data } = await apiInstance.publicBrandingApiV1CmsBrandingGet();
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

# **publicBrandingApiV1CmsBrandingGet_0**
> any publicBrandingApiV1CmsBrandingGet_0()

Public branding for marketing site.

### Example

```typescript
import {
    CMSPublicApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new CMSPublicApi(configuration);

const { status, data } = await apiInstance.publicBrandingApiV1CmsBrandingGet_0();
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

# **publicChangelogApiV1CmsChangelogGet**
> any publicChangelogApiV1CmsChangelogGet()


### Example

```typescript
import {
    CMSPublicApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new CMSPublicApi(configuration);

const { status, data } = await apiInstance.publicChangelogApiV1CmsChangelogGet();
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

# **publicChangelogApiV1CmsChangelogGet_0**
> any publicChangelogApiV1CmsChangelogGet_0()


### Example

```typescript
import {
    CMSPublicApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new CMSPublicApi(configuration);

const { status, data } = await apiInstance.publicChangelogApiV1CmsChangelogGet_0();
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

# **publicGetPageApiV1CmsContentPageGet**
> any publicGetPageApiV1CmsContentPageGet()

Public endpoint for marketing site to fetch published content.

### Example

```typescript
import {
    CMSPublicApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new CMSPublicApi(configuration);

let page: string; // (default to undefined)

const { status, data } = await apiInstance.publicGetPageApiV1CmsContentPageGet(
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

# **publicGetPageApiV1CmsContentPageGet_0**
> any publicGetPageApiV1CmsContentPageGet_0()

Public endpoint for marketing site to fetch published content.

### Example

```typescript
import {
    CMSPublicApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new CMSPublicApi(configuration);

let page: string; // (default to undefined)

const { status, data } = await apiInstance.publicGetPageApiV1CmsContentPageGet_0(
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

