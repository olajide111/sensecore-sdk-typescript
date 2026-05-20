# AdminClientHealthApi

All URIs are relative to *https://api.sensecoreai.com*

|Method | HTTP request | Description|
|------------- | ------------- | -------------|
|[**getClientHealthApiV1AdminClientHealthGet**](#getclienthealthapiv1adminclienthealthget) | **GET** /api/v1/admin/client-health | Get Client Health|

# **getClientHealthApiV1AdminClientHealthGet**
> object getClientHealthApiV1AdminClientHealthGet()

Single endpoint returning all 7 sections of the Client Health dashboard.

### Example

```typescript
import {
    AdminClientHealthApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new AdminClientHealthApi(configuration);

const { status, data } = await apiInstance.getClientHealthApiV1AdminClientHealthGet();
```

### Parameters
This endpoint does not have any parameters.


### Return type

**object**

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

