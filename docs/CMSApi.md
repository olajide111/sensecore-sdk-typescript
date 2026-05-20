# CMSApi

All URIs are relative to *https://api.sensecoreai.com*

|Method | HTTP request | Description|
|------------- | ------------- | -------------|
|[**createBlogApiV1AdminCmsBlogPost**](#createblogapiv1admincmsblogpost) | **POST** /api/v1/admin/cms/blog | Create Blog|
|[**createBlogApiV1AdminCmsBlogPost_0**](#createblogapiv1admincmsblogpost_0) | **POST** /api/v1/admin/cms/blog | Create Blog|
|[**createChangelogApiV1AdminCmsChangelogPost**](#createchangelogapiv1admincmschangelogpost) | **POST** /api/v1/admin/cms/changelog | Create Changelog|
|[**createChangelogApiV1AdminCmsChangelogPost_0**](#createchangelogapiv1admincmschangelogpost_0) | **POST** /api/v1/admin/cms/changelog | Create Changelog|
|[**createPageApiV1AdminCmsPagesPost**](#createpageapiv1admincmspagespost) | **POST** /api/v1/admin/cms/pages | Create Page|
|[**createPageApiV1AdminCmsPagesPost_0**](#createpageapiv1admincmspagespost_0) | **POST** /api/v1/admin/cms/pages | Create Page|
|[**deleteAssetApiV1AdminCmsAssetsAidDelete**](#deleteassetapiv1admincmsassetsaiddelete) | **DELETE** /api/v1/admin/cms/assets/{aid} | Delete Asset|
|[**deleteAssetApiV1AdminCmsAssetsAidDelete_0**](#deleteassetapiv1admincmsassetsaiddelete_0) | **DELETE** /api/v1/admin/cms/assets/{aid} | Delete Asset|
|[**deleteBlogApiV1AdminCmsBlogSlugDelete**](#deleteblogapiv1admincmsblogslugdelete) | **DELETE** /api/v1/admin/cms/blog/{slug} | Delete Blog|
|[**deleteBlogApiV1AdminCmsBlogSlugDelete_0**](#deleteblogapiv1admincmsblogslugdelete_0) | **DELETE** /api/v1/admin/cms/blog/{slug} | Delete Blog|
|[**deleteChangelogApiV1AdminCmsChangelogCidDelete**](#deletechangelogapiv1admincmschangelogciddelete) | **DELETE** /api/v1/admin/cms/changelog/{cid} | Delete Changelog|
|[**deleteChangelogApiV1AdminCmsChangelogCidDelete_0**](#deletechangelogapiv1admincmschangelogciddelete_0) | **DELETE** /api/v1/admin/cms/changelog/{cid} | Delete Changelog|
|[**deleteContentApiV1AdminCmsContentPageSectionDelete**](#deletecontentapiv1admincmscontentpagesectiondelete) | **DELETE** /api/v1/admin/cms/content/{page}/{section} | Delete Content|
|[**deleteContentApiV1AdminCmsContentPageSectionDelete_0**](#deletecontentapiv1admincmscontentpagesectiondelete_0) | **DELETE** /api/v1/admin/cms/content/{page}/{section} | Delete Content|
|[**deletePageApiV1AdminCmsPagesSlugDelete**](#deletepageapiv1admincmspagesslugdelete) | **DELETE** /api/v1/admin/cms/pages/{slug} | Delete Page|
|[**deletePageApiV1AdminCmsPagesSlugDelete_0**](#deletepageapiv1admincmspagesslugdelete_0) | **DELETE** /api/v1/admin/cms/pages/{slug} | Delete Page|
|[**getBlogApiV1AdminCmsBlogSlugGet**](#getblogapiv1admincmsblogslugget) | **GET** /api/v1/admin/cms/blog/{slug} | Get Blog|
|[**getBlogApiV1AdminCmsBlogSlugGet_0**](#getblogapiv1admincmsblogslugget_0) | **GET** /api/v1/admin/cms/blog/{slug} | Get Blog|
|[**getContentApiV1AdminCmsContentPageSectionGet**](#getcontentapiv1admincmscontentpagesectionget) | **GET** /api/v1/admin/cms/content/{page}/{section} | Get Content|
|[**getContentApiV1AdminCmsContentPageSectionGet_0**](#getcontentapiv1admincmscontentpagesectionget_0) | **GET** /api/v1/admin/cms/content/{page}/{section} | Get Content|
|[**listAssetsApiV1AdminCmsAssetsGet**](#listassetsapiv1admincmsassetsget) | **GET** /api/v1/admin/cms/assets | List Assets|
|[**listAssetsApiV1AdminCmsAssetsGet_0**](#listassetsapiv1admincmsassetsget_0) | **GET** /api/v1/admin/cms/assets | List Assets|
|[**listBlogApiV1AdminCmsBlogGet**](#listblogapiv1admincmsblogget) | **GET** /api/v1/admin/cms/blog | List Blog|
|[**listBlogApiV1AdminCmsBlogGet_0**](#listblogapiv1admincmsblogget_0) | **GET** /api/v1/admin/cms/blog | List Blog|
|[**listChangelogApiV1AdminCmsChangelogGet**](#listchangelogapiv1admincmschangelogget) | **GET** /api/v1/admin/cms/changelog | List Changelog|
|[**listChangelogApiV1AdminCmsChangelogGet_0**](#listchangelogapiv1admincmschangelogget_0) | **GET** /api/v1/admin/cms/changelog | List Changelog|
|[**listContentApiV1AdminCmsContentGet**](#listcontentapiv1admincmscontentget) | **GET** /api/v1/admin/cms/content | List Content|
|[**listContentApiV1AdminCmsContentGet_0**](#listcontentapiv1admincmscontentget_0) | **GET** /api/v1/admin/cms/content | List Content|
|[**listPagesApiV1AdminCmsPagesGet**](#listpagesapiv1admincmspagesget) | **GET** /api/v1/admin/cms/pages | List Pages|
|[**listPagesApiV1AdminCmsPagesGet_0**](#listpagesapiv1admincmspagesget_0) | **GET** /api/v1/admin/cms/pages | List Pages|
|[**listTogglesApiV1AdminCmsFeatureTogglesGet**](#listtogglesapiv1admincmsfeaturetogglesget) | **GET** /api/v1/admin/cms/feature-toggles | List Toggles|
|[**listTogglesApiV1AdminCmsFeatureTogglesGet_0**](#listtogglesapiv1admincmsfeaturetogglesget_0) | **GET** /api/v1/admin/cms/feature-toggles | List Toggles|
|[**listVersionsApiV1AdminCmsContentPageSectionVersionsGet**](#listversionsapiv1admincmscontentpagesectionversionsget) | **GET** /api/v1/admin/cms/content/{page}/{section}/versions | List Versions|
|[**listVersionsApiV1AdminCmsContentPageSectionVersionsGet_0**](#listversionsapiv1admincmscontentpagesectionversionsget_0) | **GET** /api/v1/admin/cms/content/{page}/{section}/versions | List Versions|
|[**rollbackContentApiV1AdminCmsContentPageSectionRollbackVersionPost**](#rollbackcontentapiv1admincmscontentpagesectionrollbackversionpost) | **POST** /api/v1/admin/cms/content/{page}/{section}/rollback/{version} | Rollback Content|
|[**rollbackContentApiV1AdminCmsContentPageSectionRollbackVersionPost_0**](#rollbackcontentapiv1admincmscontentpagesectionrollbackversionpost_0) | **POST** /api/v1/admin/cms/content/{page}/{section}/rollback/{version} | Rollback Content|
|[**updateBlogApiV1AdminCmsBlogSlugPatch**](#updateblogapiv1admincmsblogslugpatch) | **PATCH** /api/v1/admin/cms/blog/{slug} | Update Blog|
|[**updateBlogApiV1AdminCmsBlogSlugPatch_0**](#updateblogapiv1admincmsblogslugpatch_0) | **PATCH** /api/v1/admin/cms/blog/{slug} | Update Blog|
|[**updateContentApiV1AdminCmsContentPageSectionPut**](#updatecontentapiv1admincmscontentpagesectionput) | **PUT** /api/v1/admin/cms/content/{page}/{section} | Update Content|
|[**updateContentApiV1AdminCmsContentPageSectionPut_0**](#updatecontentapiv1admincmscontentpagesectionput_0) | **PUT** /api/v1/admin/cms/content/{page}/{section} | Update Content|
|[**updatePageApiV1AdminCmsPagesSlugPatch**](#updatepageapiv1admincmspagesslugpatch) | **PATCH** /api/v1/admin/cms/pages/{slug} | Update Page|
|[**updatePageApiV1AdminCmsPagesSlugPatch_0**](#updatepageapiv1admincmspagesslugpatch_0) | **PATCH** /api/v1/admin/cms/pages/{slug} | Update Page|
|[**uploadAssetApiV1AdminCmsAssetsPost**](#uploadassetapiv1admincmsassetspost) | **POST** /api/v1/admin/cms/assets | Upload Asset|
|[**uploadAssetApiV1AdminCmsAssetsPost_0**](#uploadassetapiv1admincmsassetspost_0) | **POST** /api/v1/admin/cms/assets | Upload Asset|
|[**upsertToggleApiV1AdminCmsFeatureTogglesPut**](#upserttoggleapiv1admincmsfeaturetogglesput) | **PUT** /api/v1/admin/cms/feature-toggles | Upsert Toggle|
|[**upsertToggleApiV1AdminCmsFeatureTogglesPut_0**](#upserttoggleapiv1admincmsfeaturetogglesput_0) | **PUT** /api/v1/admin/cms/feature-toggles | Upsert Toggle|

# **createBlogApiV1AdminCmsBlogPost**
> any createBlogApiV1AdminCmsBlogPost(body)


### Example

```typescript
import {
    CMSApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new CMSApi(configuration);

let body: object; //

const { status, data } = await apiInstance.createBlogApiV1AdminCmsBlogPost(
    body
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **body** | **object**|  | |


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

# **createBlogApiV1AdminCmsBlogPost_0**
> any createBlogApiV1AdminCmsBlogPost_0(body)


### Example

```typescript
import {
    CMSApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new CMSApi(configuration);

let body: object; //

const { status, data } = await apiInstance.createBlogApiV1AdminCmsBlogPost_0(
    body
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **body** | **object**|  | |


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

# **createChangelogApiV1AdminCmsChangelogPost**
> any createChangelogApiV1AdminCmsChangelogPost(body)


### Example

```typescript
import {
    CMSApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new CMSApi(configuration);

let body: object; //

const { status, data } = await apiInstance.createChangelogApiV1AdminCmsChangelogPost(
    body
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **body** | **object**|  | |


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

# **createChangelogApiV1AdminCmsChangelogPost_0**
> any createChangelogApiV1AdminCmsChangelogPost_0(body)


### Example

```typescript
import {
    CMSApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new CMSApi(configuration);

let body: object; //

const { status, data } = await apiInstance.createChangelogApiV1AdminCmsChangelogPost_0(
    body
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **body** | **object**|  | |


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

# **createPageApiV1AdminCmsPagesPost**
> any createPageApiV1AdminCmsPagesPost(body)


### Example

```typescript
import {
    CMSApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new CMSApi(configuration);

let body: object; //

const { status, data } = await apiInstance.createPageApiV1AdminCmsPagesPost(
    body
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **body** | **object**|  | |


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

# **createPageApiV1AdminCmsPagesPost_0**
> any createPageApiV1AdminCmsPagesPost_0(body)


### Example

```typescript
import {
    CMSApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new CMSApi(configuration);

let body: object; //

const { status, data } = await apiInstance.createPageApiV1AdminCmsPagesPost_0(
    body
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **body** | **object**|  | |


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

# **deleteAssetApiV1AdminCmsAssetsAidDelete**
> any deleteAssetApiV1AdminCmsAssetsAidDelete()


### Example

```typescript
import {
    CMSApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new CMSApi(configuration);

let aid: string; // (default to undefined)

const { status, data } = await apiInstance.deleteAssetApiV1AdminCmsAssetsAidDelete(
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

# **deleteAssetApiV1AdminCmsAssetsAidDelete_0**
> any deleteAssetApiV1AdminCmsAssetsAidDelete_0()


### Example

```typescript
import {
    CMSApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new CMSApi(configuration);

let aid: string; // (default to undefined)

const { status, data } = await apiInstance.deleteAssetApiV1AdminCmsAssetsAidDelete_0(
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

# **deleteBlogApiV1AdminCmsBlogSlugDelete**
> any deleteBlogApiV1AdminCmsBlogSlugDelete()


### Example

```typescript
import {
    CMSApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new CMSApi(configuration);

let slug: string; // (default to undefined)

const { status, data } = await apiInstance.deleteBlogApiV1AdminCmsBlogSlugDelete(
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

# **deleteBlogApiV1AdminCmsBlogSlugDelete_0**
> any deleteBlogApiV1AdminCmsBlogSlugDelete_0()


### Example

```typescript
import {
    CMSApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new CMSApi(configuration);

let slug: string; // (default to undefined)

const { status, data } = await apiInstance.deleteBlogApiV1AdminCmsBlogSlugDelete_0(
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

# **deleteChangelogApiV1AdminCmsChangelogCidDelete**
> any deleteChangelogApiV1AdminCmsChangelogCidDelete()


### Example

```typescript
import {
    CMSApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new CMSApi(configuration);

let cid: number; // (default to undefined)

const { status, data } = await apiInstance.deleteChangelogApiV1AdminCmsChangelogCidDelete(
    cid
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **cid** | [**number**] |  | defaults to undefined|


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

# **deleteChangelogApiV1AdminCmsChangelogCidDelete_0**
> any deleteChangelogApiV1AdminCmsChangelogCidDelete_0()


### Example

```typescript
import {
    CMSApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new CMSApi(configuration);

let cid: number; // (default to undefined)

const { status, data } = await apiInstance.deleteChangelogApiV1AdminCmsChangelogCidDelete_0(
    cid
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **cid** | [**number**] |  | defaults to undefined|


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

# **deleteContentApiV1AdminCmsContentPageSectionDelete**
> any deleteContentApiV1AdminCmsContentPageSectionDelete()


### Example

```typescript
import {
    CMSApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new CMSApi(configuration);

let page: string; // (default to undefined)
let section: string; // (default to undefined)

const { status, data } = await apiInstance.deleteContentApiV1AdminCmsContentPageSectionDelete(
    page,
    section
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **page** | [**string**] |  | defaults to undefined|
| **section** | [**string**] |  | defaults to undefined|


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

# **deleteContentApiV1AdminCmsContentPageSectionDelete_0**
> any deleteContentApiV1AdminCmsContentPageSectionDelete_0()


### Example

```typescript
import {
    CMSApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new CMSApi(configuration);

let page: string; // (default to undefined)
let section: string; // (default to undefined)

const { status, data } = await apiInstance.deleteContentApiV1AdminCmsContentPageSectionDelete_0(
    page,
    section
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **page** | [**string**] |  | defaults to undefined|
| **section** | [**string**] |  | defaults to undefined|


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

# **deletePageApiV1AdminCmsPagesSlugDelete**
> any deletePageApiV1AdminCmsPagesSlugDelete()


### Example

```typescript
import {
    CMSApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new CMSApi(configuration);

let slug: string; // (default to undefined)

const { status, data } = await apiInstance.deletePageApiV1AdminCmsPagesSlugDelete(
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

# **deletePageApiV1AdminCmsPagesSlugDelete_0**
> any deletePageApiV1AdminCmsPagesSlugDelete_0()


### Example

```typescript
import {
    CMSApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new CMSApi(configuration);

let slug: string; // (default to undefined)

const { status, data } = await apiInstance.deletePageApiV1AdminCmsPagesSlugDelete_0(
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

# **getBlogApiV1AdminCmsBlogSlugGet**
> any getBlogApiV1AdminCmsBlogSlugGet()


### Example

```typescript
import {
    CMSApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new CMSApi(configuration);

let slug: string; // (default to undefined)

const { status, data } = await apiInstance.getBlogApiV1AdminCmsBlogSlugGet(
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

# **getBlogApiV1AdminCmsBlogSlugGet_0**
> any getBlogApiV1AdminCmsBlogSlugGet_0()


### Example

```typescript
import {
    CMSApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new CMSApi(configuration);

let slug: string; // (default to undefined)

const { status, data } = await apiInstance.getBlogApiV1AdminCmsBlogSlugGet_0(
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

# **getContentApiV1AdminCmsContentPageSectionGet**
> any getContentApiV1AdminCmsContentPageSectionGet()


### Example

```typescript
import {
    CMSApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new CMSApi(configuration);

let page: string; // (default to undefined)
let section: string; // (default to undefined)

const { status, data } = await apiInstance.getContentApiV1AdminCmsContentPageSectionGet(
    page,
    section
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **page** | [**string**] |  | defaults to undefined|
| **section** | [**string**] |  | defaults to undefined|


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

# **getContentApiV1AdminCmsContentPageSectionGet_0**
> any getContentApiV1AdminCmsContentPageSectionGet_0()


### Example

```typescript
import {
    CMSApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new CMSApi(configuration);

let page: string; // (default to undefined)
let section: string; // (default to undefined)

const { status, data } = await apiInstance.getContentApiV1AdminCmsContentPageSectionGet_0(
    page,
    section
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **page** | [**string**] |  | defaults to undefined|
| **section** | [**string**] |  | defaults to undefined|


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

# **listAssetsApiV1AdminCmsAssetsGet**
> any listAssetsApiV1AdminCmsAssetsGet()


### Example

```typescript
import {
    CMSApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new CMSApi(configuration);

const { status, data } = await apiInstance.listAssetsApiV1AdminCmsAssetsGet();
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

# **listAssetsApiV1AdminCmsAssetsGet_0**
> any listAssetsApiV1AdminCmsAssetsGet_0()


### Example

```typescript
import {
    CMSApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new CMSApi(configuration);

const { status, data } = await apiInstance.listAssetsApiV1AdminCmsAssetsGet_0();
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

# **listBlogApiV1AdminCmsBlogGet**
> any listBlogApiV1AdminCmsBlogGet()


### Example

```typescript
import {
    CMSApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new CMSApi(configuration);

const { status, data } = await apiInstance.listBlogApiV1AdminCmsBlogGet();
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

# **listBlogApiV1AdminCmsBlogGet_0**
> any listBlogApiV1AdminCmsBlogGet_0()


### Example

```typescript
import {
    CMSApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new CMSApi(configuration);

const { status, data } = await apiInstance.listBlogApiV1AdminCmsBlogGet_0();
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

# **listChangelogApiV1AdminCmsChangelogGet**
> any listChangelogApiV1AdminCmsChangelogGet()


### Example

```typescript
import {
    CMSApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new CMSApi(configuration);

const { status, data } = await apiInstance.listChangelogApiV1AdminCmsChangelogGet();
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

# **listChangelogApiV1AdminCmsChangelogGet_0**
> any listChangelogApiV1AdminCmsChangelogGet_0()


### Example

```typescript
import {
    CMSApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new CMSApi(configuration);

const { status, data } = await apiInstance.listChangelogApiV1AdminCmsChangelogGet_0();
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

# **listContentApiV1AdminCmsContentGet**
> any listContentApiV1AdminCmsContentGet()

List all content sections, optionally filtered by page.

### Example

```typescript
import {
    CMSApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new CMSApi(configuration);

let page: string; // (optional) (default to undefined)

const { status, data } = await apiInstance.listContentApiV1AdminCmsContentGet(
    page
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **page** | [**string**] |  | (optional) defaults to undefined|


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

# **listContentApiV1AdminCmsContentGet_0**
> any listContentApiV1AdminCmsContentGet_0()

List all content sections, optionally filtered by page.

### Example

```typescript
import {
    CMSApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new CMSApi(configuration);

let page: string; // (optional) (default to undefined)

const { status, data } = await apiInstance.listContentApiV1AdminCmsContentGet_0(
    page
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **page** | [**string**] |  | (optional) defaults to undefined|


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

# **listPagesApiV1AdminCmsPagesGet**
> any listPagesApiV1AdminCmsPagesGet()


### Example

```typescript
import {
    CMSApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new CMSApi(configuration);

const { status, data } = await apiInstance.listPagesApiV1AdminCmsPagesGet();
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

# **listPagesApiV1AdminCmsPagesGet_0**
> any listPagesApiV1AdminCmsPagesGet_0()


### Example

```typescript
import {
    CMSApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new CMSApi(configuration);

const { status, data } = await apiInstance.listPagesApiV1AdminCmsPagesGet_0();
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

# **listTogglesApiV1AdminCmsFeatureTogglesGet**
> any listTogglesApiV1AdminCmsFeatureTogglesGet()


### Example

```typescript
import {
    CMSApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new CMSApi(configuration);

const { status, data } = await apiInstance.listTogglesApiV1AdminCmsFeatureTogglesGet();
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

# **listTogglesApiV1AdminCmsFeatureTogglesGet_0**
> any listTogglesApiV1AdminCmsFeatureTogglesGet_0()


### Example

```typescript
import {
    CMSApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new CMSApi(configuration);

const { status, data } = await apiInstance.listTogglesApiV1AdminCmsFeatureTogglesGet_0();
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

# **listVersionsApiV1AdminCmsContentPageSectionVersionsGet**
> any listVersionsApiV1AdminCmsContentPageSectionVersionsGet()

Get version history for a content section.

### Example

```typescript
import {
    CMSApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new CMSApi(configuration);

let page: string; // (default to undefined)
let section: string; // (default to undefined)

const { status, data } = await apiInstance.listVersionsApiV1AdminCmsContentPageSectionVersionsGet(
    page,
    section
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **page** | [**string**] |  | defaults to undefined|
| **section** | [**string**] |  | defaults to undefined|


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

# **listVersionsApiV1AdminCmsContentPageSectionVersionsGet_0**
> any listVersionsApiV1AdminCmsContentPageSectionVersionsGet_0()

Get version history for a content section.

### Example

```typescript
import {
    CMSApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new CMSApi(configuration);

let page: string; // (default to undefined)
let section: string; // (default to undefined)

const { status, data } = await apiInstance.listVersionsApiV1AdminCmsContentPageSectionVersionsGet_0(
    page,
    section
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **page** | [**string**] |  | defaults to undefined|
| **section** | [**string**] |  | defaults to undefined|


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

# **rollbackContentApiV1AdminCmsContentPageSectionRollbackVersionPost**
> any rollbackContentApiV1AdminCmsContentPageSectionRollbackVersionPost()

Rollback to a specific version.

### Example

```typescript
import {
    CMSApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new CMSApi(configuration);

let page: string; // (default to undefined)
let section: string; // (default to undefined)
let version: number; // (default to undefined)

const { status, data } = await apiInstance.rollbackContentApiV1AdminCmsContentPageSectionRollbackVersionPost(
    page,
    section,
    version
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **page** | [**string**] |  | defaults to undefined|
| **section** | [**string**] |  | defaults to undefined|
| **version** | [**number**] |  | defaults to undefined|


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

# **rollbackContentApiV1AdminCmsContentPageSectionRollbackVersionPost_0**
> any rollbackContentApiV1AdminCmsContentPageSectionRollbackVersionPost_0()

Rollback to a specific version.

### Example

```typescript
import {
    CMSApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new CMSApi(configuration);

let page: string; // (default to undefined)
let section: string; // (default to undefined)
let version: number; // (default to undefined)

const { status, data } = await apiInstance.rollbackContentApiV1AdminCmsContentPageSectionRollbackVersionPost_0(
    page,
    section,
    version
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **page** | [**string**] |  | defaults to undefined|
| **section** | [**string**] |  | defaults to undefined|
| **version** | [**number**] |  | defaults to undefined|


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

# **updateBlogApiV1AdminCmsBlogSlugPatch**
> any updateBlogApiV1AdminCmsBlogSlugPatch(body)


### Example

```typescript
import {
    CMSApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new CMSApi(configuration);

let slug: string; // (default to undefined)
let body: object; //

const { status, data } = await apiInstance.updateBlogApiV1AdminCmsBlogSlugPatch(
    slug,
    body
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **body** | **object**|  | |
| **slug** | [**string**] |  | defaults to undefined|


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

# **updateBlogApiV1AdminCmsBlogSlugPatch_0**
> any updateBlogApiV1AdminCmsBlogSlugPatch_0(body)


### Example

```typescript
import {
    CMSApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new CMSApi(configuration);

let slug: string; // (default to undefined)
let body: object; //

const { status, data } = await apiInstance.updateBlogApiV1AdminCmsBlogSlugPatch_0(
    slug,
    body
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **body** | **object**|  | |
| **slug** | [**string**] |  | defaults to undefined|


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

# **updateContentApiV1AdminCmsContentPageSectionPut**
> any updateContentApiV1AdminCmsContentPageSectionPut(body)

Update content. Saves previous version to history.

### Example

```typescript
import {
    CMSApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new CMSApi(configuration);

let page: string; // (default to undefined)
let section: string; // (default to undefined)
let body: object; //

const { status, data } = await apiInstance.updateContentApiV1AdminCmsContentPageSectionPut(
    page,
    section,
    body
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **body** | **object**|  | |
| **page** | [**string**] |  | defaults to undefined|
| **section** | [**string**] |  | defaults to undefined|


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

# **updateContentApiV1AdminCmsContentPageSectionPut_0**
> any updateContentApiV1AdminCmsContentPageSectionPut_0(body)

Update content. Saves previous version to history.

### Example

```typescript
import {
    CMSApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new CMSApi(configuration);

let page: string; // (default to undefined)
let section: string; // (default to undefined)
let body: object; //

const { status, data } = await apiInstance.updateContentApiV1AdminCmsContentPageSectionPut_0(
    page,
    section,
    body
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **body** | **object**|  | |
| **page** | [**string**] |  | defaults to undefined|
| **section** | [**string**] |  | defaults to undefined|


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

# **updatePageApiV1AdminCmsPagesSlugPatch**
> any updatePageApiV1AdminCmsPagesSlugPatch(body)


### Example

```typescript
import {
    CMSApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new CMSApi(configuration);

let slug: string; // (default to undefined)
let body: object; //

const { status, data } = await apiInstance.updatePageApiV1AdminCmsPagesSlugPatch(
    slug,
    body
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **body** | **object**|  | |
| **slug** | [**string**] |  | defaults to undefined|


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

# **updatePageApiV1AdminCmsPagesSlugPatch_0**
> any updatePageApiV1AdminCmsPagesSlugPatch_0(body)


### Example

```typescript
import {
    CMSApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new CMSApi(configuration);

let slug: string; // (default to undefined)
let body: object; //

const { status, data } = await apiInstance.updatePageApiV1AdminCmsPagesSlugPatch_0(
    slug,
    body
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **body** | **object**|  | |
| **slug** | [**string**] |  | defaults to undefined|


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

# **uploadAssetApiV1AdminCmsAssetsPost**
> any uploadAssetApiV1AdminCmsAssetsPost(body)

Upload base64 asset. Returns a URL path.

### Example

```typescript
import {
    CMSApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new CMSApi(configuration);

let body: object; //

const { status, data } = await apiInstance.uploadAssetApiV1AdminCmsAssetsPost(
    body
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **body** | **object**|  | |


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

# **uploadAssetApiV1AdminCmsAssetsPost_0**
> any uploadAssetApiV1AdminCmsAssetsPost_0(body)

Upload base64 asset. Returns a URL path.

### Example

```typescript
import {
    CMSApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new CMSApi(configuration);

let body: object; //

const { status, data } = await apiInstance.uploadAssetApiV1AdminCmsAssetsPost_0(
    body
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **body** | **object**|  | |


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

# **upsertToggleApiV1AdminCmsFeatureTogglesPut**
> any upsertToggleApiV1AdminCmsFeatureTogglesPut(body)


### Example

```typescript
import {
    CMSApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new CMSApi(configuration);

let body: object; //

const { status, data } = await apiInstance.upsertToggleApiV1AdminCmsFeatureTogglesPut(
    body
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **body** | **object**|  | |


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

# **upsertToggleApiV1AdminCmsFeatureTogglesPut_0**
> any upsertToggleApiV1AdminCmsFeatureTogglesPut_0(body)


### Example

```typescript
import {
    CMSApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new CMSApi(configuration);

let body: object; //

const { status, data } = await apiInstance.upsertToggleApiV1AdminCmsFeatureTogglesPut_0(
    body
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **body** | **object**|  | |


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

