# SavingsApi

All URIs are relative to *https://api.sensecoreai.com*

|Method | HTTP request | Description|
|------------- | ------------- | -------------|
|[**downloadSavingsPdfAdminApiV1SavingsAdminOrgIdPdfGet**](#downloadsavingspdfadminapiv1savingsadminorgidpdfget) | **GET** /api/v1/savings/admin/{org_id}/pdf | Download Savings Pdf Admin|
|[**downloadSavingsPdfAdminApiV1SavingsAdminOrgIdPdfGet_0**](#downloadsavingspdfadminapiv1savingsadminorgidpdfget_0) | **GET** /api/v1/savings/admin/{org_id}/pdf | Download Savings Pdf Admin|
|[**downloadSavingsPdfApiV1SavingsPdfGet**](#downloadsavingspdfapiv1savingspdfget) | **GET** /api/v1/savings/pdf | Download Savings Pdf|
|[**downloadSavingsPdfApiV1SavingsPdfGet_0**](#downloadsavingspdfapiv1savingspdfget_0) | **GET** /api/v1/savings/pdf | Download Savings Pdf|
|[**getComplianceSavingsApiV1SavingsComplianceGet**](#getcompliancesavingsapiv1savingscomplianceget) | **GET** /api/v1/savings/compliance | Get Compliance Savings|
|[**getComplianceSavingsApiV1SavingsComplianceGet_0**](#getcompliancesavingsapiv1savingscomplianceget_0) | **GET** /api/v1/savings/compliance | Get Compliance Savings|
|[**getRoiMetricApiV1SavingsRoiGet**](#getroimetricapiv1savingsroiget) | **GET** /api/v1/savings/roi | Get Roi Metric|
|[**getRoiMetricApiV1SavingsRoiGet_0**](#getroimetricapiv1savingsroiget_0) | **GET** /api/v1/savings/roi | Get Roi Metric|
|[**getSavingsByBuildingApiV1SavingsBuildingsGet**](#getsavingsbybuildingapiv1savingsbuildingsget) | **GET** /api/v1/savings/buildings | Get Savings By Building|
|[**getSavingsByBuildingApiV1SavingsBuildingsGet_0**](#getsavingsbybuildingapiv1savingsbuildingsget_0) | **GET** /api/v1/savings/buildings | Get Savings By Building|
|[**getSavingsForOrgApiV1SavingsAdminOrgIdGet**](#getsavingsfororgapiv1savingsadminorgidget) | **GET** /api/v1/savings/admin/{org_id} | Get Savings For Org|
|[**getSavingsForOrgApiV1SavingsAdminOrgIdGet_0**](#getsavingsfororgapiv1savingsadminorgidget_0) | **GET** /api/v1/savings/admin/{org_id} | Get Savings For Org|
|[**getSavingsSummaryApiV1SavingsSummaryGet**](#getsavingssummaryapiv1savingssummaryget) | **GET** /api/v1/savings/summary | Get Savings Summary|
|[**getSavingsSummaryApiV1SavingsSummaryGet_0**](#getsavingssummaryapiv1savingssummaryget_0) | **GET** /api/v1/savings/summary | Get Savings Summary|
|[**getSavingsTrendApiV1SavingsTrendGet**](#getsavingstrendapiv1savingstrendget) | **GET** /api/v1/savings/trend | Get Savings Trend|
|[**getSavingsTrendApiV1SavingsTrendGet_0**](#getsavingstrendapiv1savingstrendget_0) | **GET** /api/v1/savings/trend | Get Savings Trend|

# **downloadSavingsPdfAdminApiV1SavingsAdminOrgIdPdfGet**
> any downloadSavingsPdfAdminApiV1SavingsAdminOrgIdPdfGet()

Admin-only: Generate savings PDF for any organisation.

### Example

```typescript
import {
    SavingsApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new SavingsApi(configuration);

let orgId: number; // (default to undefined)
let period: string; // (optional) (default to 'quarterly')
let startDate: string; // (optional) (default to undefined)
let endDate: string; // (optional) (default to undefined)

const { status, data } = await apiInstance.downloadSavingsPdfAdminApiV1SavingsAdminOrgIdPdfGet(
    orgId,
    period,
    startDate,
    endDate
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **orgId** | [**number**] |  | defaults to undefined|
| **period** | [**string**] |  | (optional) defaults to 'quarterly'|
| **startDate** | [**string**] |  | (optional) defaults to undefined|
| **endDate** | [**string**] |  | (optional) defaults to undefined|


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

# **downloadSavingsPdfAdminApiV1SavingsAdminOrgIdPdfGet_0**
> any downloadSavingsPdfAdminApiV1SavingsAdminOrgIdPdfGet_0()

Admin-only: Generate savings PDF for any organisation.

### Example

```typescript
import {
    SavingsApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new SavingsApi(configuration);

let orgId: number; // (default to undefined)
let period: string; // (optional) (default to 'quarterly')
let startDate: string; // (optional) (default to undefined)
let endDate: string; // (optional) (default to undefined)

const { status, data } = await apiInstance.downloadSavingsPdfAdminApiV1SavingsAdminOrgIdPdfGet_0(
    orgId,
    period,
    startDate,
    endDate
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **orgId** | [**number**] |  | defaults to undefined|
| **period** | [**string**] |  | (optional) defaults to 'quarterly'|
| **startDate** | [**string**] |  | (optional) defaults to undefined|
| **endDate** | [**string**] |  | (optional) defaults to undefined|


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

# **downloadSavingsPdfApiV1SavingsPdfGet**
> any downloadSavingsPdfApiV1SavingsPdfGet()

Generate and download a branded, board-ready savings PDF report.

### Example

```typescript
import {
    SavingsApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new SavingsApi(configuration);

let period: string; // (optional) (default to 'quarterly')
let startDate: string; // (optional) (default to undefined)
let endDate: string; // (optional) (default to undefined)

const { status, data } = await apiInstance.downloadSavingsPdfApiV1SavingsPdfGet(
    period,
    startDate,
    endDate
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **period** | [**string**] |  | (optional) defaults to 'quarterly'|
| **startDate** | [**string**] |  | (optional) defaults to undefined|
| **endDate** | [**string**] |  | (optional) defaults to undefined|


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

# **downloadSavingsPdfApiV1SavingsPdfGet_0**
> any downloadSavingsPdfApiV1SavingsPdfGet_0()

Generate and download a branded, board-ready savings PDF report.

### Example

```typescript
import {
    SavingsApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new SavingsApi(configuration);

let period: string; // (optional) (default to 'quarterly')
let startDate: string; // (optional) (default to undefined)
let endDate: string; // (optional) (default to undefined)

const { status, data } = await apiInstance.downloadSavingsPdfApiV1SavingsPdfGet_0(
    period,
    startDate,
    endDate
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **period** | [**string**] |  | (optional) defaults to 'quarterly'|
| **startDate** | [**string**] |  | (optional) defaults to undefined|
| **endDate** | [**string**] |  | (optional) defaults to undefined|


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

# **getComplianceSavingsApiV1SavingsComplianceGet**
> any getComplianceSavingsApiV1SavingsComplianceGet()

Compliance hours and cost savings breakdown by framework.

### Example

```typescript
import {
    SavingsApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new SavingsApi(configuration);

let period: string; // (optional) (default to 'quarterly')
let startDate: string; // (optional) (default to undefined)
let endDate: string; // (optional) (default to undefined)

const { status, data } = await apiInstance.getComplianceSavingsApiV1SavingsComplianceGet(
    period,
    startDate,
    endDate
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **period** | [**string**] |  | (optional) defaults to 'quarterly'|
| **startDate** | [**string**] |  | (optional) defaults to undefined|
| **endDate** | [**string**] |  | (optional) defaults to undefined|


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

# **getComplianceSavingsApiV1SavingsComplianceGet_0**
> any getComplianceSavingsApiV1SavingsComplianceGet_0()

Compliance hours and cost savings breakdown by framework.

### Example

```typescript
import {
    SavingsApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new SavingsApi(configuration);

let period: string; // (optional) (default to 'quarterly')
let startDate: string; // (optional) (default to undefined)
let endDate: string; // (optional) (default to undefined)

const { status, data } = await apiInstance.getComplianceSavingsApiV1SavingsComplianceGet_0(
    period,
    startDate,
    endDate
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **period** | [**string**] |  | (optional) defaults to 'quarterly'|
| **startDate** | [**string**] |  | (optional) defaults to undefined|
| **endDate** | [**string**] |  | (optional) defaults to undefined|


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

# **getRoiMetricApiV1SavingsRoiGet**
> any getRoiMetricApiV1SavingsRoiGet()

ROI metric — savings vs subscription cost.

### Example

```typescript
import {
    SavingsApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new SavingsApi(configuration);

let period: string; // (optional) (default to 'quarterly')
let startDate: string; // (optional) (default to undefined)
let endDate: string; // (optional) (default to undefined)

const { status, data } = await apiInstance.getRoiMetricApiV1SavingsRoiGet(
    period,
    startDate,
    endDate
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **period** | [**string**] |  | (optional) defaults to 'quarterly'|
| **startDate** | [**string**] |  | (optional) defaults to undefined|
| **endDate** | [**string**] |  | (optional) defaults to undefined|


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

# **getRoiMetricApiV1SavingsRoiGet_0**
> any getRoiMetricApiV1SavingsRoiGet_0()

ROI metric — savings vs subscription cost.

### Example

```typescript
import {
    SavingsApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new SavingsApi(configuration);

let period: string; // (optional) (default to 'quarterly')
let startDate: string; // (optional) (default to undefined)
let endDate: string; // (optional) (default to undefined)

const { status, data } = await apiInstance.getRoiMetricApiV1SavingsRoiGet_0(
    period,
    startDate,
    endDate
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **period** | [**string**] |  | (optional) defaults to 'quarterly'|
| **startDate** | [**string**] |  | (optional) defaults to undefined|
| **endDate** | [**string**] |  | (optional) defaults to undefined|


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

# **getSavingsByBuildingApiV1SavingsBuildingsGet**
> any getSavingsByBuildingApiV1SavingsBuildingsGet()

Per-building savings breakdown, sorted by highest savings first.

### Example

```typescript
import {
    SavingsApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new SavingsApi(configuration);

let period: string; // (optional) (default to 'quarterly')
let startDate: string; // (optional) (default to undefined)
let endDate: string; // (optional) (default to undefined)

const { status, data } = await apiInstance.getSavingsByBuildingApiV1SavingsBuildingsGet(
    period,
    startDate,
    endDate
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **period** | [**string**] |  | (optional) defaults to 'quarterly'|
| **startDate** | [**string**] |  | (optional) defaults to undefined|
| **endDate** | [**string**] |  | (optional) defaults to undefined|


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

# **getSavingsByBuildingApiV1SavingsBuildingsGet_0**
> any getSavingsByBuildingApiV1SavingsBuildingsGet_0()

Per-building savings breakdown, sorted by highest savings first.

### Example

```typescript
import {
    SavingsApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new SavingsApi(configuration);

let period: string; // (optional) (default to 'quarterly')
let startDate: string; // (optional) (default to undefined)
let endDate: string; // (optional) (default to undefined)

const { status, data } = await apiInstance.getSavingsByBuildingApiV1SavingsBuildingsGet_0(
    period,
    startDate,
    endDate
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **period** | [**string**] |  | (optional) defaults to 'quarterly'|
| **startDate** | [**string**] |  | (optional) defaults to undefined|
| **endDate** | [**string**] |  | (optional) defaults to undefined|


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

# **getSavingsForOrgApiV1SavingsAdminOrgIdGet**
> any getSavingsForOrgApiV1SavingsAdminOrgIdGet()

Admin-only: full savings summary for any organisation.

### Example

```typescript
import {
    SavingsApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new SavingsApi(configuration);

let orgId: number; // (default to undefined)
let period: string; // (optional) (default to 'quarterly')
let startDate: string; // (optional) (default to undefined)
let endDate: string; // (optional) (default to undefined)

const { status, data } = await apiInstance.getSavingsForOrgApiV1SavingsAdminOrgIdGet(
    orgId,
    period,
    startDate,
    endDate
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **orgId** | [**number**] |  | defaults to undefined|
| **period** | [**string**] |  | (optional) defaults to 'quarterly'|
| **startDate** | [**string**] |  | (optional) defaults to undefined|
| **endDate** | [**string**] |  | (optional) defaults to undefined|


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

# **getSavingsForOrgApiV1SavingsAdminOrgIdGet_0**
> any getSavingsForOrgApiV1SavingsAdminOrgIdGet_0()

Admin-only: full savings summary for any organisation.

### Example

```typescript
import {
    SavingsApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new SavingsApi(configuration);

let orgId: number; // (default to undefined)
let period: string; // (optional) (default to 'quarterly')
let startDate: string; // (optional) (default to undefined)
let endDate: string; // (optional) (default to undefined)

const { status, data } = await apiInstance.getSavingsForOrgApiV1SavingsAdminOrgIdGet_0(
    orgId,
    period,
    startDate,
    endDate
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **orgId** | [**number**] |  | defaults to undefined|
| **period** | [**string**] |  | (optional) defaults to 'quarterly'|
| **startDate** | [**string**] |  | (optional) defaults to undefined|
| **endDate** | [**string**] |  | (optional) defaults to undefined|


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

# **getSavingsSummaryApiV1SavingsSummaryGet**
> any getSavingsSummaryApiV1SavingsSummaryGet()

Full savings summary for the logged-in user\'s organisation. Returns all three pillars, ROI, per-building breakdown, and trend.

### Example

```typescript
import {
    SavingsApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new SavingsApi(configuration);

let period: string; // (optional) (default to 'quarterly')
let startDate: string; // (optional) (default to undefined)
let endDate: string; // (optional) (default to undefined)
let buildingIds: string; //Comma-separated building IDs (optional) (default to undefined)

const { status, data } = await apiInstance.getSavingsSummaryApiV1SavingsSummaryGet(
    period,
    startDate,
    endDate,
    buildingIds
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **period** | [**string**] |  | (optional) defaults to 'quarterly'|
| **startDate** | [**string**] |  | (optional) defaults to undefined|
| **endDate** | [**string**] |  | (optional) defaults to undefined|
| **buildingIds** | [**string**] | Comma-separated building IDs | (optional) defaults to undefined|


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

# **getSavingsSummaryApiV1SavingsSummaryGet_0**
> any getSavingsSummaryApiV1SavingsSummaryGet_0()

Full savings summary for the logged-in user\'s organisation. Returns all three pillars, ROI, per-building breakdown, and trend.

### Example

```typescript
import {
    SavingsApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new SavingsApi(configuration);

let period: string; // (optional) (default to 'quarterly')
let startDate: string; // (optional) (default to undefined)
let endDate: string; // (optional) (default to undefined)
let buildingIds: string; //Comma-separated building IDs (optional) (default to undefined)

const { status, data } = await apiInstance.getSavingsSummaryApiV1SavingsSummaryGet_0(
    period,
    startDate,
    endDate,
    buildingIds
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **period** | [**string**] |  | (optional) defaults to 'quarterly'|
| **startDate** | [**string**] |  | (optional) defaults to undefined|
| **endDate** | [**string**] |  | (optional) defaults to undefined|
| **buildingIds** | [**string**] | Comma-separated building IDs | (optional) defaults to undefined|


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

# **getSavingsTrendApiV1SavingsTrendGet**
> any getSavingsTrendApiV1SavingsTrendGet()

Month-over-month savings trend data for charts.

### Example

```typescript
import {
    SavingsApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new SavingsApi(configuration);

let period: string; // (optional) (default to 'quarterly')
let startDate: string; // (optional) (default to undefined)
let endDate: string; // (optional) (default to undefined)

const { status, data } = await apiInstance.getSavingsTrendApiV1SavingsTrendGet(
    period,
    startDate,
    endDate
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **period** | [**string**] |  | (optional) defaults to 'quarterly'|
| **startDate** | [**string**] |  | (optional) defaults to undefined|
| **endDate** | [**string**] |  | (optional) defaults to undefined|


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

# **getSavingsTrendApiV1SavingsTrendGet_0**
> any getSavingsTrendApiV1SavingsTrendGet_0()

Month-over-month savings trend data for charts.

### Example

```typescript
import {
    SavingsApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new SavingsApi(configuration);

let period: string; // (optional) (default to 'quarterly')
let startDate: string; // (optional) (default to undefined)
let endDate: string; // (optional) (default to undefined)

const { status, data } = await apiInstance.getSavingsTrendApiV1SavingsTrendGet_0(
    period,
    startDate,
    endDate
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **period** | [**string**] |  | (optional) defaults to 'quarterly'|
| **startDate** | [**string**] |  | (optional) defaults to undefined|
| **endDate** | [**string**] |  | (optional) defaults to undefined|


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

