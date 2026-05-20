# SystemApi

All URIs are relative to *https://api.sensecoreai.com*

|Method | HTTP request | Description|
|------------- | ------------- | -------------|
|[**healthApiV1HealthHead**](#healthapiv1healthhead) | **GET** /api/v1/health | Health|
|[**healthApiV1HealthHead_0**](#healthapiv1healthhead_0) | **HEAD** /api/v1/health | Health|

# **healthApiV1HealthHead**
> HealthResponse healthApiV1HealthHead()

Returns API status, DB connectivity, loaded models, and uptime. No authentication required.

### Example

```typescript
import {
    SystemApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new SystemApi(configuration);

const { status, data } = await apiInstance.healthApiV1HealthHead();
```

### Parameters
This endpoint does not have any parameters.


### Return type

**HealthResponse**

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

# **healthApiV1HealthHead_0**
> HealthResponse healthApiV1HealthHead_0()

Returns API status, DB connectivity, loaded models, and uptime. No authentication required.

### Example

```typescript
import {
    SystemApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new SystemApi(configuration);

const { status, data } = await apiInstance.healthApiV1HealthHead_0();
```

### Parameters
This endpoint does not have any parameters.


### Return type

**HealthResponse**

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

