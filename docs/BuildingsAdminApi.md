# BuildingsAdminApi

All URIs are relative to *https://api.sensecoreai.com*

|Method | HTTP request | Description|
|------------- | ------------- | -------------|
|[**addBuildingApiV1AdminBuildingsAddPost**](#addbuildingapiv1adminbuildingsaddpost) | **POST** /api/v1/admin/buildings/add | Add Building|
|[**addBuildingApiV1AdminBuildingsAddPost_0**](#addbuildingapiv1adminbuildingsaddpost_0) | **POST** /api/v1/admin/buildings/add | Add Building|
|[**deleteBuildingApiV1AdminBuildingsDeleteBuildingIdDelete**](#deletebuildingapiv1adminbuildingsdeletebuildingiddelete) | **DELETE** /api/v1/admin/buildings/delete/{building_id} | Delete Building|
|[**deleteBuildingApiV1AdminBuildingsDeleteBuildingIdDelete_0**](#deletebuildingapiv1adminbuildingsdeletebuildingiddelete_0) | **DELETE** /api/v1/admin/buildings/delete/{building_id} | Delete Building|
|[**updateBuildingApiV1AdminBuildingsUpdateBuildingIdPut**](#updatebuildingapiv1adminbuildingsupdatebuildingidput) | **PUT** /api/v1/admin/buildings/update/{building_id} | Update Building|
|[**updateBuildingApiV1AdminBuildingsUpdateBuildingIdPut_0**](#updatebuildingapiv1adminbuildingsupdatebuildingidput_0) | **PUT** /api/v1/admin/buildings/update/{building_id} | Update Building|

# **addBuildingApiV1AdminBuildingsAddPost**
> any addBuildingApiV1AdminBuildingsAddPost(body)

Add a building. Body matches what the old direct-DB route used.

### Example

```typescript
import {
    BuildingsAdminApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new BuildingsAdminApi(configuration);

let body: object; //

const { status, data } = await apiInstance.addBuildingApiV1AdminBuildingsAddPost(
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

# **addBuildingApiV1AdminBuildingsAddPost_0**
> any addBuildingApiV1AdminBuildingsAddPost_0(body)

Add a building. Body matches what the old direct-DB route used.

### Example

```typescript
import {
    BuildingsAdminApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new BuildingsAdminApi(configuration);

let body: object; //

const { status, data } = await apiInstance.addBuildingApiV1AdminBuildingsAddPost_0(
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

# **deleteBuildingApiV1AdminBuildingsDeleteBuildingIdDelete**
> any deleteBuildingApiV1AdminBuildingsDeleteBuildingIdDelete()

Delete a building. Cascades remove meters via FK constraint.

### Example

```typescript
import {
    BuildingsAdminApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new BuildingsAdminApi(configuration);

let buildingId: string; // (default to undefined)

const { status, data } = await apiInstance.deleteBuildingApiV1AdminBuildingsDeleteBuildingIdDelete(
    buildingId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **buildingId** | [**string**] |  | defaults to undefined|


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

# **deleteBuildingApiV1AdminBuildingsDeleteBuildingIdDelete_0**
> any deleteBuildingApiV1AdminBuildingsDeleteBuildingIdDelete_0()

Delete a building. Cascades remove meters via FK constraint.

### Example

```typescript
import {
    BuildingsAdminApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new BuildingsAdminApi(configuration);

let buildingId: string; // (default to undefined)

const { status, data } = await apiInstance.deleteBuildingApiV1AdminBuildingsDeleteBuildingIdDelete_0(
    buildingId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **buildingId** | [**string**] |  | defaults to undefined|


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

# **updateBuildingApiV1AdminBuildingsUpdateBuildingIdPut**
> any updateBuildingApiV1AdminBuildingsUpdateBuildingIdPut(body)

Update fields on a building.

### Example

```typescript
import {
    BuildingsAdminApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new BuildingsAdminApi(configuration);

let buildingId: string; // (default to undefined)
let body: object; //

const { status, data } = await apiInstance.updateBuildingApiV1AdminBuildingsUpdateBuildingIdPut(
    buildingId,
    body
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **body** | **object**|  | |
| **buildingId** | [**string**] |  | defaults to undefined|


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

# **updateBuildingApiV1AdminBuildingsUpdateBuildingIdPut_0**
> any updateBuildingApiV1AdminBuildingsUpdateBuildingIdPut_0(body)

Update fields on a building.

### Example

```typescript
import {
    BuildingsAdminApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new BuildingsAdminApi(configuration);

let buildingId: string; // (default to undefined)
let body: object; //

const { status, data } = await apiInstance.updateBuildingApiV1AdminBuildingsUpdateBuildingIdPut_0(
    buildingId,
    body
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **body** | **object**|  | |
| **buildingId** | [**string**] |  | defaults to undefined|


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

