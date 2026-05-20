# MetersApi

All URIs are relative to *https://api.sensecoreai.com*

|Method | HTTP request | Description|
|------------- | ------------- | -------------|
|[**listMetersApiV1MetersGet**](#listmetersapiv1metersget) | **GET** /api/v1/meters | List Meters|

# **listMetersApiV1MetersGet**
> any listMetersApiV1MetersGet()


### Example

```typescript
import {
    MetersApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new MetersApi(configuration);

const { status, data } = await apiInstance.listMetersApiV1MetersGet();
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

