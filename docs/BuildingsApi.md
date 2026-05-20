# BuildingsApi

All URIs are relative to *https://api.sensecoreai.com*

|Method | HTTP request | Description|
|------------- | ------------- | -------------|
|[**addMeterBuildingsBuildingIdMetersPost**](#addmeterbuildingsbuildingidmeterspost) | **POST** /buildings/{building_id}/meters | Add Meter|
|[**bulkUploadBuildingsBuildingsBulkUploadPost**](#bulkuploadbuildingsbuildingsbulkuploadpost) | **POST** /buildings/bulk-upload | Bulk Upload Buildings|
|[**createBuildingApiV1BuildingsPost**](#createbuildingapiv1buildingspost) | **POST** /api/v1/buildings | Create Building|
|[**deleteBuildingApiV1BuildingsBuildingIdDelete**](#deletebuildingapiv1buildingsbuildingiddelete) | **DELETE** /api/v1/buildings/{building_id} | Delete Building|
|[**deleteMeterBuildingsBuildingIdMetersMeterIdDelete**](#deletemeterbuildingsbuildingidmetersmeteriddelete) | **DELETE** /buildings/{building_id}/meters/{meter_id} | Delete Meter|
|[**getBuildingApiV1BuildingsBuildingIdGet**](#getbuildingapiv1buildingsbuildingidget) | **GET** /api/v1/buildings/{building_id} | Get Building|
|[**getBuildingBuildingsBuildingIdGet**](#getbuildingbuildingsbuildingidget) | **GET** /buildings/{building_id} | Get Building|
|[**getMetersBuildingsBuildingIdMetersGet**](#getmetersbuildingsbuildingidmetersget) | **GET** /buildings/{building_id}/meters | Get Meters|
|[**listBuildingsApiV1BuildingsGet**](#listbuildingsapiv1buildingsget) | **GET** /api/v1/buildings | List Buildings|
|[**updateBuildingApiV1BuildingsBuildingIdPatch**](#updatebuildingapiv1buildingsbuildingidpatch) | **PATCH** /api/v1/buildings/{building_id} | Update Building|
|[**updateMeterBuildingsBuildingIdMetersMeterIdPatch**](#updatemeterbuildingsbuildingidmetersmeteridpatch) | **PATCH** /buildings/{building_id}/meters/{meter_id} | Update Meter|

# **addMeterBuildingsBuildingIdMetersPost**
> any addMeterBuildingsBuildingIdMetersPost(body)


### Example

```typescript
import {
    BuildingsApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new BuildingsApi(configuration);

let buildingId: string; // (default to undefined)
let body: object; //

const { status, data } = await apiInstance.addMeterBuildingsBuildingIdMetersPost(
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

# **bulkUploadBuildingsBuildingsBulkUploadPost**
> any bulkUploadBuildingsBuildingsBulkUploadPost(body)


### Example

```typescript
import {
    BuildingsApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new BuildingsApi(configuration);

let body: object; //

const { status, data } = await apiInstance.bulkUploadBuildingsBuildingsBulkUploadPost(
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

# **createBuildingApiV1BuildingsPost**
> any createBuildingApiV1BuildingsPost(body)


### Example

```typescript
import {
    BuildingsApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new BuildingsApi(configuration);

let body: object; //

const { status, data } = await apiInstance.createBuildingApiV1BuildingsPost(
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

# **deleteBuildingApiV1BuildingsBuildingIdDelete**
> any deleteBuildingApiV1BuildingsBuildingIdDelete()


### Example

```typescript
import {
    BuildingsApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new BuildingsApi(configuration);

let buildingId: number; // (default to undefined)

const { status, data } = await apiInstance.deleteBuildingApiV1BuildingsBuildingIdDelete(
    buildingId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **buildingId** | [**number**] |  | defaults to undefined|


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

# **deleteMeterBuildingsBuildingIdMetersMeterIdDelete**
> any deleteMeterBuildingsBuildingIdMetersMeterIdDelete()


### Example

```typescript
import {
    BuildingsApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new BuildingsApi(configuration);

let buildingId: string; // (default to undefined)
let meterId: string; // (default to undefined)

const { status, data } = await apiInstance.deleteMeterBuildingsBuildingIdMetersMeterIdDelete(
    buildingId,
    meterId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **buildingId** | [**string**] |  | defaults to undefined|
| **meterId** | [**string**] |  | defaults to undefined|


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

# **getBuildingApiV1BuildingsBuildingIdGet**
> any getBuildingApiV1BuildingsBuildingIdGet()


### Example

```typescript
import {
    BuildingsApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new BuildingsApi(configuration);

let buildingId: number; // (default to undefined)

const { status, data } = await apiInstance.getBuildingApiV1BuildingsBuildingIdGet(
    buildingId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **buildingId** | [**number**] |  | defaults to undefined|


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

# **getBuildingBuildingsBuildingIdGet**
> any getBuildingBuildingsBuildingIdGet()


### Example

```typescript
import {
    BuildingsApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new BuildingsApi(configuration);

let buildingId: string; // (default to undefined)

const { status, data } = await apiInstance.getBuildingBuildingsBuildingIdGet(
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

# **getMetersBuildingsBuildingIdMetersGet**
> any getMetersBuildingsBuildingIdMetersGet()


### Example

```typescript
import {
    BuildingsApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new BuildingsApi(configuration);

let buildingId: string; // (default to undefined)

const { status, data } = await apiInstance.getMetersBuildingsBuildingIdMetersGet(
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

# **listBuildingsApiV1BuildingsGet**
> any listBuildingsApiV1BuildingsGet()


### Example

```typescript
import {
    BuildingsApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new BuildingsApi(configuration);

const { status, data } = await apiInstance.listBuildingsApiV1BuildingsGet();
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

# **updateBuildingApiV1BuildingsBuildingIdPatch**
> any updateBuildingApiV1BuildingsBuildingIdPatch(body)


### Example

```typescript
import {
    BuildingsApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new BuildingsApi(configuration);

let buildingId: number; // (default to undefined)
let body: object; //

const { status, data } = await apiInstance.updateBuildingApiV1BuildingsBuildingIdPatch(
    buildingId,
    body
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **body** | **object**|  | |
| **buildingId** | [**number**] |  | defaults to undefined|


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

# **updateMeterBuildingsBuildingIdMetersMeterIdPatch**
> any updateMeterBuildingsBuildingIdMetersMeterIdPatch(body)


### Example

```typescript
import {
    BuildingsApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new BuildingsApi(configuration);

let buildingId: string; // (default to undefined)
let meterId: string; // (default to undefined)
let body: object; //

const { status, data } = await apiInstance.updateMeterBuildingsBuildingIdMetersMeterIdPatch(
    buildingId,
    meterId,
    body
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **body** | **object**|  | |
| **buildingId** | [**string**] |  | defaults to undefined|
| **meterId** | [**string**] |  | defaults to undefined|


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

