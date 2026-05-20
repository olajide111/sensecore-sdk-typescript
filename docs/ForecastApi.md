# ForecastApi

All URIs are relative to *https://api.sensecoreai.com*

|Method | HTTP request | Description|
|------------- | ------------- | -------------|
|[**forecastApiV1ForecastPost**](#forecastapiv1forecastpost) | **POST** /api/v1/forecast | Forecast|

# **forecastApiV1ForecastPost**
> ForecastResponse forecastApiV1ForecastPost(forecastRequest)

SenseCore AI — Full energy intelligence bundle.  **Input:** 336+ half-hourly meter readings (7 days minimum)  **Returns:** - 48-period TFT forecast with 80% prediction interval - Carbon intensity layer (Scope 2, SECR-ready) - Anomaly detection flags - Fuel poverty risk score (FPRS — 5 signals) - Occupancy inference - Cost estimate at current UK tariff

### Example

```typescript
import {
    ForecastApi,
    Configuration,
    ForecastRequest
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new ForecastApi(configuration);

let forecastRequest: ForecastRequest; //
let xAPIKey: string; // (optional) (default to undefined)

const { status, data } = await apiInstance.forecastApiV1ForecastPost(
    forecastRequest,
    xAPIKey
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **forecastRequest** | **ForecastRequest**|  | |
| **xAPIKey** | [**string**] |  | (optional) defaults to undefined|


### Return type

**ForecastResponse**

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

