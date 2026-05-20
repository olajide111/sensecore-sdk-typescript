# OverviewApi

All URIs are relative to *https://api.sensecoreai.com*

|Method | HTTP request | Description|
|------------- | ------------- | -------------|
|[**getOverviewApiV1OverviewDashboardGet**](#getoverviewapiv1overviewdashboardget) | **GET** /api/v1/overview/dashboard | Get Overview|
|[**getOverviewApiV1OverviewDashboardGet_0**](#getoverviewapiv1overviewdashboardget_0) | **GET** /api/v1/overview/dashboard | Get Overview|

# **getOverviewApiV1OverviewDashboardGet**
> any getOverviewApiV1OverviewDashboardGet()

Returns overview dashboard data. Real data from DB when available, demo fallback when not.

### Example

```typescript
import {
    OverviewApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new OverviewApi(configuration);

const { status, data } = await apiInstance.getOverviewApiV1OverviewDashboardGet();
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

# **getOverviewApiV1OverviewDashboardGet_0**
> any getOverviewApiV1OverviewDashboardGet_0()

Returns overview dashboard data. Real data from DB when available, demo fallback when not.

### Example

```typescript
import {
    OverviewApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new OverviewApi(configuration);

const { status, data } = await apiInstance.getOverviewApiV1OverviewDashboardGet_0();
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

