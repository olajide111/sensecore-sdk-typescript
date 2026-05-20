# CarbonApi

All URIs are relative to *https://api.sensecoreai.com*

|Method | HTTP request | Description|
|------------- | ------------- | -------------|
|[**carbonReportApiV1CarbonPost**](#carbonreportapiv1carbonpost) | **POST** /api/v1/carbon | Carbon Report|

# **carbonReportApiV1CarbonPost**
> CarbonResponse carbonReportApiV1CarbonPost(carbonRequest)

Generate a Scope 2 carbon report from meter readings. SECR and EU EED compliant. Uses BEIS carbon intensity factors. Suitable for NHS sustainability returns, PSDS reporting, and SECR filings.

### Example

```typescript
import {
    CarbonApi,
    Configuration,
    CarbonRequest
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new CarbonApi(configuration);

let carbonRequest: CarbonRequest; //

const { status, data } = await apiInstance.carbonReportApiV1CarbonPost(
    carbonRequest
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **carbonRequest** | **CarbonRequest**|  | |


### Return type

**CarbonResponse**

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

