# AdminApi

All URIs are relative to *https://api.sensecoreai.com*

|Method | HTTP request | Description|
|------------- | ------------- | -------------|
|[**activateOrgApiV1AdminOrganisationsOrgIdActivatePatch**](#activateorgapiv1adminorganisationsorgidactivatepatch) | **PATCH** /api/v1/admin/organisations/{org_id}/activate | Activate Org|
|[**activateOrgApiV1AdminOrganisationsOrgIdActivatePatch_0**](#activateorgapiv1adminorganisationsorgidactivatepatch_0) | **PATCH** /api/v1/admin/organisations/{org_id}/activate | Activate Org|
|[**activateUserApiV1AdminUsersUserIdActivatePatch**](#activateuserapiv1adminusersuseridactivatepatch) | **PATCH** /api/v1/admin/users/{user_id}/activate | Activate User|
|[**activateUserApiV1AdminUsersUserIdActivatePatch_0**](#activateuserapiv1adminusersuseridactivatepatch_0) | **PATCH** /api/v1/admin/users/{user_id}/activate | Activate User|
|[**adminCreateInvoiceApiV1AdminBillingInvoicePost**](#admincreateinvoiceapiv1adminbillinginvoicepost) | **POST** /api/v1/admin/billing/invoice | Generate invoice|
|[**adminCreateInvoiceApiV1AdminBillingInvoicePost_0**](#admincreateinvoiceapiv1adminbillinginvoicepost_0) | **POST** /api/v1/admin/billing/invoice | Generate invoice|
|[**adminFilterInvoicesApiV1AdminBillingInvoicesGet**](#adminfilterinvoicesapiv1adminbillinginvoicesget) | **GET** /api/v1/admin/billing/invoices | Filter invoices|
|[**adminFilterInvoicesApiV1AdminBillingInvoicesGet_0**](#adminfilterinvoicesapiv1adminbillinginvoicesget_0) | **GET** /api/v1/admin/billing/invoices | Filter invoices|
|[**adminListAllInvoicesApiV1AdminBillingAllInvoicesGet**](#adminlistallinvoicesapiv1adminbillingallinvoicesget) | **GET** /api/v1/admin/billing/all-invoices | List all invoices|
|[**adminListAllInvoicesApiV1AdminBillingAllInvoicesGet_0**](#adminlistallinvoicesapiv1adminbillingallinvoicesget_0) | **GET** /api/v1/admin/billing/all-invoices | List all invoices|
|[**adminUpdateInvoiceApiV1AdminBillingInvoiceInvoiceIdPatch**](#adminupdateinvoiceapiv1adminbillinginvoiceinvoiceidpatch) | **PATCH** /api/v1/admin/billing/invoice/{invoice_id} | Update invoice|
|[**adminUpdateInvoiceApiV1AdminBillingInvoiceInvoiceIdPatch_0**](#adminupdateinvoiceapiv1adminbillinginvoiceinvoiceidpatch_0) | **PATCH** /api/v1/admin/billing/invoice/{invoice_id} | Update invoice|
|[**adminUpdateInvoiceStatusApiV1AdminBillingInvoiceStatusPost**](#adminupdateinvoicestatusapiv1adminbillinginvoicestatuspost) | **POST** /api/v1/admin/billing/invoice-status | Update invoice status|
|[**adminUpdateInvoiceStatusApiV1AdminBillingInvoiceStatusPost_0**](#adminupdateinvoicestatusapiv1adminbillinginvoicestatuspost_0) | **POST** /api/v1/admin/billing/invoice-status | Update invoice status|
|[**billingOverviewApiV1AdminBillingOverviewGet**](#billingoverviewapiv1adminbillingoverviewget) | **GET** /api/v1/admin/billing/overview | Billing Overview|
|[**billingOverviewApiV1AdminBillingOverviewGet_0**](#billingoverviewapiv1adminbillingoverviewget_0) | **GET** /api/v1/admin/billing/overview | Billing Overview|
|[**changeUserRoleApiV1AdminUsersUserIdRolePatch**](#changeuserroleapiv1adminusersuseridrolepatch) | **PATCH** /api/v1/admin/users/{user_id}/role | Change user role|
|[**changeUserRoleApiV1AdminUsersUserIdRolePatch_0**](#changeuserroleapiv1adminusersuseridrolepatch_0) | **PATCH** /api/v1/admin/users/{user_id}/role | Change user role|
|[**createOrganisationApiV1AdminOrganisationsPost**](#createorganisationapiv1adminorganisationspost) | **POST** /api/v1/admin/organisations | Create organisation|
|[**createOrganisationApiV1AdminOrganisationsPost_0**](#createorganisationapiv1adminorganisationspost_0) | **POST** /api/v1/admin/organisations | Create organisation|
|[**createTrainingJobApiV1AdminMlopsTrainingJobsPost**](#createtrainingjobapiv1adminmlopstrainingjobspost) | **POST** /api/v1/admin/mlops/training-jobs | Create Training Job|
|[**createUserApiV1AdminUsersPost**](#createuserapiv1adminuserspost) | **POST** /api/v1/admin/users | Create a new user|
|[**createUserApiV1AdminUsersPost_0**](#createuserapiv1adminuserspost_0) | **POST** /api/v1/admin/users | Create a new user|
|[**deactivateUserApiV1AdminUsersUserIdDeactivatePatch**](#deactivateuserapiv1adminusersuseriddeactivatepatch) | **PATCH** /api/v1/admin/users/{user_id}/deactivate | Deactivate User|
|[**deactivateUserApiV1AdminUsersUserIdDeactivatePatch_0**](#deactivateuserapiv1adminusersuseriddeactivatepatch_0) | **PATCH** /api/v1/admin/users/{user_id}/deactivate | Deactivate User|
|[**deleteUserApiV1AdminUsersUserIdDelete**](#deleteuserapiv1adminusersuseriddelete) | **DELETE** /api/v1/admin/users/{user_id} | Delete User|
|[**deleteUserApiV1AdminUsersUserIdDelete_0**](#deleteuserapiv1adminusersuseriddelete_0) | **DELETE** /api/v1/admin/users/{user_id} | Delete User|
|[**emailSingleInvoiceApiV1AdminBillingInvoicesInvoiceNumberEmailPost**](#emailsingleinvoiceapiv1adminbillinginvoicesinvoicenumberemailpost) | **POST** /api/v1/admin/billing/invoices/{invoice_number}/email | Email Single Invoice|
|[**emailSingleInvoiceApiV1AdminBillingInvoicesInvoiceNumberEmailPost_0**](#emailsingleinvoiceapiv1adminbillinginvoicesinvoicenumberemailpost_0) | **POST** /api/v1/admin/billing/invoices/{invoice_number}/email | Email Single Invoice|
|[**getAllActivityApiV1AdminActivityGet**](#getallactivityapiv1adminactivityget) | **GET** /api/v1/admin/activity | Get All Activity|
|[**getAllActivityApiV1AdminActivityGet_0**](#getallactivityapiv1adminactivityget_0) | **GET** /api/v1/admin/activity | Get All Activity|
|[**getBillingEmailLogApiV1AdminBillingEmailLogGet**](#getbillingemaillogapiv1adminbillingemaillogget) | **GET** /api/v1/admin/billing/email-log | Billing email log with filters|
|[**getBillingEmailLogApiV1AdminBillingEmailLogGet_0**](#getbillingemaillogapiv1adminbillingemaillogget_0) | **GET** /api/v1/admin/billing/email-log | Billing email log with filters|
|[**getBillingSettingsApiV1AdminBillingSettingsGet**](#getbillingsettingsapiv1adminbillingsettingsget) | **GET** /api/v1/admin/billing/settings | Get Billing Settings|
|[**getBillingSettingsApiV1AdminBillingSettingsGet_0**](#getbillingsettingsapiv1adminbillingsettingsget_0) | **GET** /api/v1/admin/billing/settings | Get Billing Settings|
|[**getBrandingApiV1AdminBrandingGet**](#getbrandingapiv1adminbrandingget) | **GET** /api/v1/admin/branding | Get platform branding|
|[**getBrandingApiV1AdminBrandingGet_0**](#getbrandingapiv1adminbrandingget_0) | **GET** /api/v1/admin/branding | Get platform branding|
|[**getEmailLogSimpleApiV1AdminEmailLogGet**](#getemaillogsimpleapiv1adminemaillogget) | **GET** /api/v1/admin/email-log | Get email send log|
|[**getEmailLogSimpleApiV1AdminEmailLogGet_0**](#getemaillogsimpleapiv1adminemaillogget_0) | **GET** /api/v1/admin/email-log | Get email send log|
|[**getModelPerformanceApiV1AdminMlopsPerformanceGet**](#getmodelperformanceapiv1adminmlopsperformanceget) | **GET** /api/v1/admin/mlops/performance | Get Model Performance|
|[**getPaymentsApiV1AdminBillingInvoicesInvoiceNumberPaymentsGet**](#getpaymentsapiv1adminbillinginvoicesinvoicenumberpaymentsget) | **GET** /api/v1/admin/billing/invoices/{invoice_number}/payments | Get Payments|
|[**getPaymentsApiV1AdminBillingInvoicesInvoiceNumberPaymentsGet_0**](#getpaymentsapiv1adminbillinginvoicesinvoicenumberpaymentsget_0) | **GET** /api/v1/admin/billing/invoices/{invoice_number}/payments | Get Payments|
|[**getPlanConfigsApiV1AdminPlanConfigGet**](#getplanconfigsapiv1adminplanconfigget) | **GET** /api/v1/admin/plan-config | Get all plan configs|
|[**getPlanConfigsApiV1AdminPlanConfigGet_0**](#getplanconfigsapiv1adminplanconfigget_0) | **GET** /api/v1/admin/plan-config | Get all plan configs|
|[**getUserActivityApiV1AdminUsersUserIdActivityGet**](#getuseractivityapiv1adminusersuseridactivityget) | **GET** /api/v1/admin/users/{user_id}/activity | Get User Activity|
|[**getUserActivityApiV1AdminUsersUserIdActivityGet_0**](#getuseractivityapiv1adminusersuseridactivityget_0) | **GET** /api/v1/admin/users/{user_id}/activity | Get User Activity|
|[**listCheckpointsDetailedApiV1AdminMlopsCheckpointsGet**](#listcheckpointsdetailedapiv1adminmlopscheckpointsget) | **GET** /api/v1/admin/mlops/checkpoints | List Checkpoints Detailed|
|[**listOrganisationsApiV1AdminOrganisationsGet**](#listorganisationsapiv1adminorganisationsget) | **GET** /api/v1/admin/organisations | List all organisations|
|[**listOrganisationsApiV1AdminOrganisationsGet_0**](#listorganisationsapiv1adminorganisationsget_0) | **GET** /api/v1/admin/organisations | List all organisations|
|[**listTrainingJobsApiV1AdminMlopsTrainingJobsGet**](#listtrainingjobsapiv1adminmlopstrainingjobsget) | **GET** /api/v1/admin/mlops/training-jobs | List Training Jobs|
|[**listUsersApiV1AdminUsersGet**](#listusersapiv1adminusersget) | **GET** /api/v1/admin/users | List all users|
|[**listUsersApiV1AdminUsersGet_0**](#listusersapiv1adminusersget_0) | **GET** /api/v1/admin/users | List all users|
|[**mlopsStatusApiV1AdminMlopsStatusGet**](#mlopsstatusapiv1adminmlopsstatusget) | **GET** /api/v1/admin/mlops/status | MLOps model status|
|[**mlopsStatusApiV1AdminMlopsStatusGet_0**](#mlopsstatusapiv1adminmlopsstatusget_0) | **GET** /api/v1/admin/mlops/status | MLOps model status|
|[**recordPaymentApiV1AdminBillingInvoicesInvoiceNumberPaymentsPost**](#recordpaymentapiv1adminbillinginvoicesinvoicenumberpaymentspost) | **POST** /api/v1/admin/billing/invoices/{invoice_number}/payments | Record Payment|
|[**recordPaymentApiV1AdminBillingInvoicesInvoiceNumberPaymentsPost_0**](#recordpaymentapiv1adminbillinginvoicesinvoicenumberpaymentspost_0) | **POST** /api/v1/admin/billing/invoices/{invoice_number}/payments | Record Payment|
|[**saveBillingSettingsApiV1AdminBillingSettingsPost**](#savebillingsettingsapiv1adminbillingsettingspost) | **POST** /api/v1/admin/billing/settings | Save Billing Settings|
|[**saveBillingSettingsApiV1AdminBillingSettingsPost_0**](#savebillingsettingsapiv1adminbillingsettingspost_0) | **POST** /api/v1/admin/billing/settings | Save Billing Settings|
|[**setOrgPlanApiV1AdminOrganisationsOrgIdSetPlanPatch**](#setorgplanapiv1adminorganisationsorgidsetplanpatch) | **PATCH** /api/v1/admin/organisations/{org_id}/set-plan | Set Org Plan|
|[**setOrgPlanApiV1AdminOrganisationsOrgIdSetPlanPatch_0**](#setorgplanapiv1adminorganisationsorgidsetplanpatch_0) | **PATCH** /api/v1/admin/organisations/{org_id}/set-plan | Set Org Plan|
|[**setRetrainScheduleApiV1AdminMlopsSchedulePost**](#setretrainscheduleapiv1adminmlopsschedulepost) | **POST** /api/v1/admin/mlops/schedule | Set Retrain Schedule|
|[**suspendOrgApiV1AdminOrganisationsOrgIdSuspendPatch**](#suspendorgapiv1adminorganisationsorgidsuspendpatch) | **PATCH** /api/v1/admin/organisations/{org_id}/suspend | Suspend Org|
|[**suspendOrgApiV1AdminOrganisationsOrgIdSuspendPatch_0**](#suspendorgapiv1adminorganisationsorgidsuspendpatch_0) | **PATCH** /api/v1/admin/organisations/{org_id}/suspend | Suspend Org|
|[**triggerRetrainApiV1AdminMlopsRetrainPost**](#triggerretrainapiv1adminmlopsretrainpost) | **POST** /api/v1/admin/mlops/retrain | Trigger model retrain|
|[**triggerRetrainApiV1AdminMlopsRetrainPost_0**](#triggerretrainapiv1adminmlopsretrainpost_0) | **POST** /api/v1/admin/mlops/retrain | Trigger model retrain|
|[**updateBrandingApiV1AdminBrandingPatch**](#updatebrandingapiv1adminbrandingpatch) | **PATCH** /api/v1/admin/branding | Update platform branding|
|[**updateBrandingApiV1AdminBrandingPatch_0**](#updatebrandingapiv1adminbrandingpatch_0) | **PATCH** /api/v1/admin/branding | Update platform branding|
|[**updatePlanConfigApiV1AdminPlanConfigPlanKeyPatch**](#updateplanconfigapiv1adminplanconfigplankeypatch) | **PATCH** /api/v1/admin/plan-config/{plan_key} | Update plan config|
|[**updatePlanConfigApiV1AdminPlanConfigPlanKeyPatch_0**](#updateplanconfigapiv1adminplanconfigplankeypatch_0) | **PATCH** /api/v1/admin/plan-config/{plan_key} | Update plan config|
|[**updateTrainingJobApiV1AdminMlopsTrainingJobsJobIdPatch**](#updatetrainingjobapiv1adminmlopstrainingjobsjobidpatch) | **PATCH** /api/v1/admin/mlops/training-jobs/{job_id} | Update Training Job|
|[**voidPaymentApiV1AdminBillingPaymentsPaymentIdVoidPost**](#voidpaymentapiv1adminbillingpaymentspaymentidvoidpost) | **POST** /api/v1/admin/billing/payments/{payment_id}/void | Void Payment|
|[**voidPaymentApiV1AdminBillingPaymentsPaymentIdVoidPost_0**](#voidpaymentapiv1adminbillingpaymentspaymentidvoidpost_0) | **POST** /api/v1/admin/billing/payments/{payment_id}/void | Void Payment|

# **activateOrgApiV1AdminOrganisationsOrgIdActivatePatch**
> { [key: string]: string | null; } activateOrgApiV1AdminOrganisationsOrgIdActivatePatch()


### Example

```typescript
import {
    AdminApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new AdminApi(configuration);

let orgId: string; //Organisation ID (default to undefined)

const { status, data } = await apiInstance.activateOrgApiV1AdminOrganisationsOrgIdActivatePatch(
    orgId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **orgId** | [**string**] | Organisation ID | defaults to undefined|


### Return type

**{ [key: string]: string | null; }**

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

# **activateOrgApiV1AdminOrganisationsOrgIdActivatePatch_0**
> { [key: string]: string | null; } activateOrgApiV1AdminOrganisationsOrgIdActivatePatch_0()


### Example

```typescript
import {
    AdminApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new AdminApi(configuration);

let orgId: string; //Organisation ID (default to undefined)

const { status, data } = await apiInstance.activateOrgApiV1AdminOrganisationsOrgIdActivatePatch_0(
    orgId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **orgId** | [**string**] | Organisation ID | defaults to undefined|


### Return type

**{ [key: string]: string | null; }**

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

# **activateUserApiV1AdminUsersUserIdActivatePatch**
> { [key: string]: string | null; } activateUserApiV1AdminUsersUserIdActivatePatch()


### Example

```typescript
import {
    AdminApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new AdminApi(configuration);

let userId: string; //User ID (default to undefined)

const { status, data } = await apiInstance.activateUserApiV1AdminUsersUserIdActivatePatch(
    userId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **userId** | [**string**] | User ID | defaults to undefined|


### Return type

**{ [key: string]: string | null; }**

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

# **activateUserApiV1AdminUsersUserIdActivatePatch_0**
> { [key: string]: string | null; } activateUserApiV1AdminUsersUserIdActivatePatch_0()


### Example

```typescript
import {
    AdminApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new AdminApi(configuration);

let userId: string; //User ID (default to undefined)

const { status, data } = await apiInstance.activateUserApiV1AdminUsersUserIdActivatePatch_0(
    userId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **userId** | [**string**] | User ID | defaults to undefined|


### Return type

**{ [key: string]: string | null; }**

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

# **adminCreateInvoiceApiV1AdminBillingInvoicePost**
> object adminCreateInvoiceApiV1AdminBillingInvoicePost(createInvoiceRequest)


### Example

```typescript
import {
    AdminApi,
    Configuration,
    CreateInvoiceRequest
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new AdminApi(configuration);

let createInvoiceRequest: CreateInvoiceRequest; //

const { status, data } = await apiInstance.adminCreateInvoiceApiV1AdminBillingInvoicePost(
    createInvoiceRequest
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **createInvoiceRequest** | **CreateInvoiceRequest**|  | |


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

# **adminCreateInvoiceApiV1AdminBillingInvoicePost_0**
> object adminCreateInvoiceApiV1AdminBillingInvoicePost_0(createInvoiceRequest)


### Example

```typescript
import {
    AdminApi,
    Configuration,
    CreateInvoiceRequest
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new AdminApi(configuration);

let createInvoiceRequest: CreateInvoiceRequest; //

const { status, data } = await apiInstance.adminCreateInvoiceApiV1AdminBillingInvoicePost_0(
    createInvoiceRequest
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **createInvoiceRequest** | **CreateInvoiceRequest**|  | |


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

# **adminFilterInvoicesApiV1AdminBillingInvoicesGet**
> Array<any> adminFilterInvoicesApiV1AdminBillingInvoicesGet()


### Example

```typescript
import {
    AdminApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new AdminApi(configuration);

let status: string; //Filter by invoice status (optional) (default to undefined)
let orgId: string; //Filter by organisation ID (optional) (default to undefined)
let fromDate: string; //Start date (YYYY-MM-DD) (optional) (default to undefined)
let toDate: string; //End date (YYYY-MM-DD) (optional) (default to undefined)

const { status, data } = await apiInstance.adminFilterInvoicesApiV1AdminBillingInvoicesGet(
    status,
    orgId,
    fromDate,
    toDate
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **status** | [**string**] | Filter by invoice status | (optional) defaults to undefined|
| **orgId** | [**string**] | Filter by organisation ID | (optional) defaults to undefined|
| **fromDate** | [**string**] | Start date (YYYY-MM-DD) | (optional) defaults to undefined|
| **toDate** | [**string**] | End date (YYYY-MM-DD) | (optional) defaults to undefined|


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
|**422** | Validation Error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **adminFilterInvoicesApiV1AdminBillingInvoicesGet_0**
> Array<any> adminFilterInvoicesApiV1AdminBillingInvoicesGet_0()


### Example

```typescript
import {
    AdminApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new AdminApi(configuration);

let status: string; //Filter by invoice status (optional) (default to undefined)
let orgId: string; //Filter by organisation ID (optional) (default to undefined)
let fromDate: string; //Start date (YYYY-MM-DD) (optional) (default to undefined)
let toDate: string; //End date (YYYY-MM-DD) (optional) (default to undefined)

const { status, data } = await apiInstance.adminFilterInvoicesApiV1AdminBillingInvoicesGet_0(
    status,
    orgId,
    fromDate,
    toDate
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **status** | [**string**] | Filter by invoice status | (optional) defaults to undefined|
| **orgId** | [**string**] | Filter by organisation ID | (optional) defaults to undefined|
| **fromDate** | [**string**] | Start date (YYYY-MM-DD) | (optional) defaults to undefined|
| **toDate** | [**string**] | End date (YYYY-MM-DD) | (optional) defaults to undefined|


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
|**422** | Validation Error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **adminListAllInvoicesApiV1AdminBillingAllInvoicesGet**
> Array<any> adminListAllInvoicesApiV1AdminBillingAllInvoicesGet()


### Example

```typescript
import {
    AdminApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new AdminApi(configuration);

const { status, data } = await apiInstance.adminListAllInvoicesApiV1AdminBillingAllInvoicesGet();
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

# **adminListAllInvoicesApiV1AdminBillingAllInvoicesGet_0**
> Array<any> adminListAllInvoicesApiV1AdminBillingAllInvoicesGet_0()


### Example

```typescript
import {
    AdminApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new AdminApi(configuration);

const { status, data } = await apiInstance.adminListAllInvoicesApiV1AdminBillingAllInvoicesGet_0();
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

# **adminUpdateInvoiceApiV1AdminBillingInvoiceInvoiceIdPatch**
> object adminUpdateInvoiceApiV1AdminBillingInvoiceInvoiceIdPatch(createInvoiceRequest)


### Example

```typescript
import {
    AdminApi,
    Configuration,
    CreateInvoiceRequest
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new AdminApi(configuration);

let invoiceId: string; //Invoice ID to update (default to undefined)
let createInvoiceRequest: CreateInvoiceRequest; //

const { status, data } = await apiInstance.adminUpdateInvoiceApiV1AdminBillingInvoiceInvoiceIdPatch(
    invoiceId,
    createInvoiceRequest
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **createInvoiceRequest** | **CreateInvoiceRequest**|  | |
| **invoiceId** | [**string**] | Invoice ID to update | defaults to undefined|


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

# **adminUpdateInvoiceApiV1AdminBillingInvoiceInvoiceIdPatch_0**
> object adminUpdateInvoiceApiV1AdminBillingInvoiceInvoiceIdPatch_0(createInvoiceRequest)


### Example

```typescript
import {
    AdminApi,
    Configuration,
    CreateInvoiceRequest
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new AdminApi(configuration);

let invoiceId: string; //Invoice ID to update (default to undefined)
let createInvoiceRequest: CreateInvoiceRequest; //

const { status, data } = await apiInstance.adminUpdateInvoiceApiV1AdminBillingInvoiceInvoiceIdPatch_0(
    invoiceId,
    createInvoiceRequest
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **createInvoiceRequest** | **CreateInvoiceRequest**|  | |
| **invoiceId** | [**string**] | Invoice ID to update | defaults to undefined|


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

# **adminUpdateInvoiceStatusApiV1AdminBillingInvoiceStatusPost**
> { [key: string]: string | null; } adminUpdateInvoiceStatusApiV1AdminBillingInvoiceStatusPost(invoiceStatusRequest)


### Example

```typescript
import {
    AdminApi,
    Configuration,
    InvoiceStatusRequest
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new AdminApi(configuration);

let invoiceStatusRequest: InvoiceStatusRequest; //

const { status, data } = await apiInstance.adminUpdateInvoiceStatusApiV1AdminBillingInvoiceStatusPost(
    invoiceStatusRequest
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **invoiceStatusRequest** | **InvoiceStatusRequest**|  | |


### Return type

**{ [key: string]: string | null; }**

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

# **adminUpdateInvoiceStatusApiV1AdminBillingInvoiceStatusPost_0**
> { [key: string]: string | null; } adminUpdateInvoiceStatusApiV1AdminBillingInvoiceStatusPost_0(invoiceStatusRequest)


### Example

```typescript
import {
    AdminApi,
    Configuration,
    InvoiceStatusRequest
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new AdminApi(configuration);

let invoiceStatusRequest: InvoiceStatusRequest; //

const { status, data } = await apiInstance.adminUpdateInvoiceStatusApiV1AdminBillingInvoiceStatusPost_0(
    invoiceStatusRequest
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **invoiceStatusRequest** | **InvoiceStatusRequest**|  | |


### Return type

**{ [key: string]: string | null; }**

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

# **billingOverviewApiV1AdminBillingOverviewGet**
> Array<object | null> billingOverviewApiV1AdminBillingOverviewGet()


### Example

```typescript
import {
    AdminApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new AdminApi(configuration);

const { status, data } = await apiInstance.billingOverviewApiV1AdminBillingOverviewGet();
```

### Parameters
This endpoint does not have any parameters.


### Return type

**Array<object | null>**

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

# **billingOverviewApiV1AdminBillingOverviewGet_0**
> Array<object | null> billingOverviewApiV1AdminBillingOverviewGet_0()


### Example

```typescript
import {
    AdminApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new AdminApi(configuration);

const { status, data } = await apiInstance.billingOverviewApiV1AdminBillingOverviewGet_0();
```

### Parameters
This endpoint does not have any parameters.


### Return type

**Array<object | null>**

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

# **changeUserRoleApiV1AdminUsersUserIdRolePatch**
> object changeUserRoleApiV1AdminUsersUserIdRolePatch()


### Example

```typescript
import {
    AdminApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new AdminApi(configuration);

let userId: string; //User ID (default to undefined)
let body: object; // (optional)

const { status, data } = await apiInstance.changeUserRoleApiV1AdminUsersUserIdRolePatch(
    userId,
    body
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **body** | **object**|  | |
| **userId** | [**string**] | User ID | defaults to undefined|


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

# **changeUserRoleApiV1AdminUsersUserIdRolePatch_0**
> object changeUserRoleApiV1AdminUsersUserIdRolePatch_0()


### Example

```typescript
import {
    AdminApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new AdminApi(configuration);

let userId: string; //User ID (default to undefined)
let body: object; // (optional)

const { status, data } = await apiInstance.changeUserRoleApiV1AdminUsersUserIdRolePatch_0(
    userId,
    body
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **body** | **object**|  | |
| **userId** | [**string**] | User ID | defaults to undefined|


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

# **createOrganisationApiV1AdminOrganisationsPost**
> object createOrganisationApiV1AdminOrganisationsPost(createOrgRequest)


### Example

```typescript
import {
    AdminApi,
    Configuration,
    CreateOrgRequest
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new AdminApi(configuration);

let createOrgRequest: CreateOrgRequest; //

const { status, data } = await apiInstance.createOrganisationApiV1AdminOrganisationsPost(
    createOrgRequest
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **createOrgRequest** | **CreateOrgRequest**|  | |


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

# **createOrganisationApiV1AdminOrganisationsPost_0**
> object createOrganisationApiV1AdminOrganisationsPost_0(createOrgRequest)


### Example

```typescript
import {
    AdminApi,
    Configuration,
    CreateOrgRequest
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new AdminApi(configuration);

let createOrgRequest: CreateOrgRequest; //

const { status, data } = await apiInstance.createOrganisationApiV1AdminOrganisationsPost_0(
    createOrgRequest
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **createOrgRequest** | **CreateOrgRequest**|  | |


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

# **createTrainingJobApiV1AdminMlopsTrainingJobsPost**
> any createTrainingJobApiV1AdminMlopsTrainingJobsPost(body)

3D.2 — Queue a new training job

### Example

```typescript
import {
    AdminApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new AdminApi(configuration);

let body: object; //

const { status, data } = await apiInstance.createTrainingJobApiV1AdminMlopsTrainingJobsPost(
    body
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **body** | **object**|  | |


### Return type

**any**

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

# **createUserApiV1AdminUsersPost**
> object createUserApiV1AdminUsersPost(createUserRequest)


### Example

```typescript
import {
    AdminApi,
    Configuration,
    CreateUserRequest
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new AdminApi(configuration);

let createUserRequest: CreateUserRequest; //

const { status, data } = await apiInstance.createUserApiV1AdminUsersPost(
    createUserRequest
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **createUserRequest** | **CreateUserRequest**|  | |


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

# **createUserApiV1AdminUsersPost_0**
> object createUserApiV1AdminUsersPost_0(createUserRequest)


### Example

```typescript
import {
    AdminApi,
    Configuration,
    CreateUserRequest
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new AdminApi(configuration);

let createUserRequest: CreateUserRequest; //

const { status, data } = await apiInstance.createUserApiV1AdminUsersPost_0(
    createUserRequest
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **createUserRequest** | **CreateUserRequest**|  | |


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

# **deactivateUserApiV1AdminUsersUserIdDeactivatePatch**
> { [key: string]: string | null; } deactivateUserApiV1AdminUsersUserIdDeactivatePatch()


### Example

```typescript
import {
    AdminApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new AdminApi(configuration);

let userId: string; //User ID (default to undefined)

const { status, data } = await apiInstance.deactivateUserApiV1AdminUsersUserIdDeactivatePatch(
    userId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **userId** | [**string**] | User ID | defaults to undefined|


### Return type

**{ [key: string]: string | null; }**

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

# **deactivateUserApiV1AdminUsersUserIdDeactivatePatch_0**
> { [key: string]: string | null; } deactivateUserApiV1AdminUsersUserIdDeactivatePatch_0()


### Example

```typescript
import {
    AdminApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new AdminApi(configuration);

let userId: string; //User ID (default to undefined)

const { status, data } = await apiInstance.deactivateUserApiV1AdminUsersUserIdDeactivatePatch_0(
    userId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **userId** | [**string**] | User ID | defaults to undefined|


### Return type

**{ [key: string]: string | null; }**

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

# **deleteUserApiV1AdminUsersUserIdDelete**
> { [key: string]: string | null; } deleteUserApiV1AdminUsersUserIdDelete()


### Example

```typescript
import {
    AdminApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new AdminApi(configuration);

let userId: string; //User ID (default to undefined)

const { status, data } = await apiInstance.deleteUserApiV1AdminUsersUserIdDelete(
    userId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **userId** | [**string**] | User ID | defaults to undefined|


### Return type

**{ [key: string]: string | null; }**

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

# **deleteUserApiV1AdminUsersUserIdDelete_0**
> { [key: string]: string | null; } deleteUserApiV1AdminUsersUserIdDelete_0()


### Example

```typescript
import {
    AdminApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new AdminApi(configuration);

let userId: string; //User ID (default to undefined)

const { status, data } = await apiInstance.deleteUserApiV1AdminUsersUserIdDelete_0(
    userId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **userId** | [**string**] | User ID | defaults to undefined|


### Return type

**{ [key: string]: string | null; }**

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

# **emailSingleInvoiceApiV1AdminBillingInvoicesInvoiceNumberEmailPost**
> object emailSingleInvoiceApiV1AdminBillingInvoicesInvoiceNumberEmailPost(emailInvoiceRequest)


### Example

```typescript
import {
    AdminApi,
    Configuration,
    EmailInvoiceRequest
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new AdminApi(configuration);

let invoiceNumber: string; //Invoice number to email (default to undefined)
let emailInvoiceRequest: EmailInvoiceRequest; //

const { status, data } = await apiInstance.emailSingleInvoiceApiV1AdminBillingInvoicesInvoiceNumberEmailPost(
    invoiceNumber,
    emailInvoiceRequest
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **emailInvoiceRequest** | **EmailInvoiceRequest**|  | |
| **invoiceNumber** | [**string**] | Invoice number to email | defaults to undefined|


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

# **emailSingleInvoiceApiV1AdminBillingInvoicesInvoiceNumberEmailPost_0**
> object emailSingleInvoiceApiV1AdminBillingInvoicesInvoiceNumberEmailPost_0(emailInvoiceRequest)


### Example

```typescript
import {
    AdminApi,
    Configuration,
    EmailInvoiceRequest
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new AdminApi(configuration);

let invoiceNumber: string; //Invoice number to email (default to undefined)
let emailInvoiceRequest: EmailInvoiceRequest; //

const { status, data } = await apiInstance.emailSingleInvoiceApiV1AdminBillingInvoicesInvoiceNumberEmailPost_0(
    invoiceNumber,
    emailInvoiceRequest
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **emailInvoiceRequest** | **EmailInvoiceRequest**|  | |
| **invoiceNumber** | [**string**] | Invoice number to email | defaults to undefined|


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

# **getAllActivityApiV1AdminActivityGet**
> Array<any> getAllActivityApiV1AdminActivityGet()


### Example

```typescript
import {
    AdminApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new AdminApi(configuration);

const { status, data } = await apiInstance.getAllActivityApiV1AdminActivityGet();
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

# **getAllActivityApiV1AdminActivityGet_0**
> Array<any> getAllActivityApiV1AdminActivityGet_0()


### Example

```typescript
import {
    AdminApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new AdminApi(configuration);

const { status, data } = await apiInstance.getAllActivityApiV1AdminActivityGet_0();
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

# **getBillingEmailLogApiV1AdminBillingEmailLogGet**
> object getBillingEmailLogApiV1AdminBillingEmailLogGet()


### Example

```typescript
import {
    AdminApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new AdminApi(configuration);

let limit: number; //Max results (optional) (default to 50)
let templateKey: string; //Filter by template (optional) (default to undefined)
let status: string; //Filter by status (optional) (default to undefined)

const { status, data } = await apiInstance.getBillingEmailLogApiV1AdminBillingEmailLogGet(
    limit,
    templateKey,
    status
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **limit** | [**number**] | Max results | (optional) defaults to 50|
| **templateKey** | [**string**] | Filter by template | (optional) defaults to undefined|
| **status** | [**string**] | Filter by status | (optional) defaults to undefined|


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

# **getBillingEmailLogApiV1AdminBillingEmailLogGet_0**
> object getBillingEmailLogApiV1AdminBillingEmailLogGet_0()


### Example

```typescript
import {
    AdminApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new AdminApi(configuration);

let limit: number; //Max results (optional) (default to 50)
let templateKey: string; //Filter by template (optional) (default to undefined)
let status: string; //Filter by status (optional) (default to undefined)

const { status, data } = await apiInstance.getBillingEmailLogApiV1AdminBillingEmailLogGet_0(
    limit,
    templateKey,
    status
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **limit** | [**number**] | Max results | (optional) defaults to 50|
| **templateKey** | [**string**] | Filter by template | (optional) defaults to undefined|
| **status** | [**string**] | Filter by status | (optional) defaults to undefined|


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

# **getBillingSettingsApiV1AdminBillingSettingsGet**
> { [key: string]: string | null; } getBillingSettingsApiV1AdminBillingSettingsGet()


### Example

```typescript
import {
    AdminApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new AdminApi(configuration);

const { status, data } = await apiInstance.getBillingSettingsApiV1AdminBillingSettingsGet();
```

### Parameters
This endpoint does not have any parameters.


### Return type

**{ [key: string]: string | null; }**

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

# **getBillingSettingsApiV1AdminBillingSettingsGet_0**
> { [key: string]: string | null; } getBillingSettingsApiV1AdminBillingSettingsGet_0()


### Example

```typescript
import {
    AdminApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new AdminApi(configuration);

const { status, data } = await apiInstance.getBillingSettingsApiV1AdminBillingSettingsGet_0();
```

### Parameters
This endpoint does not have any parameters.


### Return type

**{ [key: string]: string | null; }**

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

# **getBrandingApiV1AdminBrandingGet**
> object getBrandingApiV1AdminBrandingGet()


### Example

```typescript
import {
    AdminApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new AdminApi(configuration);

const { status, data } = await apiInstance.getBrandingApiV1AdminBrandingGet();
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

# **getBrandingApiV1AdminBrandingGet_0**
> object getBrandingApiV1AdminBrandingGet_0()


### Example

```typescript
import {
    AdminApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new AdminApi(configuration);

const { status, data } = await apiInstance.getBrandingApiV1AdminBrandingGet_0();
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

# **getEmailLogSimpleApiV1AdminEmailLogGet**
> Array<object | null> getEmailLogSimpleApiV1AdminEmailLogGet()


### Example

```typescript
import {
    AdminApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new AdminApi(configuration);

const { status, data } = await apiInstance.getEmailLogSimpleApiV1AdminEmailLogGet();
```

### Parameters
This endpoint does not have any parameters.


### Return type

**Array<object | null>**

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

# **getEmailLogSimpleApiV1AdminEmailLogGet_0**
> Array<object | null> getEmailLogSimpleApiV1AdminEmailLogGet_0()


### Example

```typescript
import {
    AdminApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new AdminApi(configuration);

const { status, data } = await apiInstance.getEmailLogSimpleApiV1AdminEmailLogGet_0();
```

### Parameters
This endpoint does not have any parameters.


### Return type

**Array<object | null>**

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

# **getModelPerformanceApiV1AdminMlopsPerformanceGet**
> any getModelPerformanceApiV1AdminMlopsPerformanceGet()

3D.3 — MAPE tracking over time

### Example

```typescript
import {
    AdminApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new AdminApi(configuration);

const { status, data } = await apiInstance.getModelPerformanceApiV1AdminMlopsPerformanceGet();
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

# **getPaymentsApiV1AdminBillingInvoicesInvoiceNumberPaymentsGet**
> any getPaymentsApiV1AdminBillingInvoicesInvoiceNumberPaymentsGet()


### Example

```typescript
import {
    AdminApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new AdminApi(configuration);

let invoiceNumber: string; // (default to undefined)

const { status, data } = await apiInstance.getPaymentsApiV1AdminBillingInvoicesInvoiceNumberPaymentsGet(
    invoiceNumber
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **invoiceNumber** | [**string**] |  | defaults to undefined|


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

# **getPaymentsApiV1AdminBillingInvoicesInvoiceNumberPaymentsGet_0**
> any getPaymentsApiV1AdminBillingInvoicesInvoiceNumberPaymentsGet_0()


### Example

```typescript
import {
    AdminApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new AdminApi(configuration);

let invoiceNumber: string; // (default to undefined)

const { status, data } = await apiInstance.getPaymentsApiV1AdminBillingInvoicesInvoiceNumberPaymentsGet_0(
    invoiceNumber
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **invoiceNumber** | [**string**] |  | defaults to undefined|


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

# **getPlanConfigsApiV1AdminPlanConfigGet**
> Array<object | null> getPlanConfigsApiV1AdminPlanConfigGet()


### Example

```typescript
import {
    AdminApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new AdminApi(configuration);

const { status, data } = await apiInstance.getPlanConfigsApiV1AdminPlanConfigGet();
```

### Parameters
This endpoint does not have any parameters.


### Return type

**Array<object | null>**

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

# **getPlanConfigsApiV1AdminPlanConfigGet_0**
> Array<object | null> getPlanConfigsApiV1AdminPlanConfigGet_0()


### Example

```typescript
import {
    AdminApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new AdminApi(configuration);

const { status, data } = await apiInstance.getPlanConfigsApiV1AdminPlanConfigGet_0();
```

### Parameters
This endpoint does not have any parameters.


### Return type

**Array<object | null>**

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

# **getUserActivityApiV1AdminUsersUserIdActivityGet**
> Array<any> getUserActivityApiV1AdminUsersUserIdActivityGet()


### Example

```typescript
import {
    AdminApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new AdminApi(configuration);

let userId: string; //User ID (default to undefined)

const { status, data } = await apiInstance.getUserActivityApiV1AdminUsersUserIdActivityGet(
    userId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **userId** | [**string**] | User ID | defaults to undefined|


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
|**422** | Validation Error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getUserActivityApiV1AdminUsersUserIdActivityGet_0**
> Array<any> getUserActivityApiV1AdminUsersUserIdActivityGet_0()


### Example

```typescript
import {
    AdminApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new AdminApi(configuration);

let userId: string; //User ID (default to undefined)

const { status, data } = await apiInstance.getUserActivityApiV1AdminUsersUserIdActivityGet_0(
    userId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **userId** | [**string**] | User ID | defaults to undefined|


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
|**422** | Validation Error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **listCheckpointsDetailedApiV1AdminMlopsCheckpointsGet**
> any listCheckpointsDetailedApiV1AdminMlopsCheckpointsGet()

3D.6 — Model checkpoint details with S3 backup status

### Example

```typescript
import {
    AdminApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new AdminApi(configuration);

const { status, data } = await apiInstance.listCheckpointsDetailedApiV1AdminMlopsCheckpointsGet();
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

# **listOrganisationsApiV1AdminOrganisationsGet**
> Array<object | null> listOrganisationsApiV1AdminOrganisationsGet()


### Example

```typescript
import {
    AdminApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new AdminApi(configuration);

const { status, data } = await apiInstance.listOrganisationsApiV1AdminOrganisationsGet();
```

### Parameters
This endpoint does not have any parameters.


### Return type

**Array<object | null>**

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

# **listOrganisationsApiV1AdminOrganisationsGet_0**
> Array<object | null> listOrganisationsApiV1AdminOrganisationsGet_0()


### Example

```typescript
import {
    AdminApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new AdminApi(configuration);

const { status, data } = await apiInstance.listOrganisationsApiV1AdminOrganisationsGet_0();
```

### Parameters
This endpoint does not have any parameters.


### Return type

**Array<object | null>**

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

# **listTrainingJobsApiV1AdminMlopsTrainingJobsGet**
> any listTrainingJobsApiV1AdminMlopsTrainingJobsGet()

3D.2 — List training jobs (start, monitor, cancel)

### Example

```typescript
import {
    AdminApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new AdminApi(configuration);

const { status, data } = await apiInstance.listTrainingJobsApiV1AdminMlopsTrainingJobsGet();
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

# **listUsersApiV1AdminUsersGet**
> Array<object | null> listUsersApiV1AdminUsersGet()


### Example

```typescript
import {
    AdminApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new AdminApi(configuration);

const { status, data } = await apiInstance.listUsersApiV1AdminUsersGet();
```

### Parameters
This endpoint does not have any parameters.


### Return type

**Array<object | null>**

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

# **listUsersApiV1AdminUsersGet_0**
> Array<object | null> listUsersApiV1AdminUsersGet_0()


### Example

```typescript
import {
    AdminApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new AdminApi(configuration);

const { status, data } = await apiInstance.listUsersApiV1AdminUsersGet_0();
```

### Parameters
This endpoint does not have any parameters.


### Return type

**Array<object | null>**

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

# **mlopsStatusApiV1AdminMlopsStatusGet**
> object mlopsStatusApiV1AdminMlopsStatusGet()


### Example

```typescript
import {
    AdminApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new AdminApi(configuration);

const { status, data } = await apiInstance.mlopsStatusApiV1AdminMlopsStatusGet();
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

# **mlopsStatusApiV1AdminMlopsStatusGet_0**
> object mlopsStatusApiV1AdminMlopsStatusGet_0()


### Example

```typescript
import {
    AdminApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new AdminApi(configuration);

const { status, data } = await apiInstance.mlopsStatusApiV1AdminMlopsStatusGet_0();
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

# **recordPaymentApiV1AdminBillingInvoicesInvoiceNumberPaymentsPost**
> any recordPaymentApiV1AdminBillingInvoicesInvoiceNumberPaymentsPost(body)


### Example

```typescript
import {
    AdminApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new AdminApi(configuration);

let invoiceNumber: string; // (default to undefined)
let body: object; //

const { status, data } = await apiInstance.recordPaymentApiV1AdminBillingInvoicesInvoiceNumberPaymentsPost(
    invoiceNumber,
    body
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **body** | **object**|  | |
| **invoiceNumber** | [**string**] |  | defaults to undefined|


### Return type

**any**

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

# **recordPaymentApiV1AdminBillingInvoicesInvoiceNumberPaymentsPost_0**
> any recordPaymentApiV1AdminBillingInvoicesInvoiceNumberPaymentsPost_0(body)


### Example

```typescript
import {
    AdminApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new AdminApi(configuration);

let invoiceNumber: string; // (default to undefined)
let body: object; //

const { status, data } = await apiInstance.recordPaymentApiV1AdminBillingInvoicesInvoiceNumberPaymentsPost_0(
    invoiceNumber,
    body
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **body** | **object**|  | |
| **invoiceNumber** | [**string**] |  | defaults to undefined|


### Return type

**any**

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

# **saveBillingSettingsApiV1AdminBillingSettingsPost**
> { [key: string]: string | null; } saveBillingSettingsApiV1AdminBillingSettingsPost(body)


### Example

```typescript
import {
    AdminApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new AdminApi(configuration);

let body: object; //

const { status, data } = await apiInstance.saveBillingSettingsApiV1AdminBillingSettingsPost(
    body
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **body** | **object**|  | |


### Return type

**{ [key: string]: string | null; }**

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

# **saveBillingSettingsApiV1AdminBillingSettingsPost_0**
> { [key: string]: string | null; } saveBillingSettingsApiV1AdminBillingSettingsPost_0(body)


### Example

```typescript
import {
    AdminApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new AdminApi(configuration);

let body: object; //

const { status, data } = await apiInstance.saveBillingSettingsApiV1AdminBillingSettingsPost_0(
    body
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **body** | **object**|  | |


### Return type

**{ [key: string]: string | null; }**

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

# **setOrgPlanApiV1AdminOrganisationsOrgIdSetPlanPatch**
> { [key: string]: string | null; } setOrgPlanApiV1AdminOrganisationsOrgIdSetPlanPatch(body)


### Example

```typescript
import {
    AdminApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new AdminApi(configuration);

let orgId: string; //Organisation ID (default to undefined)
let body: object; //

const { status, data } = await apiInstance.setOrgPlanApiV1AdminOrganisationsOrgIdSetPlanPatch(
    orgId,
    body
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **body** | **object**|  | |
| **orgId** | [**string**] | Organisation ID | defaults to undefined|


### Return type

**{ [key: string]: string | null; }**

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

# **setOrgPlanApiV1AdminOrganisationsOrgIdSetPlanPatch_0**
> { [key: string]: string | null; } setOrgPlanApiV1AdminOrganisationsOrgIdSetPlanPatch_0(body)


### Example

```typescript
import {
    AdminApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new AdminApi(configuration);

let orgId: string; //Organisation ID (default to undefined)
let body: object; //

const { status, data } = await apiInstance.setOrgPlanApiV1AdminOrganisationsOrgIdSetPlanPatch_0(
    orgId,
    body
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **body** | **object**|  | |
| **orgId** | [**string**] | Organisation ID | defaults to undefined|


### Return type

**{ [key: string]: string | null; }**

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

# **setRetrainScheduleApiV1AdminMlopsSchedulePost**
> any setRetrainScheduleApiV1AdminMlopsSchedulePost(body)

3D.5 — Set retrain schedule (auto or manual)

### Example

```typescript
import {
    AdminApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new AdminApi(configuration);

let body: object; //

const { status, data } = await apiInstance.setRetrainScheduleApiV1AdminMlopsSchedulePost(
    body
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **body** | **object**|  | |


### Return type

**any**

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

# **suspendOrgApiV1AdminOrganisationsOrgIdSuspendPatch**
> { [key: string]: string | null; } suspendOrgApiV1AdminOrganisationsOrgIdSuspendPatch()


### Example

```typescript
import {
    AdminApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new AdminApi(configuration);

let orgId: string; //Organisation ID (default to undefined)

const { status, data } = await apiInstance.suspendOrgApiV1AdminOrganisationsOrgIdSuspendPatch(
    orgId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **orgId** | [**string**] | Organisation ID | defaults to undefined|


### Return type

**{ [key: string]: string | null; }**

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

# **suspendOrgApiV1AdminOrganisationsOrgIdSuspendPatch_0**
> { [key: string]: string | null; } suspendOrgApiV1AdminOrganisationsOrgIdSuspendPatch_0()


### Example

```typescript
import {
    AdminApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new AdminApi(configuration);

let orgId: string; //Organisation ID (default to undefined)

const { status, data } = await apiInstance.suspendOrgApiV1AdminOrganisationsOrgIdSuspendPatch_0(
    orgId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **orgId** | [**string**] | Organisation ID | defaults to undefined|


### Return type

**{ [key: string]: string | null; }**

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

# **triggerRetrainApiV1AdminMlopsRetrainPost**
> { [key: string]: string | null; } triggerRetrainApiV1AdminMlopsRetrainPost()


### Example

```typescript
import {
    AdminApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new AdminApi(configuration);

const { status, data } = await apiInstance.triggerRetrainApiV1AdminMlopsRetrainPost();
```

### Parameters
This endpoint does not have any parameters.


### Return type

**{ [key: string]: string | null; }**

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

# **triggerRetrainApiV1AdminMlopsRetrainPost_0**
> { [key: string]: string | null; } triggerRetrainApiV1AdminMlopsRetrainPost_0()


### Example

```typescript
import {
    AdminApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new AdminApi(configuration);

const { status, data } = await apiInstance.triggerRetrainApiV1AdminMlopsRetrainPost_0();
```

### Parameters
This endpoint does not have any parameters.


### Return type

**{ [key: string]: string | null; }**

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

# **updateBrandingApiV1AdminBrandingPatch**
> { [key: string]: string | null; } updateBrandingApiV1AdminBrandingPatch(body)


### Example

```typescript
import {
    AdminApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new AdminApi(configuration);

let body: object; //

const { status, data } = await apiInstance.updateBrandingApiV1AdminBrandingPatch(
    body
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **body** | **object**|  | |


### Return type

**{ [key: string]: string | null; }**

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

# **updateBrandingApiV1AdminBrandingPatch_0**
> { [key: string]: string | null; } updateBrandingApiV1AdminBrandingPatch_0(body)


### Example

```typescript
import {
    AdminApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new AdminApi(configuration);

let body: object; //

const { status, data } = await apiInstance.updateBrandingApiV1AdminBrandingPatch_0(
    body
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **body** | **object**|  | |


### Return type

**{ [key: string]: string | null; }**

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

# **updatePlanConfigApiV1AdminPlanConfigPlanKeyPatch**
> { [key: string]: string | null; } updatePlanConfigApiV1AdminPlanConfigPlanKeyPatch(body)


### Example

```typescript
import {
    AdminApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new AdminApi(configuration);

let planKey: string; //Plan key to update (default to undefined)
let body: object; //

const { status, data } = await apiInstance.updatePlanConfigApiV1AdminPlanConfigPlanKeyPatch(
    planKey,
    body
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **body** | **object**|  | |
| **planKey** | [**string**] | Plan key to update | defaults to undefined|


### Return type

**{ [key: string]: string | null; }**

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

# **updatePlanConfigApiV1AdminPlanConfigPlanKeyPatch_0**
> { [key: string]: string | null; } updatePlanConfigApiV1AdminPlanConfigPlanKeyPatch_0(body)


### Example

```typescript
import {
    AdminApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new AdminApi(configuration);

let planKey: string; //Plan key to update (default to undefined)
let body: object; //

const { status, data } = await apiInstance.updatePlanConfigApiV1AdminPlanConfigPlanKeyPatch_0(
    planKey,
    body
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **body** | **object**|  | |
| **planKey** | [**string**] | Plan key to update | defaults to undefined|


### Return type

**{ [key: string]: string | null; }**

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

# **updateTrainingJobApiV1AdminMlopsTrainingJobsJobIdPatch**
> any updateTrainingJobApiV1AdminMlopsTrainingJobsJobIdPatch(body)

3D.2 — Update job status (called by training script)

### Example

```typescript
import {
    AdminApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new AdminApi(configuration);

let jobId: string; // (default to undefined)
let body: object; //

const { status, data } = await apiInstance.updateTrainingJobApiV1AdminMlopsTrainingJobsJobIdPatch(
    jobId,
    body
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **body** | **object**|  | |
| **jobId** | [**string**] |  | defaults to undefined|


### Return type

**any**

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

# **voidPaymentApiV1AdminBillingPaymentsPaymentIdVoidPost**
> any voidPaymentApiV1AdminBillingPaymentsPaymentIdVoidPost()


### Example

```typescript
import {
    AdminApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new AdminApi(configuration);

let paymentId: string; // (default to undefined)

const { status, data } = await apiInstance.voidPaymentApiV1AdminBillingPaymentsPaymentIdVoidPost(
    paymentId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **paymentId** | [**string**] |  | defaults to undefined|


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

# **voidPaymentApiV1AdminBillingPaymentsPaymentIdVoidPost_0**
> any voidPaymentApiV1AdminBillingPaymentsPaymentIdVoidPost_0()


### Example

```typescript
import {
    AdminApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new AdminApi(configuration);

let paymentId: string; // (default to undefined)

const { status, data } = await apiInstance.voidPaymentApiV1AdminBillingPaymentsPaymentIdVoidPost_0(
    paymentId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **paymentId** | [**string**] |  | defaults to undefined|


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

