# UsageApi

All URIs are relative to *https://api.sensecoreai.com*

|Method | HTTP request | Description|
|------------- | ------------- | -------------|
|[**adminOrgDetailEndpointApiV1UsageAdminOrgOrgIdGet**](#adminorgdetailendpointapiv1usageadminorgorgidget) | **GET** /api/v1/usage/admin/org/{org_id} | Admin Org Detail Endpoint|
|[**adminOrgDetailEndpointApiV1UsageAdminOrgOrgIdGet_0**](#adminorgdetailendpointapiv1usageadminorgorgidget_0) | **GET** /api/v1/usage/admin/org/{org_id} | Admin Org Detail Endpoint|
|[**adminOverviewEndpointApiV1UsageAdminOverviewGet**](#adminoverviewendpointapiv1usageadminoverviewget) | **GET** /api/v1/usage/admin/overview | Admin Overview Endpoint|
|[**adminOverviewEndpointApiV1UsageAdminOverviewGet_0**](#adminoverviewendpointapiv1usageadminoverviewget_0) | **GET** /api/v1/usage/admin/overview | Admin Overview Endpoint|
|[**myHistoryEndpointApiV1UsageMeHistoryGet**](#myhistoryendpointapiv1usagemehistoryget) | **GET** /api/v1/usage/me/history | My History Endpoint|
|[**myHistoryEndpointApiV1UsageMeHistoryGet_0**](#myhistoryendpointapiv1usagemehistoryget_0) | **GET** /api/v1/usage/me/history | My History Endpoint|
|[**myUsageEndpointApiV1UsageMeGet**](#myusageendpointapiv1usagemeget) | **GET** /api/v1/usage/me | My Usage Endpoint|
|[**myUsageEndpointApiV1UsageMeGet_0**](#myusageendpointapiv1usagemeget_0) | **GET** /api/v1/usage/me | My Usage Endpoint|

# **adminOrgDetailEndpointApiV1UsageAdminOrgOrgIdGet**
> any adminOrgDetailEndpointApiV1UsageAdminOrgOrgIdGet()

Drill-down on any single organisation. Returns the same shape as /me plus the org\'s display name and 30-day history.

### Example

```typescript
import {
    UsageApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new UsageApi(configuration);

let orgId: string; // (default to undefined)

const { status, data } = await apiInstance.adminOrgDetailEndpointApiV1UsageAdminOrgOrgIdGet(
    orgId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **orgId** | [**string**] |  | defaults to undefined|


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

# **adminOrgDetailEndpointApiV1UsageAdminOrgOrgIdGet_0**
> any adminOrgDetailEndpointApiV1UsageAdminOrgOrgIdGet_0()

Drill-down on any single organisation. Returns the same shape as /me plus the org\'s display name and 30-day history.

### Example

```typescript
import {
    UsageApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new UsageApi(configuration);

let orgId: string; // (default to undefined)

const { status, data } = await apiInstance.adminOrgDetailEndpointApiV1UsageAdminOrgOrgIdGet_0(
    orgId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **orgId** | [**string**] |  | defaults to undefined|


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

# **adminOverviewEndpointApiV1UsageAdminOverviewGet**
> any adminOverviewEndpointApiV1UsageAdminOverviewGet()

All-orgs roll-up. Aggregate KPIs filtered to attributed traffic only (excludes unauthenticated noise) + per-org table with status flags (ok / warning / over).

### Example

```typescript
import {
    UsageApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new UsageApi(configuration);

const { status, data } = await apiInstance.adminOverviewEndpointApiV1UsageAdminOverviewGet();
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

# **adminOverviewEndpointApiV1UsageAdminOverviewGet_0**
> any adminOverviewEndpointApiV1UsageAdminOverviewGet_0()

All-orgs roll-up. Aggregate KPIs filtered to attributed traffic only (excludes unauthenticated noise) + per-org table with status flags (ok / warning / over).

### Example

```typescript
import {
    UsageApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new UsageApi(configuration);

const { status, data } = await apiInstance.adminOverviewEndpointApiV1UsageAdminOverviewGet_0();
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

# **myHistoryEndpointApiV1UsageMeHistoryGet**
> any myHistoryEndpointApiV1UsageMeHistoryGet()

Daily call counts for the last N days (1-90), zero-filled.

### Example

```typescript
import {
    UsageApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new UsageApi(configuration);

let days: number; // (optional) (default to 30)
let xAPIKey: string; // (optional) (default to undefined)

const { status, data } = await apiInstance.myHistoryEndpointApiV1UsageMeHistoryGet(
    days,
    xAPIKey
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **days** | [**number**] |  | (optional) defaults to 30|
| **xAPIKey** | [**string**] |  | (optional) defaults to undefined|


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

# **myHistoryEndpointApiV1UsageMeHistoryGet_0**
> any myHistoryEndpointApiV1UsageMeHistoryGet_0()

Daily call counts for the last N days (1-90), zero-filled.

### Example

```typescript
import {
    UsageApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new UsageApi(configuration);

let days: number; // (optional) (default to 30)
let xAPIKey: string; // (optional) (default to undefined)

const { status, data } = await apiInstance.myHistoryEndpointApiV1UsageMeHistoryGet_0(
    days,
    xAPIKey
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **days** | [**number**] |  | (optional) defaults to 30|
| **xAPIKey** | [**string**] |  | (optional) defaults to undefined|


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

# **myUsageEndpointApiV1UsageMeGet**
> any myUsageEndpointApiV1UsageMeGet()

Current calendar-month usage summary for the caller\'s organisation.  Returns plan_key, max_api_calls (None if unlimited), calls_this_month, percent_used, calls_today, error_rate_pct, p95_latency_ms, and the top 10 endpoints this month.

### Example

```typescript
import {
    UsageApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new UsageApi(configuration);

let xAPIKey: string; // (optional) (default to undefined)

const { status, data } = await apiInstance.myUsageEndpointApiV1UsageMeGet(
    xAPIKey
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **xAPIKey** | [**string**] |  | (optional) defaults to undefined|


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

# **myUsageEndpointApiV1UsageMeGet_0**
> any myUsageEndpointApiV1UsageMeGet_0()

Current calendar-month usage summary for the caller\'s organisation.  Returns plan_key, max_api_calls (None if unlimited), calls_this_month, percent_used, calls_today, error_rate_pct, p95_latency_ms, and the top 10 endpoints this month.

### Example

```typescript
import {
    UsageApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new UsageApi(configuration);

let xAPIKey: string; // (optional) (default to undefined)

const { status, data } = await apiInstance.myUsageEndpointApiV1UsageMeGet_0(
    xAPIKey
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **xAPIKey** | [**string**] |  | (optional) defaults to undefined|


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

