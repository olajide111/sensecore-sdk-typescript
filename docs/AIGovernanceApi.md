# AIGovernanceApi

All URIs are relative to *https://api.sensecoreai.com*

|Method | HTTP request | Description|
|------------- | ------------- | -------------|
|[**aiTransparencyApiV1AiTransparencyGet**](#aitransparencyapiv1aitransparencyget) | **GET** /api/v1/ai/transparency | Ai Transparency|
|[**aiTransparencyApiV1AiTransparencyGet_0**](#aitransparencyapiv1aitransparencyget_0) | **GET** /api/v1/ai/transparency | Ai Transparency|
|[**biasAssessmentApiV1AiBiasAssessmentGet**](#biasassessmentapiv1aibiasassessmentget) | **GET** /api/v1/ai/bias-assessment | Bias Assessment|
|[**biasAssessmentApiV1AiBiasAssessmentGet_0**](#biasassessmentapiv1aibiasassessmentget_0) | **GET** /api/v1/ai/bias-assessment | Bias Assessment|
|[**getModelDetailApiV1AiModelsModelIdGet**](#getmodeldetailapiv1aimodelsmodelidget) | **GET** /api/v1/ai/models/{model_id} | Get Model Detail|
|[**getModelDetailApiV1AiModelsModelIdGet_0**](#getmodeldetailapiv1aimodelsmodelidget_0) | **GET** /api/v1/ai/models/{model_id} | Get Model Detail|
|[**listModelsApiV1AiModelsGet**](#listmodelsapiv1aimodelsget) | **GET** /api/v1/ai/models | List Models|
|[**listModelsApiV1AiModelsGet_0**](#listmodelsapiv1aimodelsget_0) | **GET** /api/v1/ai/models | List Models|

# **aiTransparencyApiV1AiTransparencyGet**
> any aiTransparencyApiV1AiTransparencyGet()

EU AI Act Article 13 transparency information.

### Example

```typescript
import {
    AIGovernanceApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new AIGovernanceApi(configuration);

const { status, data } = await apiInstance.aiTransparencyApiV1AiTransparencyGet();
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

# **aiTransparencyApiV1AiTransparencyGet_0**
> any aiTransparencyApiV1AiTransparencyGet_0()

EU AI Act Article 13 transparency information.

### Example

```typescript
import {
    AIGovernanceApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new AIGovernanceApi(configuration);

const { status, data } = await apiInstance.aiTransparencyApiV1AiTransparencyGet_0();
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

# **biasAssessmentApiV1AiBiasAssessmentGet**
> any biasAssessmentApiV1AiBiasAssessmentGet()

FPRS bias assessment — protected characteristics analysis.

### Example

```typescript
import {
    AIGovernanceApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new AIGovernanceApi(configuration);

const { status, data } = await apiInstance.biasAssessmentApiV1AiBiasAssessmentGet();
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

# **biasAssessmentApiV1AiBiasAssessmentGet_0**
> any biasAssessmentApiV1AiBiasAssessmentGet_0()

FPRS bias assessment — protected characteristics analysis.

### Example

```typescript
import {
    AIGovernanceApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new AIGovernanceApi(configuration);

const { status, data } = await apiInstance.biasAssessmentApiV1AiBiasAssessmentGet_0();
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

# **getModelDetailApiV1AiModelsModelIdGet**
> any getModelDetailApiV1AiModelsModelIdGet()

Get detailed information about a specific model.

### Example

```typescript
import {
    AIGovernanceApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new AIGovernanceApi(configuration);

let modelId: string; // (default to undefined)

const { status, data } = await apiInstance.getModelDetailApiV1AiModelsModelIdGet(
    modelId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **modelId** | [**string**] |  | defaults to undefined|


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

# **getModelDetailApiV1AiModelsModelIdGet_0**
> any getModelDetailApiV1AiModelsModelIdGet_0()

Get detailed information about a specific model.

### Example

```typescript
import {
    AIGovernanceApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new AIGovernanceApi(configuration);

let modelId: string; // (default to undefined)

const { status, data } = await apiInstance.getModelDetailApiV1AiModelsModelIdGet_0(
    modelId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **modelId** | [**string**] |  | defaults to undefined|


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

# **listModelsApiV1AiModelsGet**
> any listModelsApiV1AiModelsGet()

List all deployed AI models with metadata.

### Example

```typescript
import {
    AIGovernanceApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new AIGovernanceApi(configuration);

const { status, data } = await apiInstance.listModelsApiV1AiModelsGet();
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

# **listModelsApiV1AiModelsGet_0**
> any listModelsApiV1AiModelsGet_0()

List all deployed AI models with metadata.

### Example

```typescript
import {
    AIGovernanceApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new AIGovernanceApi(configuration);

const { status, data } = await apiInstance.listModelsApiV1AiModelsGet_0();
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

