# PublicApi

All URIs are relative to *https://api.sensecoreai.com*

|Method | HTTP request | Description|
|------------- | ------------- | -------------|
|[**getPublicInvoiceApiV1InvoicePublicTokenGet**](#getpublicinvoiceapiv1invoicepublictokenget) | **GET** /api/v1/invoice/public/{token} | Get Public Invoice|

# **getPublicInvoiceApiV1InvoicePublicTokenGet**
> any getPublicInvoiceApiV1InvoicePublicTokenGet()


### Example

```typescript
import {
    PublicApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new PublicApi(configuration);

let token: string; // (default to undefined)

const { status, data } = await apiInstance.getPublicInvoiceApiV1InvoicePublicTokenGet(
    token
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **token** | [**string**] |  | defaults to undefined|


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

