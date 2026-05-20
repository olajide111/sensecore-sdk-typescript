# BillingApi

All URIs are relative to *https://api.sensecoreai.com*

|Method | HTTP request | Description|
|------------- | ------------- | -------------|
|[**getInvoiceDetailApiV1BillingInvoiceInvoiceIdGet**](#getinvoicedetailapiv1billinginvoiceinvoiceidget) | **GET** /api/v1/billing/invoice/{invoice_id} | Get Invoice Detail|
|[**getInvoiceDetailApiV1BillingInvoiceInvoiceIdGet_0**](#getinvoicedetailapiv1billinginvoiceinvoiceidget_0) | **GET** /api/v1/billing/invoice/{invoice_id} | Get Invoice Detail|
|[**getInvoicesApiV1BillingInvoicesGet**](#getinvoicesapiv1billinginvoicesget) | **GET** /api/v1/billing/invoices | Get Invoices|
|[**getInvoicesApiV1BillingInvoicesGet_0**](#getinvoicesapiv1billinginvoicesget_0) | **GET** /api/v1/billing/invoices | Get Invoices|
|[**getMyPlanApiV1BillingMyPlanGet**](#getmyplanapiv1billingmyplanget) | **GET** /api/v1/billing/my-plan | Get current org plan details and feature access|
|[**getMyPlanApiV1BillingMyPlanGet_0**](#getmyplanapiv1billingmyplanget_0) | **GET** /api/v1/billing/my-plan | Get current org plan details and feature access|
|[**getMyPlanApiV1BillingMyPlanGet_1**](#getmyplanapiv1billingmyplanget_1) | **GET** /api/v1/billing/my-plan | Get current org plan details and feature access|
|[**getPaymentSettingsApiV1BillingPaymentSettingsGet**](#getpaymentsettingsapiv1billingpaymentsettingsget) | **GET** /api/v1/billing/payment-settings | Get Payment Settings|
|[**getPaymentSettingsApiV1BillingPaymentSettingsGet_0**](#getpaymentsettingsapiv1billingpaymentsettingsget_0) | **GET** /api/v1/billing/payment-settings | Get Payment Settings|
|[**getPaymentSettingsApiV1BillingPaymentSettingsGet_1**](#getpaymentsettingsapiv1billingpaymentsettingsget_1) | **GET** /api/v1/billing/payment-settings | Get Payment Settings|
|[**getPlanApiV1BillingPlanGet**](#getplanapiv1billingplanget) | **GET** /api/v1/billing/plan | Get Plan|
|[**getPlanApiV1BillingPlanGet_0**](#getplanapiv1billingplanget_0) | **GET** /api/v1/billing/plan | Get Plan|
|[**requestInvoiceApiV1BillingInvoicesRequestPost**](#requestinvoiceapiv1billinginvoicesrequestpost) | **POST** /api/v1/billing/invoices/request | Request Invoice|
|[**requestInvoiceApiV1BillingInvoicesRequestPost_0**](#requestinvoiceapiv1billinginvoicesrequestpost_0) | **POST** /api/v1/billing/invoices/request | Request Invoice|
|[**updatePlanApiV1BillingPlanPost**](#updateplanapiv1billingplanpost) | **POST** /api/v1/billing/plan | Update Plan|
|[**updatePlanApiV1BillingPlanPost_0**](#updateplanapiv1billingplanpost_0) | **POST** /api/v1/billing/plan | Update Plan|

# **getInvoiceDetailApiV1BillingInvoiceInvoiceIdGet**
> object getInvoiceDetailApiV1BillingInvoiceInvoiceIdGet()


### Example

```typescript
import {
    BillingApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new BillingApi(configuration);

let invoiceId: string; //Invoice ID or number (default to undefined)

const { status, data } = await apiInstance.getInvoiceDetailApiV1BillingInvoiceInvoiceIdGet(
    invoiceId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **invoiceId** | [**string**] | Invoice ID or number | defaults to undefined|


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
|**422** | Validation Error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getInvoiceDetailApiV1BillingInvoiceInvoiceIdGet_0**
> object getInvoiceDetailApiV1BillingInvoiceInvoiceIdGet_0()


### Example

```typescript
import {
    BillingApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new BillingApi(configuration);

let invoiceId: string; //Invoice ID or number (default to undefined)

const { status, data } = await apiInstance.getInvoiceDetailApiV1BillingInvoiceInvoiceIdGet_0(
    invoiceId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **invoiceId** | [**string**] | Invoice ID or number | defaults to undefined|


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
|**422** | Validation Error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getInvoicesApiV1BillingInvoicesGet**
> Array<any> getInvoicesApiV1BillingInvoicesGet()


### Example

```typescript
import {
    BillingApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new BillingApi(configuration);

const { status, data } = await apiInstance.getInvoicesApiV1BillingInvoicesGet();
```

### Parameters
This endpoint does not have any parameters.


### Return type

**Array<any>**

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

# **getInvoicesApiV1BillingInvoicesGet_0**
> Array<any> getInvoicesApiV1BillingInvoicesGet_0()


### Example

```typescript
import {
    BillingApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new BillingApi(configuration);

const { status, data } = await apiInstance.getInvoicesApiV1BillingInvoicesGet_0();
```

### Parameters
This endpoint does not have any parameters.


### Return type

**Array<any>**

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

# **getMyPlanApiV1BillingMyPlanGet**
> object getMyPlanApiV1BillingMyPlanGet()


### Example

```typescript
import {
    BillingApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new BillingApi(configuration);

const { status, data } = await apiInstance.getMyPlanApiV1BillingMyPlanGet();
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

# **getMyPlanApiV1BillingMyPlanGet_0**
> object getMyPlanApiV1BillingMyPlanGet_0()


### Example

```typescript
import {
    BillingApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new BillingApi(configuration);

const { status, data } = await apiInstance.getMyPlanApiV1BillingMyPlanGet_0();
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

# **getMyPlanApiV1BillingMyPlanGet_1**
> object getMyPlanApiV1BillingMyPlanGet_1()


### Example

```typescript
import {
    BillingApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new BillingApi(configuration);

const { status, data } = await apiInstance.getMyPlanApiV1BillingMyPlanGet_1();
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

# **getPaymentSettingsApiV1BillingPaymentSettingsGet**
> object getPaymentSettingsApiV1BillingPaymentSettingsGet()


### Example

```typescript
import {
    BillingApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new BillingApi(configuration);

const { status, data } = await apiInstance.getPaymentSettingsApiV1BillingPaymentSettingsGet();
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

# **getPaymentSettingsApiV1BillingPaymentSettingsGet_0**
> object getPaymentSettingsApiV1BillingPaymentSettingsGet_0()


### Example

```typescript
import {
    BillingApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new BillingApi(configuration);

const { status, data } = await apiInstance.getPaymentSettingsApiV1BillingPaymentSettingsGet_0();
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

# **getPaymentSettingsApiV1BillingPaymentSettingsGet_1**
> object getPaymentSettingsApiV1BillingPaymentSettingsGet_1()


### Example

```typescript
import {
    BillingApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new BillingApi(configuration);

const { status, data } = await apiInstance.getPaymentSettingsApiV1BillingPaymentSettingsGet_1();
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

# **getPlanApiV1BillingPlanGet**
> object getPlanApiV1BillingPlanGet()


### Example

```typescript
import {
    BillingApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new BillingApi(configuration);

const { status, data } = await apiInstance.getPlanApiV1BillingPlanGet();
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

# **getPlanApiV1BillingPlanGet_0**
> object getPlanApiV1BillingPlanGet_0()


### Example

```typescript
import {
    BillingApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new BillingApi(configuration);

const { status, data } = await apiInstance.getPlanApiV1BillingPlanGet_0();
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

# **requestInvoiceApiV1BillingInvoicesRequestPost**
> object requestInvoiceApiV1BillingInvoicesRequestPost(body)


### Example

```typescript
import {
    BillingApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new BillingApi(configuration);

let body: object; //

const { status, data } = await apiInstance.requestInvoiceApiV1BillingInvoicesRequestPost(
    body
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **body** | **object**|  | |


### Return type

**object**

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

# **requestInvoiceApiV1BillingInvoicesRequestPost_0**
> object requestInvoiceApiV1BillingInvoicesRequestPost_0(body)


### Example

```typescript
import {
    BillingApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new BillingApi(configuration);

let body: object; //

const { status, data } = await apiInstance.requestInvoiceApiV1BillingInvoicesRequestPost_0(
    body
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **body** | **object**|  | |


### Return type

**object**

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

# **updatePlanApiV1BillingPlanPost**
> object updatePlanApiV1BillingPlanPost(body)


### Example

```typescript
import {
    BillingApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new BillingApi(configuration);

let body: object; //

const { status, data } = await apiInstance.updatePlanApiV1BillingPlanPost(
    body
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **body** | **object**|  | |


### Return type

**object**

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

# **updatePlanApiV1BillingPlanPost_0**
> object updatePlanApiV1BillingPlanPost_0(body)


### Example

```typescript
import {
    BillingApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new BillingApi(configuration);

let body: object; //

const { status, data } = await apiInstance.updatePlanApiV1BillingPlanPost_0(
    body
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **body** | **object**|  | |


### Return type

**object**

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

