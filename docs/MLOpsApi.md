# MLOpsApi

All URIs are relative to *https://api.sensecoreai.com*

|Method | HTTP request | Description|
|------------- | ------------- | -------------|
|[**createTrainingJobApiV1AdminMlopsTrainingJobsPost**](#createtrainingjobapiv1adminmlopstrainingjobspost) | **POST** /api/v1/admin/mlops/training-jobs | Create Training Job|
|[**getModelPerformanceApiV1AdminMlopsPerformanceGet**](#getmodelperformanceapiv1adminmlopsperformanceget) | **GET** /api/v1/admin/mlops/performance | Get Model Performance|
|[**listCheckpointsDetailedApiV1AdminMlopsCheckpointsGet**](#listcheckpointsdetailedapiv1adminmlopscheckpointsget) | **GET** /api/v1/admin/mlops/checkpoints | List Checkpoints Detailed|
|[**listTrainingJobsApiV1AdminMlopsTrainingJobsGet**](#listtrainingjobsapiv1adminmlopstrainingjobsget) | **GET** /api/v1/admin/mlops/training-jobs | List Training Jobs|
|[**setRetrainScheduleApiV1AdminMlopsSchedulePost**](#setretrainscheduleapiv1adminmlopsschedulepost) | **POST** /api/v1/admin/mlops/schedule | Set Retrain Schedule|
|[**updateTrainingJobApiV1AdminMlopsTrainingJobsJobIdPatch**](#updatetrainingjobapiv1adminmlopstrainingjobsjobidpatch) | **PATCH** /api/v1/admin/mlops/training-jobs/{job_id} | Update Training Job|

# **createTrainingJobApiV1AdminMlopsTrainingJobsPost**
> any createTrainingJobApiV1AdminMlopsTrainingJobsPost(body)

3D.2 — Queue a new training job

### Example

```typescript
import {
    MLOpsApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new MLOpsApi(configuration);

let body: object; //

const { status, data } = await apiInstance.createTrainingJobApiV1AdminMlopsTrainingJobsPost(
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

# **getModelPerformanceApiV1AdminMlopsPerformanceGet**
> any getModelPerformanceApiV1AdminMlopsPerformanceGet()

3D.3 — MAPE tracking over time

### Example

```typescript
import {
    MLOpsApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new MLOpsApi(configuration);

const { status, data } = await apiInstance.getModelPerformanceApiV1AdminMlopsPerformanceGet();
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

# **listCheckpointsDetailedApiV1AdminMlopsCheckpointsGet**
> any listCheckpointsDetailedApiV1AdminMlopsCheckpointsGet()

3D.6 — Model checkpoint details with S3 backup status

### Example

```typescript
import {
    MLOpsApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new MLOpsApi(configuration);

const { status, data } = await apiInstance.listCheckpointsDetailedApiV1AdminMlopsCheckpointsGet();
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

# **listTrainingJobsApiV1AdminMlopsTrainingJobsGet**
> any listTrainingJobsApiV1AdminMlopsTrainingJobsGet()

3D.2 — List training jobs (start, monitor, cancel)

### Example

```typescript
import {
    MLOpsApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new MLOpsApi(configuration);

const { status, data } = await apiInstance.listTrainingJobsApiV1AdminMlopsTrainingJobsGet();
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

# **setRetrainScheduleApiV1AdminMlopsSchedulePost**
> any setRetrainScheduleApiV1AdminMlopsSchedulePost(body)

3D.5 — Set retrain schedule (auto or manual)

### Example

```typescript
import {
    MLOpsApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new MLOpsApi(configuration);

let body: object; //

const { status, data } = await apiInstance.setRetrainScheduleApiV1AdminMlopsSchedulePost(
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

# **updateTrainingJobApiV1AdminMlopsTrainingJobsJobIdPatch**
> any updateTrainingJobApiV1AdminMlopsTrainingJobsJobIdPatch(body)

3D.2 — Update job status (called by training script)

### Example

```typescript
import {
    MLOpsApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new MLOpsApi(configuration);

let jobId: string; // (default to undefined)
let body: object; //

const { status, data } = await apiInstance.updateTrainingJobApiV1AdminMlopsTrainingJobsJobIdPatch(
    jobId,
    body
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **body** | **object**|  | |
| **jobId** | [**string**] |  | defaults to undefined|


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

