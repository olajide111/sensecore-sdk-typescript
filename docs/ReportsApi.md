# ReportsApi

All URIs are relative to *https://api.sensecoreai.com*

|Method | HTTP request | Description|
|------------- | ------------- | -------------|
|[**downloadAnomalyPdfApiV1ReportsAnomalyPdfGet**](#downloadanomalypdfapiv1reportsanomalypdfget) | **GET** /api/v1/reports/anomaly/pdf | Download Anomaly Pdf|
|[**downloadCarbonPdfApiV1ReportsCarbonPdfGet**](#downloadcarbonpdfapiv1reportscarbonpdfget) | **GET** /api/v1/reports/carbon/pdf | Download Carbon Pdf|
|[**downloadCompliancePdfApiV1ReportsCompliancePdfGet**](#downloadcompliancepdfapiv1reportscompliancepdfget) | **GET** /api/v1/reports/compliance/pdf | Download Compliance Pdf|
|[**downloadPortfolioPdfApiV1ReportsPortfolioPdfGet**](#downloadportfoliopdfapiv1reportsportfoliopdfget) | **GET** /api/v1/reports/portfolio/pdf | Download Portfolio Pdf|

# **downloadAnomalyPdfApiV1ReportsAnomalyPdfGet**
> any downloadAnomalyPdfApiV1ReportsAnomalyPdfGet()

Generate anomaly detection report PDF.

### Example

```typescript
import {
    ReportsApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new ReportsApi(configuration);

let period: string; // (optional) (default to 'Last 30 days')

const { status, data } = await apiInstance.downloadAnomalyPdfApiV1ReportsAnomalyPdfGet(
    period
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **period** | [**string**] |  | (optional) defaults to 'Last 30 days'|


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

# **downloadCarbonPdfApiV1ReportsCarbonPdfGet**
> any downloadCarbonPdfApiV1ReportsCarbonPdfGet()

Generate SECR-compliant carbon report PDF.

### Example

```typescript
import {
    ReportsApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new ReportsApi(configuration);

let period: string; // (optional) (default to '2025/26')
let revenueMillions: number; //Revenue in GBP millions (optional) (default to undefined)
let fteCount: number; //Full-time equivalent employees (optional) (default to undefined)
let floorAreaM2: number; //Total floor area m2 (optional) (default to undefined)

const { status, data } = await apiInstance.downloadCarbonPdfApiV1ReportsCarbonPdfGet(
    period,
    revenueMillions,
    fteCount,
    floorAreaM2
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **period** | [**string**] |  | (optional) defaults to '2025/26'|
| **revenueMillions** | [**number**] | Revenue in GBP millions | (optional) defaults to undefined|
| **fteCount** | [**number**] | Full-time equivalent employees | (optional) defaults to undefined|
| **floorAreaM2** | [**number**] | Total floor area m2 | (optional) defaults to undefined|


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

# **downloadCompliancePdfApiV1ReportsCompliancePdfGet**
> any downloadCompliancePdfApiV1ReportsCompliancePdfGet()

Generate multi-framework compliance status PDF.

### Example

```typescript
import {
    ReportsApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new ReportsApi(configuration);

const { status, data } = await apiInstance.downloadCompliancePdfApiV1ReportsCompliancePdfGet();
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

# **downloadPortfolioPdfApiV1ReportsPortfolioPdfGet**
> any downloadPortfolioPdfApiV1ReportsPortfolioPdfGet()

Generate portfolio performance report with CIBSE TM46 benchmarking.

### Example

```typescript
import {
    ReportsApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new ReportsApi(configuration);

const { status, data } = await apiInstance.downloadPortfolioPdfApiV1ReportsPortfolioPdfGet();
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

