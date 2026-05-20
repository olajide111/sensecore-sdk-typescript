# EnergyApi

All URIs are relative to *https://api.sensecoreai.com*

|Method | HTTP request | Description|
|------------- | ------------- | -------------|
|[**energyForecastApiV1EnergyForecastPost**](#energyforecastapiv1energyforecastpost) | **POST** /api/v1/energy/forecast | Energy Forecast|
|[**energyForecastApiV1EnergyForecastPost_0**](#energyforecastapiv1energyforecastpost_0) | **POST** /api/v1/energy/forecast | Energy Forecast|
|[**getEnergyTypesApiV1EnergyTypesGet**](#getenergytypesapiv1energytypesget) | **GET** /api/v1/energy/types | Get Energy Types|
|[**getEnergyTypesApiV1EnergyTypesGet_0**](#getenergytypesapiv1energytypesget_0) | **GET** /api/v1/energy/types | Get Energy Types|
|[**getWeatherDataApiV1EnergyWeatherGet**](#getweatherdataapiv1energyweatherget) | **GET** /api/v1/energy/weather | Get Weather Data|
|[**getWeatherDataApiV1EnergyWeatherGet_0**](#getweatherdataapiv1energyweatherget_0) | **GET** /api/v1/energy/weather | Get Weather Data|
|[**toggleEnergyTypeApiV1EnergyTypesTogglePost**](#toggleenergytypeapiv1energytypestogglepost) | **POST** /api/v1/energy/types/toggle | Toggle Energy Type|
|[**toggleEnergyTypeApiV1EnergyTypesTogglePost_0**](#toggleenergytypeapiv1energytypestogglepost_0) | **POST** /api/v1/energy/types/toggle | Toggle Energy Type|

# **energyForecastApiV1EnergyForecastPost**
> any energyForecastApiV1EnergyForecastPost(energyForecastRequest)


### Example

```typescript
import {
    EnergyApi,
    Configuration,
    EnergyForecastRequest
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new EnergyApi(configuration);

let energyForecastRequest: EnergyForecastRequest; //
let type: string; // (optional) (default to 'electricity')

const { status, data } = await apiInstance.energyForecastApiV1EnergyForecastPost(
    energyForecastRequest,
    type
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **energyForecastRequest** | **EnergyForecastRequest**|  | |
| **type** | [**string**] |  | (optional) defaults to 'electricity'|


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

# **energyForecastApiV1EnergyForecastPost_0**
> any energyForecastApiV1EnergyForecastPost_0(energyForecastRequest)


### Example

```typescript
import {
    EnergyApi,
    Configuration,
    EnergyForecastRequest
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new EnergyApi(configuration);

let energyForecastRequest: EnergyForecastRequest; //
let type: string; // (optional) (default to 'electricity')

const { status, data } = await apiInstance.energyForecastApiV1EnergyForecastPost_0(
    energyForecastRequest,
    type
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **energyForecastRequest** | **EnergyForecastRequest**|  | |
| **type** | [**string**] |  | (optional) defaults to 'electricity'|


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

# **getEnergyTypesApiV1EnergyTypesGet**
> any getEnergyTypesApiV1EnergyTypesGet()


### Example

```typescript
import {
    EnergyApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new EnergyApi(configuration);

const { status, data } = await apiInstance.getEnergyTypesApiV1EnergyTypesGet();
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

# **getEnergyTypesApiV1EnergyTypesGet_0**
> any getEnergyTypesApiV1EnergyTypesGet_0()


### Example

```typescript
import {
    EnergyApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new EnergyApi(configuration);

const { status, data } = await apiInstance.getEnergyTypesApiV1EnergyTypesGet_0();
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

# **getWeatherDataApiV1EnergyWeatherGet**
> any getWeatherDataApiV1EnergyWeatherGet()


### Example

```typescript
import {
    EnergyApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new EnergyApi(configuration);

let lat: number; // (optional) (default to 51.5074)
let lon: number; // (optional) (default to -0.1278)
let days: number; // (optional) (default to 7)

const { status, data } = await apiInstance.getWeatherDataApiV1EnergyWeatherGet(
    lat,
    lon,
    days
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **lat** | [**number**] |  | (optional) defaults to 51.5074|
| **lon** | [**number**] |  | (optional) defaults to -0.1278|
| **days** | [**number**] |  | (optional) defaults to 7|


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

# **getWeatherDataApiV1EnergyWeatherGet_0**
> any getWeatherDataApiV1EnergyWeatherGet_0()


### Example

```typescript
import {
    EnergyApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new EnergyApi(configuration);

let lat: number; // (optional) (default to 51.5074)
let lon: number; // (optional) (default to -0.1278)
let days: number; // (optional) (default to 7)

const { status, data } = await apiInstance.getWeatherDataApiV1EnergyWeatherGet_0(
    lat,
    lon,
    days
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **lat** | [**number**] |  | (optional) defaults to 51.5074|
| **lon** | [**number**] |  | (optional) defaults to -0.1278|
| **days** | [**number**] |  | (optional) defaults to 7|


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

# **toggleEnergyTypeApiV1EnergyTypesTogglePost**
> any toggleEnergyTypeApiV1EnergyTypesTogglePost(body)


### Example

```typescript
import {
    EnergyApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new EnergyApi(configuration);

let body: object; //

const { status, data } = await apiInstance.toggleEnergyTypeApiV1EnergyTypesTogglePost(
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

# **toggleEnergyTypeApiV1EnergyTypesTogglePost_0**
> any toggleEnergyTypeApiV1EnergyTypesTogglePost_0(body)


### Example

```typescript
import {
    EnergyApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new EnergyApi(configuration);

let body: object; //

const { status, data } = await apiInstance.toggleEnergyTypeApiV1EnergyTypesTogglePost_0(
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

