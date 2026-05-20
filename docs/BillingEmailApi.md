# BillingEmailApi

All URIs are relative to *https://api.sensecoreai.com*

|Method | HTTP request | Description|
|------------- | ------------- | -------------|
|[**emailAllInvoicesApiV1BillingInvoicesEmailAllPost**](#emailallinvoicesapiv1billinginvoicesemailallpost) | **POST** /api/v1/billing/invoices/email-all | Email All Invoices|
|[**emailAllInvoicesApiV1BillingInvoicesEmailAllPost_0**](#emailallinvoicesapiv1billinginvoicesemailallpost_0) | **POST** /api/v1/billing/invoices/email-all | Email All Invoices|
|[**emailInvoiceApiV1BillingInvoicesInvoiceIdEmailPost**](#emailinvoiceapiv1billinginvoicesinvoiceidemailpost) | **POST** /api/v1/billing/invoices/{invoice_id}/email | Email Invoice|
|[**emailInvoiceApiV1BillingInvoicesInvoiceIdEmailPost_0**](#emailinvoiceapiv1billinginvoicesinvoiceidemailpost_0) | **POST** /api/v1/billing/invoices/{invoice_id}/email | Email Invoice|

# **emailAllInvoicesApiV1BillingInvoicesEmailAllPost**
> object emailAllInvoicesApiV1BillingInvoicesEmailAllPost()

Email all invoices for the current organisation as a single ZIP of PDFs. Body (optional): {\"recipient_email\": \"...\", \"status_filters\": [...], \"date_from\": \"...\", \"date_to\": \"...\"}

### Example

```typescript
import {
    BillingEmailApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new BillingEmailApi(configuration);

let body: object; // (optional)

const { status, data } = await apiInstance.emailAllInvoicesApiV1BillingInvoicesEmailAllPost(
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

# **emailAllInvoicesApiV1BillingInvoicesEmailAllPost_0**
> object emailAllInvoicesApiV1BillingInvoicesEmailAllPost_0()

Email all invoices for the current organisation as a single ZIP of PDFs. Body (optional): {\"recipient_email\": \"...\", \"status_filters\": [...], \"date_from\": \"...\", \"date_to\": \"...\"}

### Example

```typescript
import {
    BillingEmailApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new BillingEmailApi(configuration);

let body: object; // (optional)

const { status, data } = await apiInstance.emailAllInvoicesApiV1BillingInvoicesEmailAllPost_0(
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

# **emailInvoiceApiV1BillingInvoicesInvoiceIdEmailPost**
> object emailInvoiceApiV1BillingInvoicesInvoiceIdEmailPost()

Email a single invoice as PDF attachment. Delegates to send_invoice_email() — same branded template as status-change emails. Body (optional): {\"recipient_email\": \"...\", \"cc_emails\": [\"...\"], \"message\": \"...\", \"copy_to_sender\": true}

### Example

```typescript
import {
    BillingEmailApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new BillingEmailApi(configuration);

let invoiceId: string; //Invoice ID or number (default to undefined)
let body: object; // (optional)

const { status, data } = await apiInstance.emailInvoiceApiV1BillingInvoicesInvoiceIdEmailPost(
    invoiceId,
    body
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **body** | **object**|  | |
| **invoiceId** | [**string**] | Invoice ID or number | defaults to undefined|


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

# **emailInvoiceApiV1BillingInvoicesInvoiceIdEmailPost_0**
> object emailInvoiceApiV1BillingInvoicesInvoiceIdEmailPost_0()

Email a single invoice as PDF attachment. Delegates to send_invoice_email() — same branded template as status-change emails. Body (optional): {\"recipient_email\": \"...\", \"cc_emails\": [\"...\"], \"message\": \"...\", \"copy_to_sender\": true}

### Example

```typescript
import {
    BillingEmailApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new BillingEmailApi(configuration);

let invoiceId: string; //Invoice ID or number (default to undefined)
let body: object; // (optional)

const { status, data } = await apiInstance.emailInvoiceApiV1BillingInvoicesInvoiceIdEmailPost_0(
    invoiceId,
    body
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **body** | **object**|  | |
| **invoiceId** | [**string**] | Invoice ID or number | defaults to undefined|


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

