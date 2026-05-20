# OptimiseApi

All URIs are relative to *https://api.sensecoreai.com*

|Method | HTTP request | Description|
|------------- | ------------- | -------------|
|[**optimiseApiV1OptimisePost**](#optimiseapiv1optimisepost) | **POST** /api/v1/optimise | Optimise|

# **optimiseApiV1OptimisePost**
> OptimiseResponse optimiseApiV1OptimisePost(optimiseRequest)

Compare UK energy tariffs using actual consumption data. Returns best tariff and estimated annual saving in GBP.

### Example

```typescript
import {
    OptimiseApi,
    Configuration,
    OptimiseRequest
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new OptimiseApi(configuration);

let optimiseRequest: OptimiseRequest; //
let xAPIKey: string; // (optional) (default to undefined)

const { status, data } = await apiInstance.optimiseApiV1OptimisePost(
    optimiseRequest,
    xAPIKey
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **optimiseRequest** | **OptimiseRequest**|  | |
| **xAPIKey** | [**string**] |  | (optional) defaults to undefined|


### Return type

**OptimiseResponse**

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

