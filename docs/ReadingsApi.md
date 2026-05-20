# ReadingsApi

All URIs are relative to *https://api.sensecoreai.com*

|Method | HTTP request | Description|
|------------- | ------------- | -------------|
|[**getReadingsApiV1ReadingsGet**](#getreadingsapiv1readingsget) | **GET** /api/v1/readings | Get Readings|
|[**getReadingsApiV1ReadingsMeterIdGet**](#getreadingsapiv1readingsmeteridget) | **GET** /api/v1/readings/{meter_id} | Get Readings|
|[**listMetersApiV1BuildingsMetersGet**](#listmetersapiv1buildingsmetersget) | **GET** /api/v1/buildings/meters | List Meters|
|[**manualReadingApiV1ReadingsManualPost**](#manualreadingapiv1readingsmanualpost) | **POST** /api/v1/readings/manual | Manual Reading|
|[**pushReadingsApiV1ReadingsPushPost**](#pushreadingsapiv1readingspushpost) | **POST** /api/v1/readings/push | Push Readings|

# **getReadingsApiV1ReadingsGet**
> any getReadingsApiV1ReadingsGet()


### Example

```typescript
import {
    ReadingsApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new ReadingsApi(configuration);

let meterId: string; // (default to undefined)

const { status, data } = await apiInstance.getReadingsApiV1ReadingsGet(
    meterId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
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

# **getReadingsApiV1ReadingsMeterIdGet**
> any getReadingsApiV1ReadingsMeterIdGet()

Fetch the most recent readings for a meter. Returns readings sorted by timestamp (newest first, then reversed for chart display).

### Example

```typescript
import {
    ReadingsApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new ReadingsApi(configuration);

let meterId: string; // (default to undefined)
let limit: number; // (optional) (default to 336)

const { status, data } = await apiInstance.getReadingsApiV1ReadingsMeterIdGet(
    meterId,
    limit
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **meterId** | [**string**] |  | defaults to undefined|
| **limit** | [**number**] |  | (optional) defaults to 336|


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

# **listMetersApiV1BuildingsMetersGet**
> any listMetersApiV1BuildingsMetersGet()

List all meters that have ingested readings. Returns meter_id, building name, reading count, date range, quality.

### Example

```typescript
import {
    ReadingsApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new ReadingsApi(configuration);

const { status, data } = await apiInstance.listMetersApiV1BuildingsMetersGet();
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

# **manualReadingApiV1ReadingsManualPost**
> ManualResponse manualReadingApiV1ReadingsManualPost(manualRequest)

Submit a single meter reading manually. Used for gap-filling, testing, or manual data entry from the dashboard.

### Example

```typescript
import {
    ReadingsApi,
    Configuration,
    ManualRequest
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new ReadingsApi(configuration);

let manualRequest: ManualRequest; //

const { status, data } = await apiInstance.manualReadingApiV1ReadingsManualPost(
    manualRequest
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **manualRequest** | **ManualRequest**|  | |


### Return type

**ManualResponse**

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

# **pushReadingsApiV1ReadingsPushPost**
> PushResponse pushReadingsApiV1ReadingsPushPost(pushRequest)

Bulk push meter readings as JSON. Used by IoT gateways, BMS integrations, and automated data feeds. Duplicate timestamps are updated (upsert).

### Example

```typescript
import {
    ReadingsApi,
    Configuration,
    PushRequest
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new ReadingsApi(configuration);

let pushRequest: PushRequest; //

const { status, data } = await apiInstance.pushReadingsApiV1ReadingsPushPost(
    pushRequest
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **pushRequest** | **PushRequest**|  | |


### Return type

**PushResponse**

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

