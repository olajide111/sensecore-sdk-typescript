# IngestApi

All URIs are relative to *https://api.sensecoreai.com*

|Method | HTTP request | Description|
|------------- | ------------- | -------------|
|[**ingestApiV1IngestPost**](#ingestapiv1ingestpost) | **POST** /api/v1/ingest | Ingest|

# **ingestApiV1IngestPost**
> IngestResponse ingestApiV1IngestPost()

Upload a CSV of half-hourly meter readings. Accepts exports from Octopus Energy, British Gas, EON, and most UK suppliers.

### Example

```typescript
import {
    IngestApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new IngestApi(configuration);

let meterId: string; // (default to undefined)
let file: File; // (default to undefined)
let xAPIKey: string; // (optional) (default to undefined)

const { status, data } = await apiInstance.ingestApiV1IngestPost(
    meterId,
    file,
    xAPIKey
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **meterId** | [**string**] |  | defaults to undefined|
| **file** | [**File**] |  | defaults to undefined|
| **xAPIKey** | [**string**] |  | (optional) defaults to undefined|


### Return type

**IngestResponse**

### Authorization

[OAuth2PasswordBearer](../README.md#OAuth2PasswordBearer)

### HTTP request headers

 - **Content-Type**: multipart/form-data
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | Successful Response |  -  |
|**422** | Validation Error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

