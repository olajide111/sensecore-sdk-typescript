## @sensecore/sdk@0.1.0

This generator creates TypeScript/JavaScript client that utilizes [axios](https://github.com/axios/axios). The generated Node module can be used in the following environments:

Environment
* Node.js
* Webpack
* Browserify

Language level
* ES5 - you must have a Promises/A+ library installed
* ES6

Module system
* CommonJS
* ES6 module system

It can be used in both TypeScript and JavaScript. In TypeScript, the definition will be automatically resolved via `package.json`. ([Reference](https://www.typescriptlang.org/docs/handbook/declaration-files/consumption.html))

### Building

To build and compile the typescript sources to javascript use:
```
npm install
npm run build
```

### Publishing

First build the package then run `npm publish`

### Consuming

navigate to the folder of your consuming project and run one of the following commands.

_published:_

```
npm install @sensecore/sdk@0.1.0 --save
```

_unPublished (not recommended):_

```
npm install PATH_TO_GENERATED_PACKAGE --save
```

### Documentation for API Endpoints

All URIs are relative to *https://api.sensecoreai.com*

Class | Method | HTTP request | Description
------------ | ------------- | ------------- | -------------
*AIGovernanceApi* | [**aiTransparencyApiV1AiTransparencyGet**](docs/AIGovernanceApi.md#aitransparencyapiv1aitransparencyget) | **GET** /api/v1/ai/transparency | Ai Transparency
*AIGovernanceApi* | [**aiTransparencyApiV1AiTransparencyGet_0**](docs/AIGovernanceApi.md#aitransparencyapiv1aitransparencyget_0) | **GET** /api/v1/ai/transparency | Ai Transparency
*AIGovernanceApi* | [**biasAssessmentApiV1AiBiasAssessmentGet**](docs/AIGovernanceApi.md#biasassessmentapiv1aibiasassessmentget) | **GET** /api/v1/ai/bias-assessment | Bias Assessment
*AIGovernanceApi* | [**biasAssessmentApiV1AiBiasAssessmentGet_0**](docs/AIGovernanceApi.md#biasassessmentapiv1aibiasassessmentget_0) | **GET** /api/v1/ai/bias-assessment | Bias Assessment
*AIGovernanceApi* | [**getModelDetailApiV1AiModelsModelIdGet**](docs/AIGovernanceApi.md#getmodeldetailapiv1aimodelsmodelidget) | **GET** /api/v1/ai/models/{model_id} | Get Model Detail
*AIGovernanceApi* | [**getModelDetailApiV1AiModelsModelIdGet_0**](docs/AIGovernanceApi.md#getmodeldetailapiv1aimodelsmodelidget_0) | **GET** /api/v1/ai/models/{model_id} | Get Model Detail
*AIGovernanceApi* | [**listModelsApiV1AiModelsGet**](docs/AIGovernanceApi.md#listmodelsapiv1aimodelsget) | **GET** /api/v1/ai/models | List Models
*AIGovernanceApi* | [**listModelsApiV1AiModelsGet_0**](docs/AIGovernanceApi.md#listmodelsapiv1aimodelsget_0) | **GET** /api/v1/ai/models | List Models
*APIKeysApi* | [**createApiKeyApiV1ApiKeysPost**](docs/APIKeysApi.md#createapikeyapiv1apikeyspost) | **POST** /api/v1/api-keys | Create Api Key
*APIKeysApi* | [**listApiKeysApiV1ApiKeysGet**](docs/APIKeysApi.md#listapikeysapiv1apikeysget) | **GET** /api/v1/api-keys | List Api Keys
*APIKeysApi* | [**revokeApiKeyApiV1ApiKeysKeyIdDelete**](docs/APIKeysApi.md#revokeapikeyapiv1apikeyskeyiddelete) | **DELETE** /api/v1/api-keys/{key_id} | Revoke Api Key
*APIKeysApi* | [**rotateApiKeyApiV1ApiKeysKeyIdRotatePost**](docs/APIKeysApi.md#rotateapikeyapiv1apikeyskeyidrotatepost) | **POST** /api/v1/api-keys/{key_id}/rotate | Rotate Api Key
*APIKeysApi* | [**whoamiApiV1ApiKeysWhoamiGet**](docs/APIKeysApi.md#whoamiapiv1apikeyswhoamiget) | **GET** /api/v1/api-keys/whoami | Whoami
*AdminApi* | [**activateOrgApiV1AdminOrganisationsOrgIdActivatePatch**](docs/AdminApi.md#activateorgapiv1adminorganisationsorgidactivatepatch) | **PATCH** /api/v1/admin/organisations/{org_id}/activate | Activate Org
*AdminApi* | [**activateOrgApiV1AdminOrganisationsOrgIdActivatePatch_0**](docs/AdminApi.md#activateorgapiv1adminorganisationsorgidactivatepatch_0) | **PATCH** /api/v1/admin/organisations/{org_id}/activate | Activate Org
*AdminApi* | [**activateUserApiV1AdminUsersUserIdActivatePatch**](docs/AdminApi.md#activateuserapiv1adminusersuseridactivatepatch) | **PATCH** /api/v1/admin/users/{user_id}/activate | Activate User
*AdminApi* | [**activateUserApiV1AdminUsersUserIdActivatePatch_0**](docs/AdminApi.md#activateuserapiv1adminusersuseridactivatepatch_0) | **PATCH** /api/v1/admin/users/{user_id}/activate | Activate User
*AdminApi* | [**adminCreateInvoiceApiV1AdminBillingInvoicePost**](docs/AdminApi.md#admincreateinvoiceapiv1adminbillinginvoicepost) | **POST** /api/v1/admin/billing/invoice | Generate invoice
*AdminApi* | [**adminCreateInvoiceApiV1AdminBillingInvoicePost_0**](docs/AdminApi.md#admincreateinvoiceapiv1adminbillinginvoicepost_0) | **POST** /api/v1/admin/billing/invoice | Generate invoice
*AdminApi* | [**adminFilterInvoicesApiV1AdminBillingInvoicesGet**](docs/AdminApi.md#adminfilterinvoicesapiv1adminbillinginvoicesget) | **GET** /api/v1/admin/billing/invoices | Filter invoices
*AdminApi* | [**adminFilterInvoicesApiV1AdminBillingInvoicesGet_0**](docs/AdminApi.md#adminfilterinvoicesapiv1adminbillinginvoicesget_0) | **GET** /api/v1/admin/billing/invoices | Filter invoices
*AdminApi* | [**adminListAllInvoicesApiV1AdminBillingAllInvoicesGet**](docs/AdminApi.md#adminlistallinvoicesapiv1adminbillingallinvoicesget) | **GET** /api/v1/admin/billing/all-invoices | List all invoices
*AdminApi* | [**adminListAllInvoicesApiV1AdminBillingAllInvoicesGet_0**](docs/AdminApi.md#adminlistallinvoicesapiv1adminbillingallinvoicesget_0) | **GET** /api/v1/admin/billing/all-invoices | List all invoices
*AdminApi* | [**adminUpdateInvoiceApiV1AdminBillingInvoiceInvoiceIdPatch**](docs/AdminApi.md#adminupdateinvoiceapiv1adminbillinginvoiceinvoiceidpatch) | **PATCH** /api/v1/admin/billing/invoice/{invoice_id} | Update invoice
*AdminApi* | [**adminUpdateInvoiceApiV1AdminBillingInvoiceInvoiceIdPatch_0**](docs/AdminApi.md#adminupdateinvoiceapiv1adminbillinginvoiceinvoiceidpatch_0) | **PATCH** /api/v1/admin/billing/invoice/{invoice_id} | Update invoice
*AdminApi* | [**adminUpdateInvoiceStatusApiV1AdminBillingInvoiceStatusPost**](docs/AdminApi.md#adminupdateinvoicestatusapiv1adminbillinginvoicestatuspost) | **POST** /api/v1/admin/billing/invoice-status | Update invoice status
*AdminApi* | [**adminUpdateInvoiceStatusApiV1AdminBillingInvoiceStatusPost_0**](docs/AdminApi.md#adminupdateinvoicestatusapiv1adminbillinginvoicestatuspost_0) | **POST** /api/v1/admin/billing/invoice-status | Update invoice status
*AdminApi* | [**billingOverviewApiV1AdminBillingOverviewGet**](docs/AdminApi.md#billingoverviewapiv1adminbillingoverviewget) | **GET** /api/v1/admin/billing/overview | Billing Overview
*AdminApi* | [**billingOverviewApiV1AdminBillingOverviewGet_0**](docs/AdminApi.md#billingoverviewapiv1adminbillingoverviewget_0) | **GET** /api/v1/admin/billing/overview | Billing Overview
*AdminApi* | [**changeUserRoleApiV1AdminUsersUserIdRolePatch**](docs/AdminApi.md#changeuserroleapiv1adminusersuseridrolepatch) | **PATCH** /api/v1/admin/users/{user_id}/role | Change user role
*AdminApi* | [**changeUserRoleApiV1AdminUsersUserIdRolePatch_0**](docs/AdminApi.md#changeuserroleapiv1adminusersuseridrolepatch_0) | **PATCH** /api/v1/admin/users/{user_id}/role | Change user role
*AdminApi* | [**createOrganisationApiV1AdminOrganisationsPost**](docs/AdminApi.md#createorganisationapiv1adminorganisationspost) | **POST** /api/v1/admin/organisations | Create organisation
*AdminApi* | [**createOrganisationApiV1AdminOrganisationsPost_0**](docs/AdminApi.md#createorganisationapiv1adminorganisationspost_0) | **POST** /api/v1/admin/organisations | Create organisation
*AdminApi* | [**createTrainingJobApiV1AdminMlopsTrainingJobsPost**](docs/AdminApi.md#createtrainingjobapiv1adminmlopstrainingjobspost) | **POST** /api/v1/admin/mlops/training-jobs | Create Training Job
*AdminApi* | [**createUserApiV1AdminUsersPost**](docs/AdminApi.md#createuserapiv1adminuserspost) | **POST** /api/v1/admin/users | Create a new user
*AdminApi* | [**createUserApiV1AdminUsersPost_0**](docs/AdminApi.md#createuserapiv1adminuserspost_0) | **POST** /api/v1/admin/users | Create a new user
*AdminApi* | [**deactivateUserApiV1AdminUsersUserIdDeactivatePatch**](docs/AdminApi.md#deactivateuserapiv1adminusersuseriddeactivatepatch) | **PATCH** /api/v1/admin/users/{user_id}/deactivate | Deactivate User
*AdminApi* | [**deactivateUserApiV1AdminUsersUserIdDeactivatePatch_0**](docs/AdminApi.md#deactivateuserapiv1adminusersuseriddeactivatepatch_0) | **PATCH** /api/v1/admin/users/{user_id}/deactivate | Deactivate User
*AdminApi* | [**deleteUserApiV1AdminUsersUserIdDelete**](docs/AdminApi.md#deleteuserapiv1adminusersuseriddelete) | **DELETE** /api/v1/admin/users/{user_id} | Delete User
*AdminApi* | [**deleteUserApiV1AdminUsersUserIdDelete_0**](docs/AdminApi.md#deleteuserapiv1adminusersuseriddelete_0) | **DELETE** /api/v1/admin/users/{user_id} | Delete User
*AdminApi* | [**emailSingleInvoiceApiV1AdminBillingInvoicesInvoiceNumberEmailPost**](docs/AdminApi.md#emailsingleinvoiceapiv1adminbillinginvoicesinvoicenumberemailpost) | **POST** /api/v1/admin/billing/invoices/{invoice_number}/email | Email Single Invoice
*AdminApi* | [**emailSingleInvoiceApiV1AdminBillingInvoicesInvoiceNumberEmailPost_0**](docs/AdminApi.md#emailsingleinvoiceapiv1adminbillinginvoicesinvoicenumberemailpost_0) | **POST** /api/v1/admin/billing/invoices/{invoice_number}/email | Email Single Invoice
*AdminApi* | [**getAllActivityApiV1AdminActivityGet**](docs/AdminApi.md#getallactivityapiv1adminactivityget) | **GET** /api/v1/admin/activity | Get All Activity
*AdminApi* | [**getAllActivityApiV1AdminActivityGet_0**](docs/AdminApi.md#getallactivityapiv1adminactivityget_0) | **GET** /api/v1/admin/activity | Get All Activity
*AdminApi* | [**getBillingEmailLogApiV1AdminBillingEmailLogGet**](docs/AdminApi.md#getbillingemaillogapiv1adminbillingemaillogget) | **GET** /api/v1/admin/billing/email-log | Billing email log with filters
*AdminApi* | [**getBillingEmailLogApiV1AdminBillingEmailLogGet_0**](docs/AdminApi.md#getbillingemaillogapiv1adminbillingemaillogget_0) | **GET** /api/v1/admin/billing/email-log | Billing email log with filters
*AdminApi* | [**getBillingSettingsApiV1AdminBillingSettingsGet**](docs/AdminApi.md#getbillingsettingsapiv1adminbillingsettingsget) | **GET** /api/v1/admin/billing/settings | Get Billing Settings
*AdminApi* | [**getBillingSettingsApiV1AdminBillingSettingsGet_0**](docs/AdminApi.md#getbillingsettingsapiv1adminbillingsettingsget_0) | **GET** /api/v1/admin/billing/settings | Get Billing Settings
*AdminApi* | [**getBrandingApiV1AdminBrandingGet**](docs/AdminApi.md#getbrandingapiv1adminbrandingget) | **GET** /api/v1/admin/branding | Get platform branding
*AdminApi* | [**getBrandingApiV1AdminBrandingGet_0**](docs/AdminApi.md#getbrandingapiv1adminbrandingget_0) | **GET** /api/v1/admin/branding | Get platform branding
*AdminApi* | [**getEmailLogSimpleApiV1AdminEmailLogGet**](docs/AdminApi.md#getemaillogsimpleapiv1adminemaillogget) | **GET** /api/v1/admin/email-log | Get email send log
*AdminApi* | [**getEmailLogSimpleApiV1AdminEmailLogGet_0**](docs/AdminApi.md#getemaillogsimpleapiv1adminemaillogget_0) | **GET** /api/v1/admin/email-log | Get email send log
*AdminApi* | [**getModelPerformanceApiV1AdminMlopsPerformanceGet**](docs/AdminApi.md#getmodelperformanceapiv1adminmlopsperformanceget) | **GET** /api/v1/admin/mlops/performance | Get Model Performance
*AdminApi* | [**getPaymentsApiV1AdminBillingInvoicesInvoiceNumberPaymentsGet**](docs/AdminApi.md#getpaymentsapiv1adminbillinginvoicesinvoicenumberpaymentsget) | **GET** /api/v1/admin/billing/invoices/{invoice_number}/payments | Get Payments
*AdminApi* | [**getPaymentsApiV1AdminBillingInvoicesInvoiceNumberPaymentsGet_0**](docs/AdminApi.md#getpaymentsapiv1adminbillinginvoicesinvoicenumberpaymentsget_0) | **GET** /api/v1/admin/billing/invoices/{invoice_number}/payments | Get Payments
*AdminApi* | [**getPlanConfigsApiV1AdminPlanConfigGet**](docs/AdminApi.md#getplanconfigsapiv1adminplanconfigget) | **GET** /api/v1/admin/plan-config | Get all plan configs
*AdminApi* | [**getPlanConfigsApiV1AdminPlanConfigGet_0**](docs/AdminApi.md#getplanconfigsapiv1adminplanconfigget_0) | **GET** /api/v1/admin/plan-config | Get all plan configs
*AdminApi* | [**getUserActivityApiV1AdminUsersUserIdActivityGet**](docs/AdminApi.md#getuseractivityapiv1adminusersuseridactivityget) | **GET** /api/v1/admin/users/{user_id}/activity | Get User Activity
*AdminApi* | [**getUserActivityApiV1AdminUsersUserIdActivityGet_0**](docs/AdminApi.md#getuseractivityapiv1adminusersuseridactivityget_0) | **GET** /api/v1/admin/users/{user_id}/activity | Get User Activity
*AdminApi* | [**listCheckpointsDetailedApiV1AdminMlopsCheckpointsGet**](docs/AdminApi.md#listcheckpointsdetailedapiv1adminmlopscheckpointsget) | **GET** /api/v1/admin/mlops/checkpoints | List Checkpoints Detailed
*AdminApi* | [**listOrganisationsApiV1AdminOrganisationsGet**](docs/AdminApi.md#listorganisationsapiv1adminorganisationsget) | **GET** /api/v1/admin/organisations | List all organisations
*AdminApi* | [**listOrganisationsApiV1AdminOrganisationsGet_0**](docs/AdminApi.md#listorganisationsapiv1adminorganisationsget_0) | **GET** /api/v1/admin/organisations | List all organisations
*AdminApi* | [**listTrainingJobsApiV1AdminMlopsTrainingJobsGet**](docs/AdminApi.md#listtrainingjobsapiv1adminmlopstrainingjobsget) | **GET** /api/v1/admin/mlops/training-jobs | List Training Jobs
*AdminApi* | [**listUsersApiV1AdminUsersGet**](docs/AdminApi.md#listusersapiv1adminusersget) | **GET** /api/v1/admin/users | List all users
*AdminApi* | [**listUsersApiV1AdminUsersGet_0**](docs/AdminApi.md#listusersapiv1adminusersget_0) | **GET** /api/v1/admin/users | List all users
*AdminApi* | [**mlopsStatusApiV1AdminMlopsStatusGet**](docs/AdminApi.md#mlopsstatusapiv1adminmlopsstatusget) | **GET** /api/v1/admin/mlops/status | MLOps model status
*AdminApi* | [**mlopsStatusApiV1AdminMlopsStatusGet_0**](docs/AdminApi.md#mlopsstatusapiv1adminmlopsstatusget_0) | **GET** /api/v1/admin/mlops/status | MLOps model status
*AdminApi* | [**recordPaymentApiV1AdminBillingInvoicesInvoiceNumberPaymentsPost**](docs/AdminApi.md#recordpaymentapiv1adminbillinginvoicesinvoicenumberpaymentspost) | **POST** /api/v1/admin/billing/invoices/{invoice_number}/payments | Record Payment
*AdminApi* | [**recordPaymentApiV1AdminBillingInvoicesInvoiceNumberPaymentsPost_0**](docs/AdminApi.md#recordpaymentapiv1adminbillinginvoicesinvoicenumberpaymentspost_0) | **POST** /api/v1/admin/billing/invoices/{invoice_number}/payments | Record Payment
*AdminApi* | [**saveBillingSettingsApiV1AdminBillingSettingsPost**](docs/AdminApi.md#savebillingsettingsapiv1adminbillingsettingspost) | **POST** /api/v1/admin/billing/settings | Save Billing Settings
*AdminApi* | [**saveBillingSettingsApiV1AdminBillingSettingsPost_0**](docs/AdminApi.md#savebillingsettingsapiv1adminbillingsettingspost_0) | **POST** /api/v1/admin/billing/settings | Save Billing Settings
*AdminApi* | [**setOrgPlanApiV1AdminOrganisationsOrgIdSetPlanPatch**](docs/AdminApi.md#setorgplanapiv1adminorganisationsorgidsetplanpatch) | **PATCH** /api/v1/admin/organisations/{org_id}/set-plan | Set Org Plan
*AdminApi* | [**setOrgPlanApiV1AdminOrganisationsOrgIdSetPlanPatch_0**](docs/AdminApi.md#setorgplanapiv1adminorganisationsorgidsetplanpatch_0) | **PATCH** /api/v1/admin/organisations/{org_id}/set-plan | Set Org Plan
*AdminApi* | [**setRetrainScheduleApiV1AdminMlopsSchedulePost**](docs/AdminApi.md#setretrainscheduleapiv1adminmlopsschedulepost) | **POST** /api/v1/admin/mlops/schedule | Set Retrain Schedule
*AdminApi* | [**suspendOrgApiV1AdminOrganisationsOrgIdSuspendPatch**](docs/AdminApi.md#suspendorgapiv1adminorganisationsorgidsuspendpatch) | **PATCH** /api/v1/admin/organisations/{org_id}/suspend | Suspend Org
*AdminApi* | [**suspendOrgApiV1AdminOrganisationsOrgIdSuspendPatch_0**](docs/AdminApi.md#suspendorgapiv1adminorganisationsorgidsuspendpatch_0) | **PATCH** /api/v1/admin/organisations/{org_id}/suspend | Suspend Org
*AdminApi* | [**triggerRetrainApiV1AdminMlopsRetrainPost**](docs/AdminApi.md#triggerretrainapiv1adminmlopsretrainpost) | **POST** /api/v1/admin/mlops/retrain | Trigger model retrain
*AdminApi* | [**triggerRetrainApiV1AdminMlopsRetrainPost_0**](docs/AdminApi.md#triggerretrainapiv1adminmlopsretrainpost_0) | **POST** /api/v1/admin/mlops/retrain | Trigger model retrain
*AdminApi* | [**updateBrandingApiV1AdminBrandingPatch**](docs/AdminApi.md#updatebrandingapiv1adminbrandingpatch) | **PATCH** /api/v1/admin/branding | Update platform branding
*AdminApi* | [**updateBrandingApiV1AdminBrandingPatch_0**](docs/AdminApi.md#updatebrandingapiv1adminbrandingpatch_0) | **PATCH** /api/v1/admin/branding | Update platform branding
*AdminApi* | [**updatePlanConfigApiV1AdminPlanConfigPlanKeyPatch**](docs/AdminApi.md#updateplanconfigapiv1adminplanconfigplankeypatch) | **PATCH** /api/v1/admin/plan-config/{plan_key} | Update plan config
*AdminApi* | [**updatePlanConfigApiV1AdminPlanConfigPlanKeyPatch_0**](docs/AdminApi.md#updateplanconfigapiv1adminplanconfigplankeypatch_0) | **PATCH** /api/v1/admin/plan-config/{plan_key} | Update plan config
*AdminApi* | [**updateTrainingJobApiV1AdminMlopsTrainingJobsJobIdPatch**](docs/AdminApi.md#updatetrainingjobapiv1adminmlopstrainingjobsjobidpatch) | **PATCH** /api/v1/admin/mlops/training-jobs/{job_id} | Update Training Job
*AdminApi* | [**voidPaymentApiV1AdminBillingPaymentsPaymentIdVoidPost**](docs/AdminApi.md#voidpaymentapiv1adminbillingpaymentspaymentidvoidpost) | **POST** /api/v1/admin/billing/payments/{payment_id}/void | Void Payment
*AdminApi* | [**voidPaymentApiV1AdminBillingPaymentsPaymentIdVoidPost_0**](docs/AdminApi.md#voidpaymentapiv1adminbillingpaymentspaymentidvoidpost_0) | **POST** /api/v1/admin/billing/payments/{payment_id}/void | Void Payment
*AdminClientHealthApi* | [**getClientHealthApiV1AdminClientHealthGet**](docs/AdminClientHealthApi.md#getclienthealthapiv1adminclienthealthget) | **GET** /api/v1/admin/client-health | Get Client Health
*AuthApi* | [**getMeApiV1AuthMeGet**](docs/AuthApi.md#getmeapiv1authmeget) | **GET** /api/v1/auth/me | Get Me
*AuthApi* | [**loginApiV1AuthLoginPost**](docs/AuthApi.md#loginapiv1authloginpost) | **POST** /api/v1/auth/login | Get access token
*AuthApi* | [**myPermissionsApiV1MePermissionsGet**](docs/AuthApi.md#mypermissionsapiv1mepermissionsget) | **GET** /api/v1/me/permissions | My Permissions
*AuthApi* | [**registerApiV1AuthRegisterPost**](docs/AuthApi.md#registerapiv1authregisterpost) | **POST** /api/v1/auth/register | Register
*AuthApi* | [**resetPasswordApiV1AuthResetPasswordPost**](docs/AuthApi.md#resetpasswordapiv1authresetpasswordpost) | **POST** /api/v1/auth/reset-password | Reset Password
*AuthApi* | [**verifyApiV1AuthVerifyGet**](docs/AuthApi.md#verifyapiv1authverifyget) | **GET** /api/v1/auth/verify | Verify
*BillingApi* | [**getInvoiceDetailApiV1BillingInvoiceInvoiceIdGet**](docs/BillingApi.md#getinvoicedetailapiv1billinginvoiceinvoiceidget) | **GET** /api/v1/billing/invoice/{invoice_id} | Get Invoice Detail
*BillingApi* | [**getInvoiceDetailApiV1BillingInvoiceInvoiceIdGet_0**](docs/BillingApi.md#getinvoicedetailapiv1billinginvoiceinvoiceidget_0) | **GET** /api/v1/billing/invoice/{invoice_id} | Get Invoice Detail
*BillingApi* | [**getInvoicesApiV1BillingInvoicesGet**](docs/BillingApi.md#getinvoicesapiv1billinginvoicesget) | **GET** /api/v1/billing/invoices | Get Invoices
*BillingApi* | [**getInvoicesApiV1BillingInvoicesGet_0**](docs/BillingApi.md#getinvoicesapiv1billinginvoicesget_0) | **GET** /api/v1/billing/invoices | Get Invoices
*BillingApi* | [**getMyPlanApiV1BillingMyPlanGet**](docs/BillingApi.md#getmyplanapiv1billingmyplanget) | **GET** /api/v1/billing/my-plan | Get current org plan details and feature access
*BillingApi* | [**getMyPlanApiV1BillingMyPlanGet_0**](docs/BillingApi.md#getmyplanapiv1billingmyplanget_0) | **GET** /api/v1/billing/my-plan | Get current org plan details and feature access
*BillingApi* | [**getMyPlanApiV1BillingMyPlanGet_1**](docs/BillingApi.md#getmyplanapiv1billingmyplanget_1) | **GET** /api/v1/billing/my-plan | Get current org plan details and feature access
*BillingApi* | [**getPaymentSettingsApiV1BillingPaymentSettingsGet**](docs/BillingApi.md#getpaymentsettingsapiv1billingpaymentsettingsget) | **GET** /api/v1/billing/payment-settings | Get Payment Settings
*BillingApi* | [**getPaymentSettingsApiV1BillingPaymentSettingsGet_0**](docs/BillingApi.md#getpaymentsettingsapiv1billingpaymentsettingsget_0) | **GET** /api/v1/billing/payment-settings | Get Payment Settings
*BillingApi* | [**getPaymentSettingsApiV1BillingPaymentSettingsGet_1**](docs/BillingApi.md#getpaymentsettingsapiv1billingpaymentsettingsget_1) | **GET** /api/v1/billing/payment-settings | Get Payment Settings
*BillingApi* | [**getPlanApiV1BillingPlanGet**](docs/BillingApi.md#getplanapiv1billingplanget) | **GET** /api/v1/billing/plan | Get Plan
*BillingApi* | [**getPlanApiV1BillingPlanGet_0**](docs/BillingApi.md#getplanapiv1billingplanget_0) | **GET** /api/v1/billing/plan | Get Plan
*BillingApi* | [**requestInvoiceApiV1BillingInvoicesRequestPost**](docs/BillingApi.md#requestinvoiceapiv1billinginvoicesrequestpost) | **POST** /api/v1/billing/invoices/request | Request Invoice
*BillingApi* | [**requestInvoiceApiV1BillingInvoicesRequestPost_0**](docs/BillingApi.md#requestinvoiceapiv1billinginvoicesrequestpost_0) | **POST** /api/v1/billing/invoices/request | Request Invoice
*BillingApi* | [**updatePlanApiV1BillingPlanPost**](docs/BillingApi.md#updateplanapiv1billingplanpost) | **POST** /api/v1/billing/plan | Update Plan
*BillingApi* | [**updatePlanApiV1BillingPlanPost_0**](docs/BillingApi.md#updateplanapiv1billingplanpost_0) | **POST** /api/v1/billing/plan | Update Plan
*BillingEmailApi* | [**emailAllInvoicesApiV1BillingInvoicesEmailAllPost**](docs/BillingEmailApi.md#emailallinvoicesapiv1billinginvoicesemailallpost) | **POST** /api/v1/billing/invoices/email-all | Email All Invoices
*BillingEmailApi* | [**emailAllInvoicesApiV1BillingInvoicesEmailAllPost_0**](docs/BillingEmailApi.md#emailallinvoicesapiv1billinginvoicesemailallpost_0) | **POST** /api/v1/billing/invoices/email-all | Email All Invoices
*BillingEmailApi* | [**emailInvoiceApiV1BillingInvoicesInvoiceIdEmailPost**](docs/BillingEmailApi.md#emailinvoiceapiv1billinginvoicesinvoiceidemailpost) | **POST** /api/v1/billing/invoices/{invoice_id}/email | Email Invoice
*BillingEmailApi* | [**emailInvoiceApiV1BillingInvoicesInvoiceIdEmailPost_0**](docs/BillingEmailApi.md#emailinvoiceapiv1billinginvoicesinvoiceidemailpost_0) | **POST** /api/v1/billing/invoices/{invoice_id}/email | Email Invoice
*BuildingsApi* | [**addMeterBuildingsBuildingIdMetersPost**](docs/BuildingsApi.md#addmeterbuildingsbuildingidmeterspost) | **POST** /buildings/{building_id}/meters | Add Meter
*BuildingsApi* | [**bulkUploadBuildingsBuildingsBulkUploadPost**](docs/BuildingsApi.md#bulkuploadbuildingsbuildingsbulkuploadpost) | **POST** /buildings/bulk-upload | Bulk Upload Buildings
*BuildingsApi* | [**createBuildingApiV1BuildingsPost**](docs/BuildingsApi.md#createbuildingapiv1buildingspost) | **POST** /api/v1/buildings | Create Building
*BuildingsApi* | [**deleteBuildingApiV1BuildingsBuildingIdDelete**](docs/BuildingsApi.md#deletebuildingapiv1buildingsbuildingiddelete) | **DELETE** /api/v1/buildings/{building_id} | Delete Building
*BuildingsApi* | [**deleteMeterBuildingsBuildingIdMetersMeterIdDelete**](docs/BuildingsApi.md#deletemeterbuildingsbuildingidmetersmeteriddelete) | **DELETE** /buildings/{building_id}/meters/{meter_id} | Delete Meter
*BuildingsApi* | [**getBuildingApiV1BuildingsBuildingIdGet**](docs/BuildingsApi.md#getbuildingapiv1buildingsbuildingidget) | **GET** /api/v1/buildings/{building_id} | Get Building
*BuildingsApi* | [**getBuildingBuildingsBuildingIdGet**](docs/BuildingsApi.md#getbuildingbuildingsbuildingidget) | **GET** /buildings/{building_id} | Get Building
*BuildingsApi* | [**getMetersBuildingsBuildingIdMetersGet**](docs/BuildingsApi.md#getmetersbuildingsbuildingidmetersget) | **GET** /buildings/{building_id}/meters | Get Meters
*BuildingsApi* | [**listBuildingsApiV1BuildingsGet**](docs/BuildingsApi.md#listbuildingsapiv1buildingsget) | **GET** /api/v1/buildings | List Buildings
*BuildingsApi* | [**updateBuildingApiV1BuildingsBuildingIdPatch**](docs/BuildingsApi.md#updatebuildingapiv1buildingsbuildingidpatch) | **PATCH** /api/v1/buildings/{building_id} | Update Building
*BuildingsApi* | [**updateMeterBuildingsBuildingIdMetersMeterIdPatch**](docs/BuildingsApi.md#updatemeterbuildingsbuildingidmetersmeteridpatch) | **PATCH** /buildings/{building_id}/meters/{meter_id} | Update Meter
*BuildingsAdminApi* | [**addBuildingApiV1AdminBuildingsAddPost**](docs/BuildingsAdminApi.md#addbuildingapiv1adminbuildingsaddpost) | **POST** /api/v1/admin/buildings/add | Add Building
*BuildingsAdminApi* | [**addBuildingApiV1AdminBuildingsAddPost_0**](docs/BuildingsAdminApi.md#addbuildingapiv1adminbuildingsaddpost_0) | **POST** /api/v1/admin/buildings/add | Add Building
*BuildingsAdminApi* | [**deleteBuildingApiV1AdminBuildingsDeleteBuildingIdDelete**](docs/BuildingsAdminApi.md#deletebuildingapiv1adminbuildingsdeletebuildingiddelete) | **DELETE** /api/v1/admin/buildings/delete/{building_id} | Delete Building
*BuildingsAdminApi* | [**deleteBuildingApiV1AdminBuildingsDeleteBuildingIdDelete_0**](docs/BuildingsAdminApi.md#deletebuildingapiv1adminbuildingsdeletebuildingiddelete_0) | **DELETE** /api/v1/admin/buildings/delete/{building_id} | Delete Building
*BuildingsAdminApi* | [**updateBuildingApiV1AdminBuildingsUpdateBuildingIdPut**](docs/BuildingsAdminApi.md#updatebuildingapiv1adminbuildingsupdatebuildingidput) | **PUT** /api/v1/admin/buildings/update/{building_id} | Update Building
*BuildingsAdminApi* | [**updateBuildingApiV1AdminBuildingsUpdateBuildingIdPut_0**](docs/BuildingsAdminApi.md#updatebuildingapiv1adminbuildingsupdatebuildingidput_0) | **PUT** /api/v1/admin/buildings/update/{building_id} | Update Building
*BuildingsMapApi* | [**geocodeOneBuildingApiV1BuildingsBuildingIdGeocodePost**](docs/BuildingsMapApi.md#geocodeonebuildingapiv1buildingsbuildingidgeocodepost) | **POST** /api/v1/buildings/{building_id}/geocode | Geocode One Building
*BuildingsMapApi* | [**getBuildingsForMapApiV1BuildingsMapGet**](docs/BuildingsMapApi.md#getbuildingsformapapiv1buildingsmapget) | **GET** /api/v1/buildings/map | Get Buildings For Map
*CMSApi* | [**createBlogApiV1AdminCmsBlogPost**](docs/CMSApi.md#createblogapiv1admincmsblogpost) | **POST** /api/v1/admin/cms/blog | Create Blog
*CMSApi* | [**createBlogApiV1AdminCmsBlogPost_0**](docs/CMSApi.md#createblogapiv1admincmsblogpost_0) | **POST** /api/v1/admin/cms/blog | Create Blog
*CMSApi* | [**createChangelogApiV1AdminCmsChangelogPost**](docs/CMSApi.md#createchangelogapiv1admincmschangelogpost) | **POST** /api/v1/admin/cms/changelog | Create Changelog
*CMSApi* | [**createChangelogApiV1AdminCmsChangelogPost_0**](docs/CMSApi.md#createchangelogapiv1admincmschangelogpost_0) | **POST** /api/v1/admin/cms/changelog | Create Changelog
*CMSApi* | [**createPageApiV1AdminCmsPagesPost**](docs/CMSApi.md#createpageapiv1admincmspagespost) | **POST** /api/v1/admin/cms/pages | Create Page
*CMSApi* | [**createPageApiV1AdminCmsPagesPost_0**](docs/CMSApi.md#createpageapiv1admincmspagespost_0) | **POST** /api/v1/admin/cms/pages | Create Page
*CMSApi* | [**deleteAssetApiV1AdminCmsAssetsAidDelete**](docs/CMSApi.md#deleteassetapiv1admincmsassetsaiddelete) | **DELETE** /api/v1/admin/cms/assets/{aid} | Delete Asset
*CMSApi* | [**deleteAssetApiV1AdminCmsAssetsAidDelete_0**](docs/CMSApi.md#deleteassetapiv1admincmsassetsaiddelete_0) | **DELETE** /api/v1/admin/cms/assets/{aid} | Delete Asset
*CMSApi* | [**deleteBlogApiV1AdminCmsBlogSlugDelete**](docs/CMSApi.md#deleteblogapiv1admincmsblogslugdelete) | **DELETE** /api/v1/admin/cms/blog/{slug} | Delete Blog
*CMSApi* | [**deleteBlogApiV1AdminCmsBlogSlugDelete_0**](docs/CMSApi.md#deleteblogapiv1admincmsblogslugdelete_0) | **DELETE** /api/v1/admin/cms/blog/{slug} | Delete Blog
*CMSApi* | [**deleteChangelogApiV1AdminCmsChangelogCidDelete**](docs/CMSApi.md#deletechangelogapiv1admincmschangelogciddelete) | **DELETE** /api/v1/admin/cms/changelog/{cid} | Delete Changelog
*CMSApi* | [**deleteChangelogApiV1AdminCmsChangelogCidDelete_0**](docs/CMSApi.md#deletechangelogapiv1admincmschangelogciddelete_0) | **DELETE** /api/v1/admin/cms/changelog/{cid} | Delete Changelog
*CMSApi* | [**deleteContentApiV1AdminCmsContentPageSectionDelete**](docs/CMSApi.md#deletecontentapiv1admincmscontentpagesectiondelete) | **DELETE** /api/v1/admin/cms/content/{page}/{section} | Delete Content
*CMSApi* | [**deleteContentApiV1AdminCmsContentPageSectionDelete_0**](docs/CMSApi.md#deletecontentapiv1admincmscontentpagesectiondelete_0) | **DELETE** /api/v1/admin/cms/content/{page}/{section} | Delete Content
*CMSApi* | [**deletePageApiV1AdminCmsPagesSlugDelete**](docs/CMSApi.md#deletepageapiv1admincmspagesslugdelete) | **DELETE** /api/v1/admin/cms/pages/{slug} | Delete Page
*CMSApi* | [**deletePageApiV1AdminCmsPagesSlugDelete_0**](docs/CMSApi.md#deletepageapiv1admincmspagesslugdelete_0) | **DELETE** /api/v1/admin/cms/pages/{slug} | Delete Page
*CMSApi* | [**getBlogApiV1AdminCmsBlogSlugGet**](docs/CMSApi.md#getblogapiv1admincmsblogslugget) | **GET** /api/v1/admin/cms/blog/{slug} | Get Blog
*CMSApi* | [**getBlogApiV1AdminCmsBlogSlugGet_0**](docs/CMSApi.md#getblogapiv1admincmsblogslugget_0) | **GET** /api/v1/admin/cms/blog/{slug} | Get Blog
*CMSApi* | [**getContentApiV1AdminCmsContentPageSectionGet**](docs/CMSApi.md#getcontentapiv1admincmscontentpagesectionget) | **GET** /api/v1/admin/cms/content/{page}/{section} | Get Content
*CMSApi* | [**getContentApiV1AdminCmsContentPageSectionGet_0**](docs/CMSApi.md#getcontentapiv1admincmscontentpagesectionget_0) | **GET** /api/v1/admin/cms/content/{page}/{section} | Get Content
*CMSApi* | [**listAssetsApiV1AdminCmsAssetsGet**](docs/CMSApi.md#listassetsapiv1admincmsassetsget) | **GET** /api/v1/admin/cms/assets | List Assets
*CMSApi* | [**listAssetsApiV1AdminCmsAssetsGet_0**](docs/CMSApi.md#listassetsapiv1admincmsassetsget_0) | **GET** /api/v1/admin/cms/assets | List Assets
*CMSApi* | [**listBlogApiV1AdminCmsBlogGet**](docs/CMSApi.md#listblogapiv1admincmsblogget) | **GET** /api/v1/admin/cms/blog | List Blog
*CMSApi* | [**listBlogApiV1AdminCmsBlogGet_0**](docs/CMSApi.md#listblogapiv1admincmsblogget_0) | **GET** /api/v1/admin/cms/blog | List Blog
*CMSApi* | [**listChangelogApiV1AdminCmsChangelogGet**](docs/CMSApi.md#listchangelogapiv1admincmschangelogget) | **GET** /api/v1/admin/cms/changelog | List Changelog
*CMSApi* | [**listChangelogApiV1AdminCmsChangelogGet_0**](docs/CMSApi.md#listchangelogapiv1admincmschangelogget_0) | **GET** /api/v1/admin/cms/changelog | List Changelog
*CMSApi* | [**listContentApiV1AdminCmsContentGet**](docs/CMSApi.md#listcontentapiv1admincmscontentget) | **GET** /api/v1/admin/cms/content | List Content
*CMSApi* | [**listContentApiV1AdminCmsContentGet_0**](docs/CMSApi.md#listcontentapiv1admincmscontentget_0) | **GET** /api/v1/admin/cms/content | List Content
*CMSApi* | [**listPagesApiV1AdminCmsPagesGet**](docs/CMSApi.md#listpagesapiv1admincmspagesget) | **GET** /api/v1/admin/cms/pages | List Pages
*CMSApi* | [**listPagesApiV1AdminCmsPagesGet_0**](docs/CMSApi.md#listpagesapiv1admincmspagesget_0) | **GET** /api/v1/admin/cms/pages | List Pages
*CMSApi* | [**listTogglesApiV1AdminCmsFeatureTogglesGet**](docs/CMSApi.md#listtogglesapiv1admincmsfeaturetogglesget) | **GET** /api/v1/admin/cms/feature-toggles | List Toggles
*CMSApi* | [**listTogglesApiV1AdminCmsFeatureTogglesGet_0**](docs/CMSApi.md#listtogglesapiv1admincmsfeaturetogglesget_0) | **GET** /api/v1/admin/cms/feature-toggles | List Toggles
*CMSApi* | [**listVersionsApiV1AdminCmsContentPageSectionVersionsGet**](docs/CMSApi.md#listversionsapiv1admincmscontentpagesectionversionsget) | **GET** /api/v1/admin/cms/content/{page}/{section}/versions | List Versions
*CMSApi* | [**listVersionsApiV1AdminCmsContentPageSectionVersionsGet_0**](docs/CMSApi.md#listversionsapiv1admincmscontentpagesectionversionsget_0) | **GET** /api/v1/admin/cms/content/{page}/{section}/versions | List Versions
*CMSApi* | [**rollbackContentApiV1AdminCmsContentPageSectionRollbackVersionPost**](docs/CMSApi.md#rollbackcontentapiv1admincmscontentpagesectionrollbackversionpost) | **POST** /api/v1/admin/cms/content/{page}/{section}/rollback/{version} | Rollback Content
*CMSApi* | [**rollbackContentApiV1AdminCmsContentPageSectionRollbackVersionPost_0**](docs/CMSApi.md#rollbackcontentapiv1admincmscontentpagesectionrollbackversionpost_0) | **POST** /api/v1/admin/cms/content/{page}/{section}/rollback/{version} | Rollback Content
*CMSApi* | [**updateBlogApiV1AdminCmsBlogSlugPatch**](docs/CMSApi.md#updateblogapiv1admincmsblogslugpatch) | **PATCH** /api/v1/admin/cms/blog/{slug} | Update Blog
*CMSApi* | [**updateBlogApiV1AdminCmsBlogSlugPatch_0**](docs/CMSApi.md#updateblogapiv1admincmsblogslugpatch_0) | **PATCH** /api/v1/admin/cms/blog/{slug} | Update Blog
*CMSApi* | [**updateContentApiV1AdminCmsContentPageSectionPut**](docs/CMSApi.md#updatecontentapiv1admincmscontentpagesectionput) | **PUT** /api/v1/admin/cms/content/{page}/{section} | Update Content
*CMSApi* | [**updateContentApiV1AdminCmsContentPageSectionPut_0**](docs/CMSApi.md#updatecontentapiv1admincmscontentpagesectionput_0) | **PUT** /api/v1/admin/cms/content/{page}/{section} | Update Content
*CMSApi* | [**updatePageApiV1AdminCmsPagesSlugPatch**](docs/CMSApi.md#updatepageapiv1admincmspagesslugpatch) | **PATCH** /api/v1/admin/cms/pages/{slug} | Update Page
*CMSApi* | [**updatePageApiV1AdminCmsPagesSlugPatch_0**](docs/CMSApi.md#updatepageapiv1admincmspagesslugpatch_0) | **PATCH** /api/v1/admin/cms/pages/{slug} | Update Page
*CMSApi* | [**uploadAssetApiV1AdminCmsAssetsPost**](docs/CMSApi.md#uploadassetapiv1admincmsassetspost) | **POST** /api/v1/admin/cms/assets | Upload Asset
*CMSApi* | [**uploadAssetApiV1AdminCmsAssetsPost_0**](docs/CMSApi.md#uploadassetapiv1admincmsassetspost_0) | **POST** /api/v1/admin/cms/assets | Upload Asset
*CMSApi* | [**upsertToggleApiV1AdminCmsFeatureTogglesPut**](docs/CMSApi.md#upserttoggleapiv1admincmsfeaturetogglesput) | **PUT** /api/v1/admin/cms/feature-toggles | Upsert Toggle
*CMSApi* | [**upsertToggleApiV1AdminCmsFeatureTogglesPut_0**](docs/CMSApi.md#upserttoggleapiv1admincmsfeaturetogglesput_0) | **PUT** /api/v1/admin/cms/feature-toggles | Upsert Toggle
*CMSBrandingPublicApi* | [**getBrandingFullApiV1CmsBrandingFullGet**](docs/CMSBrandingPublicApi.md#getbrandingfullapiv1cmsbrandingfullget) | **GET** /api/v1/cms/branding-full | Get Branding Full
*CMSBrandingPublicApi* | [**getBrandingFullApiV1CmsBrandingFullGet_0**](docs/CMSBrandingPublicApi.md#getbrandingfullapiv1cmsbrandingfullget_0) | **GET** /api/v1/cms/branding-full | Get Branding Full
*CMSBrandingPublicApi* | [**serveFaviconApiV1CmsFaviconGet**](docs/CMSBrandingPublicApi.md#servefaviconapiv1cmsfaviconget) | **GET** /api/v1/cms/favicon | Serve Favicon
*CMSBrandingPublicApi* | [**serveFaviconApiV1CmsFaviconGet_0**](docs/CMSBrandingPublicApi.md#servefaviconapiv1cmsfaviconget_0) | **GET** /api/v1/cms/favicon | Serve Favicon
*CMSPageBuilderApi* | [**addSectionApiV1AdminCmsPagesBuilderPageSectionsPost**](docs/CMSPageBuilderApi.md#addsectionapiv1admincmspagesbuilderpagesectionspost) | **POST** /api/v1/admin/cms/pages-builder/{page}/sections | Add Section
*CMSPageBuilderApi* | [**addSectionApiV1AdminCmsPagesBuilderPageSectionsPost_0**](docs/CMSPageBuilderApi.md#addsectionapiv1admincmspagesbuilderpagesectionspost_0) | **POST** /api/v1/admin/cms/pages-builder/{page}/sections | Add Section
*CMSPageBuilderApi* | [**listSectionsApiV1AdminCmsPagesBuilderPageSectionsGet**](docs/CMSPageBuilderApi.md#listsectionsapiv1admincmspagesbuilderpagesectionsget) | **GET** /api/v1/admin/cms/pages-builder/{page}/sections | List Sections
*CMSPageBuilderApi* | [**listSectionsApiV1AdminCmsPagesBuilderPageSectionsGet_0**](docs/CMSPageBuilderApi.md#listsectionsapiv1admincmspagesbuilderpagesectionsget_0) | **GET** /api/v1/admin/cms/pages-builder/{page}/sections | List Sections
*CMSPageBuilderApi* | [**reorderSectionsApiV1AdminCmsPagesBuilderPageReorderPut**](docs/CMSPageBuilderApi.md#reordersectionsapiv1admincmspagesbuilderpagereorderput) | **PUT** /api/v1/admin/cms/pages-builder/{page}/reorder | Reorder Sections
*CMSPageBuilderApi* | [**reorderSectionsApiV1AdminCmsPagesBuilderPageReorderPut_0**](docs/CMSPageBuilderApi.md#reordersectionsapiv1admincmspagesbuilderpagereorderput_0) | **PUT** /api/v1/admin/cms/pages-builder/{page}/reorder | Reorder Sections
*CMSPageBuilderPublicApi* | [**publicListSectionsApiV1CmsPageSectionsPageGet**](docs/CMSPageBuilderPublicApi.md#publiclistsectionsapiv1cmspagesectionspageget) | **GET** /api/v1/cms/page-sections/{page} | Public List Sections
*CMSPageBuilderPublicApi* | [**publicListSectionsApiV1CmsPageSectionsPageGet_0**](docs/CMSPageBuilderPublicApi.md#publiclistsectionsapiv1cmspagesectionspageget_0) | **GET** /api/v1/cms/page-sections/{page} | Public List Sections
*CMSPublicApi* | [**publicAnnouncementApiV1CmsAnnouncementGet**](docs/CMSPublicApi.md#publicannouncementapiv1cmsannouncementget) | **GET** /api/v1/cms/announcement | Public Announcement
*CMSPublicApi* | [**publicAnnouncementApiV1CmsAnnouncementGet_0**](docs/CMSPublicApi.md#publicannouncementapiv1cmsannouncementget_0) | **GET** /api/v1/cms/announcement | Public Announcement
*CMSPublicApi* | [**publicAssetApiV1CmsAssetAidGet**](docs/CMSPublicApi.md#publicassetapiv1cmsassetaidget) | **GET** /api/v1/cms/asset/{aid} | Public Asset
*CMSPublicApi* | [**publicAssetApiV1CmsAssetAidGet_0**](docs/CMSPublicApi.md#publicassetapiv1cmsassetaidget_0) | **GET** /api/v1/cms/asset/{aid} | Public Asset
*CMSPublicApi* | [**publicBlogGetApiV1CmsBlogSlugGet**](docs/CMSPublicApi.md#publicbloggetapiv1cmsblogslugget) | **GET** /api/v1/cms/blog/{slug} | Public Blog Get
*CMSPublicApi* | [**publicBlogGetApiV1CmsBlogSlugGet_0**](docs/CMSPublicApi.md#publicbloggetapiv1cmsblogslugget_0) | **GET** /api/v1/cms/blog/{slug} | Public Blog Get
*CMSPublicApi* | [**publicBlogListApiV1CmsBlogGet**](docs/CMSPublicApi.md#publicbloglistapiv1cmsblogget) | **GET** /api/v1/cms/blog | Public Blog List
*CMSPublicApi* | [**publicBlogListApiV1CmsBlogGet_0**](docs/CMSPublicApi.md#publicbloglistapiv1cmsblogget_0) | **GET** /api/v1/cms/blog | Public Blog List
*CMSPublicApi* | [**publicBrandingApiV1CmsBrandingGet**](docs/CMSPublicApi.md#publicbrandingapiv1cmsbrandingget) | **GET** /api/v1/cms/branding | Public Branding
*CMSPublicApi* | [**publicBrandingApiV1CmsBrandingGet_0**](docs/CMSPublicApi.md#publicbrandingapiv1cmsbrandingget_0) | **GET** /api/v1/cms/branding | Public Branding
*CMSPublicApi* | [**publicChangelogApiV1CmsChangelogGet**](docs/CMSPublicApi.md#publicchangelogapiv1cmschangelogget) | **GET** /api/v1/cms/changelog | Public Changelog
*CMSPublicApi* | [**publicChangelogApiV1CmsChangelogGet_0**](docs/CMSPublicApi.md#publicchangelogapiv1cmschangelogget_0) | **GET** /api/v1/cms/changelog | Public Changelog
*CMSPublicApi* | [**publicGetPageApiV1CmsContentPageGet**](docs/CMSPublicApi.md#publicgetpageapiv1cmscontentpageget) | **GET** /api/v1/cms/content/{page} | Public Get Page
*CMSPublicApi* | [**publicGetPageApiV1CmsContentPageGet_0**](docs/CMSPublicApi.md#publicgetpageapiv1cmscontentpageget_0) | **GET** /api/v1/cms/content/{page} | Public Get Page
*CarbonApi* | [**carbonReportApiV1CarbonPost**](docs/CarbonApi.md#carbonreportapiv1carbonpost) | **POST** /api/v1/carbon | Carbon Report
*ChatApi* | [**adminChatStatsApiV1ChatAdminStatsGet**](docs/ChatApi.md#adminchatstatsapiv1chatadminstatsget) | **GET** /api/v1/chat/admin/stats | Admin Chat Stats
*ChatApi* | [**adminConversationDetailApiV1ChatAdminConversationsConversationIdGet**](docs/ChatApi.md#adminconversationdetailapiv1chatadminconversationsconversationidget) | **GET** /api/v1/chat/admin/conversations/{conversation_id} | Admin Conversation Detail
*ChatApi* | [**adminGetChatConfigApiV1ChatAdminConfigGet**](docs/ChatApi.md#admingetchatconfigapiv1chatadminconfigget) | **GET** /api/v1/chat/admin/config | Admin Get Chat Config
*ChatApi* | [**adminGetWidgetsApiV1ChatAdminWidgetsGet**](docs/ChatApi.md#admingetwidgetsapiv1chatadminwidgetsget) | **GET** /api/v1/chat/admin/widgets | Admin Get Widgets
*ChatApi* | [**adminListConversationsApiV1ChatAdminConversationsGet**](docs/ChatApi.md#adminlistconversationsapiv1chatadminconversationsget) | **GET** /api/v1/chat/admin/conversations | Admin List Conversations
*ChatApi* | [**adminListLeadsApiV1ChatAdminLeadsGet**](docs/ChatApi.md#adminlistleadsapiv1chatadminleadsget) | **GET** /api/v1/chat/admin/leads | Admin List Leads
*ChatApi* | [**adminUpdateChatConfigApiV1ChatAdminConfigPut**](docs/ChatApi.md#adminupdatechatconfigapiv1chatadminconfigput) | **PUT** /api/v1/chat/admin/config | Admin Update Chat Config
*ChatApi* | [**adminUpdateLeadStatusApiV1ChatAdminLeadsLeadIdStatusPut**](docs/ChatApi.md#adminupdateleadstatusapiv1chatadminleadsleadidstatusput) | **PUT** /api/v1/chat/admin/leads/{lead_id}/status | Admin Update Lead Status
*ChatApi* | [**adminUpdateWidgetPromptApiV1ChatAdminWidgetsWidgetIdPromptPut**](docs/ChatApi.md#adminupdatewidgetpromptapiv1chatadminwidgetswidgetidpromptput) | **PUT** /api/v1/chat/admin/widgets/{widget_id}/prompt | Admin Update Widget Prompt
*ChatApi* | [**captureChatLeadApiV1ChatLeadPost**](docs/ChatApi.md#capturechatleadapiv1chatleadpost) | **POST** /api/v1/chat/lead | Capture Chat Lead
*ChatApi* | [**chatMessageApiV1ChatMessagePost**](docs/ChatApi.md#chatmessageapiv1chatmessagepost) | **POST** /api/v1/chat/message | Chat Message
*ChatApi* | [**chatMessageAuthenticatedApiV1ChatMessageAuthenticatedPost**](docs/ChatApi.md#chatmessageauthenticatedapiv1chatmessageauthenticatedpost) | **POST** /api/v1/chat/message/authenticated | Chat Message Authenticated
*ChatApi* | [**getChatConfigApiV1ChatConfigGet**](docs/ChatApi.md#getchatconfigapiv1chatconfigget) | **GET** /api/v1/chat/config | Get Chat Config
*ChatApi* | [**getChatHistoryApiV1ChatHistorySessionIdGet**](docs/ChatApi.md#getchathistoryapiv1chathistorysessionidget) | **GET** /api/v1/chat/history/{session_id} | Get Chat History
*ComplianceApi* | [**generateEricApiV1ComplianceEricPost**](docs/ComplianceApi.md#generateericapiv1complianceericpost) | **POST** /api/v1/compliance/eric | Generate Eric
*ComplianceApi* | [**generateEricApiV1ComplianceEricPost_0**](docs/ComplianceApi.md#generateericapiv1complianceericpost_0) | **POST** /api/v1/compliance/eric | Generate Eric
*ComplianceApi* | [**generateEsosApiV1ComplianceEsosPost**](docs/ComplianceApi.md#generateesosapiv1complianceesospost) | **POST** /api/v1/compliance/esos | Generate Esos
*ComplianceApi* | [**generateEsosApiV1ComplianceEsosPost_0**](docs/ComplianceApi.md#generateesosapiv1complianceesospost_0) | **POST** /api/v1/compliance/esos | Generate Esos
*ComplianceApi* | [**generateSecrApiV1ComplianceSecrPost**](docs/ComplianceApi.md#generatesecrapiv1compliancesecrpost) | **POST** /api/v1/compliance/secr | Generate Secr
*ComplianceApi* | [**generateSecrApiV1ComplianceSecrPost_0**](docs/ComplianceApi.md#generatesecrapiv1compliancesecrpost_0) | **POST** /api/v1/compliance/secr | Generate Secr
*ComplianceApi* | [**generateShdfApiV1ComplianceShdfPost**](docs/ComplianceApi.md#generateshdfapiv1complianceshdfpost) | **POST** /api/v1/compliance/shdf | Generate Shdf
*ComplianceApi* | [**generateShdfApiV1ComplianceShdfPost_0**](docs/ComplianceApi.md#generateshdfapiv1complianceshdfpost_0) | **POST** /api/v1/compliance/shdf | Generate Shdf
*ComplianceApi* | [**getEpcTrackingApiV1ComplianceEpcGet**](docs/ComplianceApi.md#getepctrackingapiv1complianceepcget) | **GET** /api/v1/compliance/epc | Get Epc Tracking
*ComplianceApi* | [**getEpcTrackingApiV1ComplianceEpcGet_0**](docs/ComplianceApi.md#getepctrackingapiv1complianceepcget_0) | **GET** /api/v1/compliance/epc | Get Epc Tracking
*EmailProvidersApi* | [**activateProviderApiV1AdminEmailProvidersKindActivatePost**](docs/EmailProvidersApi.md#activateproviderapiv1adminemailproviderskindactivatepost) | **POST** /api/v1/admin/email-providers/{kind}/activate | Activate Provider
*EmailProvidersApi* | [**activateProviderApiV1AdminEmailProvidersKindActivatePost_0**](docs/EmailProvidersApi.md#activateproviderapiv1adminemailproviderskindactivatepost_0) | **POST** /api/v1/admin/email-providers/{kind}/activate | Activate Provider
*EmailProvidersApi* | [**getProviderApiV1AdminEmailProvidersKindGet**](docs/EmailProvidersApi.md#getproviderapiv1adminemailproviderskindget) | **GET** /api/v1/admin/email-providers/{kind} | Get Provider
*EmailProvidersApi* | [**getProviderApiV1AdminEmailProvidersKindGet_0**](docs/EmailProvidersApi.md#getproviderapiv1adminemailproviderskindget_0) | **GET** /api/v1/admin/email-providers/{kind} | Get Provider
*EmailProvidersApi* | [**getRegistryApiV1AdminEmailProvidersTypesRegistryGet**](docs/EmailProvidersApi.md#getregistryapiv1adminemailproviderstypesregistryget) | **GET** /api/v1/admin/email-providers/types/registry | Get Registry
*EmailProvidersApi* | [**getRegistryApiV1AdminEmailProvidersTypesRegistryGet_0**](docs/EmailProvidersApi.md#getregistryapiv1adminemailproviderstypesregistryget_0) | **GET** /api/v1/admin/email-providers/types/registry | Get Registry
*EmailProvidersApi* | [**listProvidersApiV1AdminEmailProvidersGet**](docs/EmailProvidersApi.md#listprovidersapiv1adminemailprovidersget) | **GET** /api/v1/admin/email-providers | List Providers
*EmailProvidersApi* | [**listProvidersApiV1AdminEmailProvidersGet_0**](docs/EmailProvidersApi.md#listprovidersapiv1adminemailprovidersget_0) | **GET** /api/v1/admin/email-providers | List Providers
*EmailProvidersApi* | [**testProviderApiV1AdminEmailProvidersKindTestPost**](docs/EmailProvidersApi.md#testproviderapiv1adminemailproviderskindtestpost) | **POST** /api/v1/admin/email-providers/{kind}/test | Test Provider
*EmailProvidersApi* | [**testProviderApiV1AdminEmailProvidersKindTestPost_0**](docs/EmailProvidersApi.md#testproviderapiv1adminemailproviderskindtestpost_0) | **POST** /api/v1/admin/email-providers/{kind}/test | Test Provider
*EmailProvidersApi* | [**updateProviderApiV1AdminEmailProvidersKindPut**](docs/EmailProvidersApi.md#updateproviderapiv1adminemailproviderskindput) | **PUT** /api/v1/admin/email-providers/{kind} | Update Provider
*EmailProvidersApi* | [**updateProviderApiV1AdminEmailProvidersKindPut_0**](docs/EmailProvidersApi.md#updateproviderapiv1adminemailproviderskindput_0) | **PUT** /api/v1/admin/email-providers/{kind} | Update Provider
*EmailTemplatesApi* | [**getTemplateApiV1AdminEmailTemplatesKeyGet**](docs/EmailTemplatesApi.md#gettemplateapiv1adminemailtemplateskeyget) | **GET** /api/v1/admin/email-templates/{key} | Get Template
*EmailTemplatesApi* | [**getTemplateApiV1AdminEmailTemplatesKeyGet_0**](docs/EmailTemplatesApi.md#gettemplateapiv1adminemailtemplateskeyget_0) | **GET** /api/v1/admin/email-templates/{key} | Get Template
*EmailTemplatesApi* | [**listTemplatesApiV1AdminEmailTemplatesGet**](docs/EmailTemplatesApi.md#listtemplatesapiv1adminemailtemplatesget) | **GET** /api/v1/admin/email-templates | List Templates
*EmailTemplatesApi* | [**listTemplatesApiV1AdminEmailTemplatesGet_0**](docs/EmailTemplatesApi.md#listtemplatesapiv1adminemailtemplatesget_0) | **GET** /api/v1/admin/email-templates | List Templates
*EmailTemplatesApi* | [**previewTemplateApiV1AdminEmailTemplatesKeyPreviewPost**](docs/EmailTemplatesApi.md#previewtemplateapiv1adminemailtemplateskeypreviewpost) | **POST** /api/v1/admin/email-templates/{key}/preview | Preview Template
*EmailTemplatesApi* | [**previewTemplateApiV1AdminEmailTemplatesKeyPreviewPost_0**](docs/EmailTemplatesApi.md#previewtemplateapiv1adminemailtemplateskeypreviewpost_0) | **POST** /api/v1/admin/email-templates/{key}/preview | Preview Template
*EmailTemplatesApi* | [**resetTemplateApiV1AdminEmailTemplatesKeyResetPost**](docs/EmailTemplatesApi.md#resettemplateapiv1adminemailtemplateskeyresetpost) | **POST** /api/v1/admin/email-templates/{key}/reset | Reset Template
*EmailTemplatesApi* | [**resetTemplateApiV1AdminEmailTemplatesKeyResetPost_0**](docs/EmailTemplatesApi.md#resettemplateapiv1adminemailtemplateskeyresetpost_0) | **POST** /api/v1/admin/email-templates/{key}/reset | Reset Template
*EmailTemplatesApi* | [**sendTestApiV1AdminEmailTemplatesKeySendTestPost**](docs/EmailTemplatesApi.md#sendtestapiv1adminemailtemplateskeysendtestpost) | **POST** /api/v1/admin/email-templates/{key}/send-test | Send Test
*EmailTemplatesApi* | [**sendTestApiV1AdminEmailTemplatesKeySendTestPost_0**](docs/EmailTemplatesApi.md#sendtestapiv1adminemailtemplateskeysendtestpost_0) | **POST** /api/v1/admin/email-templates/{key}/send-test | Send Test
*EmailTemplatesApi* | [**updateTemplateApiV1AdminEmailTemplatesKeyPut**](docs/EmailTemplatesApi.md#updatetemplateapiv1adminemailtemplateskeyput) | **PUT** /api/v1/admin/email-templates/{key} | Update Template
*EmailTemplatesApi* | [**updateTemplateApiV1AdminEmailTemplatesKeyPut_0**](docs/EmailTemplatesApi.md#updatetemplateapiv1adminemailtemplateskeyput_0) | **PUT** /api/v1/admin/email-templates/{key} | Update Template
*EnergyApi* | [**energyForecastApiV1EnergyForecastPost**](docs/EnergyApi.md#energyforecastapiv1energyforecastpost) | **POST** /api/v1/energy/forecast | Energy Forecast
*EnergyApi* | [**energyForecastApiV1EnergyForecastPost_0**](docs/EnergyApi.md#energyforecastapiv1energyforecastpost_0) | **POST** /api/v1/energy/forecast | Energy Forecast
*EnergyApi* | [**getEnergyTypesApiV1EnergyTypesGet**](docs/EnergyApi.md#getenergytypesapiv1energytypesget) | **GET** /api/v1/energy/types | Get Energy Types
*EnergyApi* | [**getEnergyTypesApiV1EnergyTypesGet_0**](docs/EnergyApi.md#getenergytypesapiv1energytypesget_0) | **GET** /api/v1/energy/types | Get Energy Types
*EnergyApi* | [**getWeatherDataApiV1EnergyWeatherGet**](docs/EnergyApi.md#getweatherdataapiv1energyweatherget) | **GET** /api/v1/energy/weather | Get Weather Data
*EnergyApi* | [**getWeatherDataApiV1EnergyWeatherGet_0**](docs/EnergyApi.md#getweatherdataapiv1energyweatherget_0) | **GET** /api/v1/energy/weather | Get Weather Data
*EnergyApi* | [**toggleEnergyTypeApiV1EnergyTypesTogglePost**](docs/EnergyApi.md#toggleenergytypeapiv1energytypestogglepost) | **POST** /api/v1/energy/types/toggle | Toggle Energy Type
*EnergyApi* | [**toggleEnergyTypeApiV1EnergyTypesTogglePost_0**](docs/EnergyApi.md#toggleenergytypeapiv1energytypestogglepost_0) | **POST** /api/v1/energy/types/toggle | Toggle Energy Type
*EngineeringApi* | [**budgetForecastApiV1EngineeringBudgetForecastPost**](docs/EngineeringApi.md#budgetforecastapiv1engineeringbudgetforecastpost) | **POST** /api/v1/engineering/budget-forecast | Budget Forecast
*EngineeringApi* | [**budgetForecastApiV1EngineeringBudgetForecastPost_0**](docs/EngineeringApi.md#budgetforecastapiv1engineeringbudgetforecastpost_0) | **POST** /api/v1/engineering/budget-forecast | Budget Forecast
*EngineeringApi* | [**costAvoidanceApiV1EngineeringCostAvoidancePost**](docs/EngineeringApi.md#costavoidanceapiv1engineeringcostavoidancepost) | **POST** /api/v1/engineering/cost-avoidance | Cost Avoidance
*EngineeringApi* | [**costAvoidanceApiV1EngineeringCostAvoidancePost_0**](docs/EngineeringApi.md#costavoidanceapiv1engineeringcostavoidancepost_0) | **POST** /api/v1/engineering/cost-avoidance | Cost Avoidance
*EngineeringApi* | [**costTrendingApiV1EngineeringCostTrendPost**](docs/EngineeringApi.md#costtrendingapiv1engineeringcosttrendpost) | **POST** /api/v1/engineering/cost-trend | Cost Trending
*EngineeringApi* | [**costTrendingApiV1EngineeringCostTrendPost_0**](docs/EngineeringApi.md#costtrendingapiv1engineeringcosttrendpost_0) | **POST** /api/v1/engineering/cost-trend | Cost Trending
*EngineeringApi* | [**decRatingApiV1EngineeringDecRatingPost**](docs/EngineeringApi.md#decratingapiv1engineeringdecratingpost) | **POST** /api/v1/engineering/dec-rating | Dec Rating
*EngineeringApi* | [**decRatingApiV1EngineeringDecRatingPost_0**](docs/EngineeringApi.md#decratingapiv1engineeringdecratingpost_0) | **POST** /api/v1/engineering/dec-rating | Dec Rating
*EngineeringApi* | [**defraFactorsApiV1EngineeringDefraFactorsGet**](docs/EngineeringApi.md#defrafactorsapiv1engineeringdefrafactorsget) | **GET** /api/v1/engineering/defra-factors | Defra Factors
*EngineeringApi* | [**defraFactorsApiV1EngineeringDefraFactorsGet_0**](docs/EngineeringApi.md#defrafactorsapiv1engineeringdefrafactorsget_0) | **GET** /api/v1/engineering/defra-factors | Defra Factors
*EngineeringApi* | [**degreeDayNormalisationApiV1EngineeringDegreeDaysPost**](docs/EngineeringApi.md#degreedaynormalisationapiv1engineeringdegreedayspost) | **POST** /api/v1/engineering/degree-days | Degree Day Normalisation
*EngineeringApi* | [**degreeDayNormalisationApiV1EngineeringDegreeDaysPost_0**](docs/EngineeringApi.md#degreedaynormalisationapiv1engineeringdegreedayspost_0) | **POST** /api/v1/engineering/degree-days | Degree Day Normalisation
*EngineeringApi* | [**energyUseIntensityApiV1EngineeringEuiPost**](docs/EngineeringApi.md#energyuseintensityapiv1engineeringeuipost) | **POST** /api/v1/engineering/eui | Energy Use Intensity
*EngineeringApi* | [**energyUseIntensityApiV1EngineeringEuiPost_0**](docs/EngineeringApi.md#energyuseintensityapiv1engineeringeuipost_0) | **POST** /api/v1/engineering/eui | Energy Use Intensity
*EngineeringApi* | [**epcEstimateApiV1EngineeringEpcEstimatePost**](docs/EngineeringApi.md#epcestimateapiv1engineeringepcestimatepost) | **POST** /api/v1/engineering/epc-estimate | Epc Estimate
*EngineeringApi* | [**epcEstimateApiV1EngineeringEpcEstimatePost_0**](docs/EngineeringApi.md#epcestimateapiv1engineeringepcestimatepost_0) | **POST** /api/v1/engineering/epc-estimate | Epc Estimate
*EngineeringApi* | [**esosThresholdApiV1EngineeringEsosThresholdPost**](docs/EngineeringApi.md#esosthresholdapiv1engineeringesosthresholdpost) | **POST** /api/v1/engineering/esos-threshold | Esos Threshold
*EngineeringApi* | [**esosThresholdApiV1EngineeringEsosThresholdPost_0**](docs/EngineeringApi.md#esosthresholdapiv1engineeringesosthresholdpost_0) | **POST** /api/v1/engineering/esos-threshold | Esos Threshold
*EngineeringApi* | [**heatLossCalculationApiV1EngineeringHeatLossPost**](docs/EngineeringApi.md#heatlosscalculationapiv1engineeringheatlosspost) | **POST** /api/v1/engineering/heat-loss | Heat Loss Calculation
*EngineeringApi* | [**heatLossCalculationApiV1EngineeringHeatLossPost_0**](docs/EngineeringApi.md#heatlosscalculationapiv1engineeringheatlosspost_0) | **POST** /api/v1/engineering/heat-loss | Heat Loss Calculation
*EngineeringApi* | [**movingAverageBaselineApiV1EngineeringMovingAveragePost**](docs/EngineeringApi.md#movingaveragebaselineapiv1engineeringmovingaveragepost) | **POST** /api/v1/engineering/moving-average | Moving Average Baseline
*EngineeringApi* | [**movingAverageBaselineApiV1EngineeringMovingAveragePost_0**](docs/EngineeringApi.md#movingaveragebaselineapiv1engineeringmovingaveragepost_0) | **POST** /api/v1/engineering/moving-average | Moving Average Baseline
*EngineeringApi* | [**netPresentValueApiV1EngineeringNpvPost**](docs/EngineeringApi.md#netpresentvalueapiv1engineeringnpvpost) | **POST** /api/v1/engineering/npv | Net Present Value
*EngineeringApi* | [**netPresentValueApiV1EngineeringNpvPost_0**](docs/EngineeringApi.md#netpresentvalueapiv1engineeringnpvpost_0) | **POST** /api/v1/engineering/npv | Net Present Value
*EngineeringApi* | [**paybackCalculatorApiV1EngineeringPaybackPost**](docs/EngineeringApi.md#paybackcalculatorapiv1engineeringpaybackpost) | **POST** /api/v1/engineering/payback | Payback Calculator
*EngineeringApi* | [**paybackCalculatorApiV1EngineeringPaybackPost_0**](docs/EngineeringApi.md#paybackcalculatorapiv1engineeringpaybackpost_0) | **POST** /api/v1/engineering/payback | Payback Calculator
*EngineeringApi* | [**roiCalculatorApiV1EngineeringRoiPost**](docs/EngineeringApi.md#roicalculatorapiv1engineeringroipost) | **POST** /api/v1/engineering/roi | Roi Calculator
*EngineeringApi* | [**roiCalculatorApiV1EngineeringRoiPost_0**](docs/EngineeringApi.md#roicalculatorapiv1engineeringroipost_0) | **POST** /api/v1/engineering/roi | Roi Calculator
*EngineeringApi* | [**sapRatingApiV1EngineeringSapRatingPost**](docs/EngineeringApi.md#sapratingapiv1engineeringsapratingpost) | **POST** /api/v1/engineering/sap-rating | Sap Rating
*EngineeringApi* | [**sapRatingApiV1EngineeringSapRatingPost_0**](docs/EngineeringApi.md#sapratingapiv1engineeringsapratingpost_0) | **POST** /api/v1/engineering/sap-rating | Sap Rating
*EngineeringApi* | [**secrIntensityApiV1EngineeringSecrIntensityPost**](docs/EngineeringApi.md#secrintensityapiv1engineeringsecrintensitypost) | **POST** /api/v1/engineering/secr-intensity | Secr Intensity
*EngineeringApi* | [**secrIntensityApiV1EngineeringSecrIntensityPost_0**](docs/EngineeringApi.md#secrintensityapiv1engineeringsecrintensitypost_0) | **POST** /api/v1/engineering/secr-intensity | Secr Intensity
*EngineeringApi* | [**stdDeviationAnomalyApiV1EngineeringStdAnomalyPost**](docs/EngineeringApi.md#stddeviationanomalyapiv1engineeringstdanomalypost) | **POST** /api/v1/engineering/std-anomaly | Std Deviation Anomaly
*EngineeringApi* | [**stdDeviationAnomalyApiV1EngineeringStdAnomalyPost_0**](docs/EngineeringApi.md#stddeviationanomalyapiv1engineeringstdanomalypost_0) | **POST** /api/v1/engineering/std-anomaly | Std Deviation Anomaly
*EngineeringApi* | [**tariffComparisonApiV1EngineeringTariffComparePost**](docs/EngineeringApi.md#tariffcomparisonapiv1engineeringtariffcomparepost) | **POST** /api/v1/engineering/tariff-compare | Tariff Comparison
*EngineeringApi* | [**tariffComparisonApiV1EngineeringTariffComparePost_0**](docs/EngineeringApi.md#tariffcomparisonapiv1engineeringtariffcomparepost_0) | **POST** /api/v1/engineering/tariff-compare | Tariff Comparison
*EngineeringApi* | [**thermalComfortApiV1EngineeringThermalComfortPost**](docs/EngineeringApi.md#thermalcomfortapiv1engineeringthermalcomfortpost) | **POST** /api/v1/engineering/thermal-comfort | Thermal Comfort
*EngineeringApi* | [**thermalComfortApiV1EngineeringThermalComfortPost_0**](docs/EngineeringApi.md#thermalcomfortapiv1engineeringthermalcomfortpost_0) | **POST** /api/v1/engineering/thermal-comfort | Thermal Comfort
*ForecastApi* | [**forecastApiV1ForecastPost**](docs/ForecastApi.md#forecastapiv1forecastpost) | **POST** /api/v1/forecast | Forecast
*IngestApi* | [**ingestApiV1IngestPost**](docs/IngestApi.md#ingestapiv1ingestpost) | **POST** /api/v1/ingest | Ingest
*MLOpsApi* | [**createTrainingJobApiV1AdminMlopsTrainingJobsPost**](docs/MLOpsApi.md#createtrainingjobapiv1adminmlopstrainingjobspost) | **POST** /api/v1/admin/mlops/training-jobs | Create Training Job
*MLOpsApi* | [**getModelPerformanceApiV1AdminMlopsPerformanceGet**](docs/MLOpsApi.md#getmodelperformanceapiv1adminmlopsperformanceget) | **GET** /api/v1/admin/mlops/performance | Get Model Performance
*MLOpsApi* | [**listCheckpointsDetailedApiV1AdminMlopsCheckpointsGet**](docs/MLOpsApi.md#listcheckpointsdetailedapiv1adminmlopscheckpointsget) | **GET** /api/v1/admin/mlops/checkpoints | List Checkpoints Detailed
*MLOpsApi* | [**listTrainingJobsApiV1AdminMlopsTrainingJobsGet**](docs/MLOpsApi.md#listtrainingjobsapiv1adminmlopstrainingjobsget) | **GET** /api/v1/admin/mlops/training-jobs | List Training Jobs
*MLOpsApi* | [**setRetrainScheduleApiV1AdminMlopsSchedulePost**](docs/MLOpsApi.md#setretrainscheduleapiv1adminmlopsschedulepost) | **POST** /api/v1/admin/mlops/schedule | Set Retrain Schedule
*MLOpsApi* | [**updateTrainingJobApiV1AdminMlopsTrainingJobsJobIdPatch**](docs/MLOpsApi.md#updatetrainingjobapiv1adminmlopstrainingjobsjobidpatch) | **PATCH** /api/v1/admin/mlops/training-jobs/{job_id} | Update Training Job
*MetersApi* | [**listMetersApiV1MetersGet**](docs/MetersApi.md#listmetersapiv1metersget) | **GET** /api/v1/meters | List Meters
*NotificationsApi* | [**clearNotificationsApiV1NotificationsDelete**](docs/NotificationsApi.md#clearnotificationsapiv1notificationsdelete) | **DELETE** /api/v1/notifications | Clear Notifications
*NotificationsApi* | [**clearNotificationsApiV1NotificationsDelete_0**](docs/NotificationsApi.md#clearnotificationsapiv1notificationsdelete_0) | **DELETE** /api/v1/notifications | Clear Notifications
*NotificationsApi* | [**listNotificationsApiV1NotificationsGet**](docs/NotificationsApi.md#listnotificationsapiv1notificationsget) | **GET** /api/v1/notifications | List Notifications
*NotificationsApi* | [**listNotificationsApiV1NotificationsGet_0**](docs/NotificationsApi.md#listnotificationsapiv1notificationsget_0) | **GET** /api/v1/notifications | List Notifications
*NotificationsApi* | [**markReadApiV1NotificationsReadPost**](docs/NotificationsApi.md#markreadapiv1notificationsreadpost) | **POST** /api/v1/notifications/read | Mark Read
*NotificationsApi* | [**markReadApiV1NotificationsReadPost_0**](docs/NotificationsApi.md#markreadapiv1notificationsreadpost_0) | **POST** /api/v1/notifications/read | Mark Read
*NotificationsApi* | [**unreadCountApiV1NotificationsUnreadCountGet**](docs/NotificationsApi.md#unreadcountapiv1notificationsunreadcountget) | **GET** /api/v1/notifications/unread-count | Unread Count
*NotificationsApi* | [**unreadCountApiV1NotificationsUnreadCountGet_0**](docs/NotificationsApi.md#unreadcountapiv1notificationsunreadcountget_0) | **GET** /api/v1/notifications/unread-count | Unread Count
*OnboardingApi* | [**completeTourApiV1OnboardingCompleteTourPost**](docs/OnboardingApi.md#completetourapiv1onboardingcompletetourpost) | **POST** /api/v1/onboarding/complete-tour | Complete Tour
*OnboardingApi* | [**dismissChecklistApiV1OnboardingDismissPost**](docs/OnboardingApi.md#dismisschecklistapiv1onboardingdismisspost) | **POST** /api/v1/onboarding/dismiss | Dismiss Checklist
*OnboardingApi* | [**getStatusApiV1OnboardingStatusGet**](docs/OnboardingApi.md#getstatusapiv1onboardingstatusget) | **GET** /api/v1/onboarding/status | Get Status
*OnboardingApi* | [**markForecastRunApiV1OnboardingMarkForecastRunPost**](docs/OnboardingApi.md#markforecastrunapiv1onboardingmarkforecastrunpost) | **POST** /api/v1/onboarding/mark-forecast-run | Mark Forecast Run
*OnboardingApi* | [**reopenChecklistApiV1OnboardingReopenPost**](docs/OnboardingApi.md#reopenchecklistapiv1onboardingreopenpost) | **POST** /api/v1/onboarding/reopen | Reopen Checklist
*OnboardingApi* | [**setPersonaApiV1OnboardingPersonaPost**](docs/OnboardingApi.md#setpersonaapiv1onboardingpersonapost) | **POST** /api/v1/onboarding/persona | Set Persona
*OptimiseApi* | [**optimiseApiV1OptimisePost**](docs/OptimiseApi.md#optimiseapiv1optimisepost) | **POST** /api/v1/optimise | Optimise
*OverviewApi* | [**getOverviewApiV1OverviewDashboardGet**](docs/OverviewApi.md#getoverviewapiv1overviewdashboardget) | **GET** /api/v1/overview/dashboard | Get Overview
*OverviewApi* | [**getOverviewApiV1OverviewDashboardGet_0**](docs/OverviewApi.md#getoverviewapiv1overviewdashboardget_0) | **GET** /api/v1/overview/dashboard | Get Overview
*PublicApi* | [**getPublicInvoiceApiV1InvoicePublicTokenGet**](docs/PublicApi.md#getpublicinvoiceapiv1invoicepublictokenget) | **GET** /api/v1/invoice/public/{token} | Get Public Invoice
*ReadingsApi* | [**getReadingsApiV1ReadingsGet**](docs/ReadingsApi.md#getreadingsapiv1readingsget) | **GET** /api/v1/readings | Get Readings
*ReadingsApi* | [**getReadingsApiV1ReadingsMeterIdGet**](docs/ReadingsApi.md#getreadingsapiv1readingsmeteridget) | **GET** /api/v1/readings/{meter_id} | Get Readings
*ReadingsApi* | [**listMetersApiV1BuildingsMetersGet**](docs/ReadingsApi.md#listmetersapiv1buildingsmetersget) | **GET** /api/v1/buildings/meters | List Meters
*ReadingsApi* | [**manualReadingApiV1ReadingsManualPost**](docs/ReadingsApi.md#manualreadingapiv1readingsmanualpost) | **POST** /api/v1/readings/manual | Manual Reading
*ReadingsApi* | [**pushReadingsApiV1ReadingsPushPost**](docs/ReadingsApi.md#pushreadingsapiv1readingspushpost) | **POST** /api/v1/readings/push | Push Readings
*ReportsApi* | [**downloadAnomalyPdfApiV1ReportsAnomalyPdfGet**](docs/ReportsApi.md#downloadanomalypdfapiv1reportsanomalypdfget) | **GET** /api/v1/reports/anomaly/pdf | Download Anomaly Pdf
*ReportsApi* | [**downloadCarbonPdfApiV1ReportsCarbonPdfGet**](docs/ReportsApi.md#downloadcarbonpdfapiv1reportscarbonpdfget) | **GET** /api/v1/reports/carbon/pdf | Download Carbon Pdf
*ReportsApi* | [**downloadCompliancePdfApiV1ReportsCompliancePdfGet**](docs/ReportsApi.md#downloadcompliancepdfapiv1reportscompliancepdfget) | **GET** /api/v1/reports/compliance/pdf | Download Compliance Pdf
*ReportsApi* | [**downloadPortfolioPdfApiV1ReportsPortfolioPdfGet**](docs/ReportsApi.md#downloadportfoliopdfapiv1reportsportfoliopdfget) | **GET** /api/v1/reports/portfolio/pdf | Download Portfolio Pdf
*RolesApi* | [**changeUserRoleApiV1AdminRolesUsersUserIdRolePatch**](docs/RolesApi.md#changeuserroleapiv1adminrolesusersuseridrolepatch) | **PATCH** /api/v1/admin/roles/users/{user_id}/role | Change User Role
*RolesApi* | [**changeUserRoleApiV1AdminRolesUsersUserIdRolePatch_0**](docs/RolesApi.md#changeuserroleapiv1adminrolesusersuseridrolepatch_0) | **PATCH** /api/v1/admin/roles/users/{user_id}/role | Change User Role
*RolesApi* | [**getMyPermissionsApiV1AdminRolesMyPermissionsGet**](docs/RolesApi.md#getmypermissionsapiv1adminrolesmypermissionsget) | **GET** /api/v1/admin/roles/my-permissions | Get My Permissions
*RolesApi* | [**getMyPermissionsApiV1AdminRolesMyPermissionsGet_0**](docs/RolesApi.md#getmypermissionsapiv1adminrolesmypermissionsget_0) | **GET** /api/v1/admin/roles/my-permissions | Get My Permissions
*RolesApi* | [**getRoleDefinitionsApiV1AdminRolesDefinitionsGet**](docs/RolesApi.md#getroledefinitionsapiv1adminrolesdefinitionsget) | **GET** /api/v1/admin/roles/definitions | Get Role Definitions
*RolesApi* | [**getRoleDefinitionsApiV1AdminRolesDefinitionsGet_0**](docs/RolesApi.md#getroledefinitionsapiv1adminrolesdefinitionsget_0) | **GET** /api/v1/admin/roles/definitions | Get Role Definitions
*RolesApi* | [**getUsersWithRolesApiV1AdminRolesUsersGet**](docs/RolesApi.md#getuserswithrolesapiv1adminrolesusersget) | **GET** /api/v1/admin/roles/users | Get Users With Roles
*RolesApi* | [**getUsersWithRolesApiV1AdminRolesUsersGet_0**](docs/RolesApi.md#getuserswithrolesapiv1adminrolesusersget_0) | **GET** /api/v1/admin/roles/users | Get Users With Roles
*RolesApi* | [**resetPermissionsApiV1AdminRolesUsersUserIdResetPost**](docs/RolesApi.md#resetpermissionsapiv1adminrolesusersuseridresetpost) | **POST** /api/v1/admin/roles/users/{user_id}/reset | Reset Permissions
*RolesApi* | [**resetPermissionsApiV1AdminRolesUsersUserIdResetPost_0**](docs/RolesApi.md#resetpermissionsapiv1adminrolesusersuseridresetpost_0) | **POST** /api/v1/admin/roles/users/{user_id}/reset | Reset Permissions
*RolesApi* | [**updateUserPermissionsApiV1AdminRolesUsersUserIdPermissionsPatch**](docs/RolesApi.md#updateuserpermissionsapiv1adminrolesusersuseridpermissionspatch) | **PATCH** /api/v1/admin/roles/users/{user_id}/permissions | Update User Permissions
*RolesApi* | [**updateUserPermissionsApiV1AdminRolesUsersUserIdPermissionsPatch_0**](docs/RolesApi.md#updateuserpermissionsapiv1adminrolesusersuseridpermissionspatch_0) | **PATCH** /api/v1/admin/roles/users/{user_id}/permissions | Update User Permissions
*SavingsApi* | [**downloadSavingsPdfAdminApiV1SavingsAdminOrgIdPdfGet**](docs/SavingsApi.md#downloadsavingspdfadminapiv1savingsadminorgidpdfget) | **GET** /api/v1/savings/admin/{org_id}/pdf | Download Savings Pdf Admin
*SavingsApi* | [**downloadSavingsPdfAdminApiV1SavingsAdminOrgIdPdfGet_0**](docs/SavingsApi.md#downloadsavingspdfadminapiv1savingsadminorgidpdfget_0) | **GET** /api/v1/savings/admin/{org_id}/pdf | Download Savings Pdf Admin
*SavingsApi* | [**downloadSavingsPdfApiV1SavingsPdfGet**](docs/SavingsApi.md#downloadsavingspdfapiv1savingspdfget) | **GET** /api/v1/savings/pdf | Download Savings Pdf
*SavingsApi* | [**downloadSavingsPdfApiV1SavingsPdfGet_0**](docs/SavingsApi.md#downloadsavingspdfapiv1savingspdfget_0) | **GET** /api/v1/savings/pdf | Download Savings Pdf
*SavingsApi* | [**getComplianceSavingsApiV1SavingsComplianceGet**](docs/SavingsApi.md#getcompliancesavingsapiv1savingscomplianceget) | **GET** /api/v1/savings/compliance | Get Compliance Savings
*SavingsApi* | [**getComplianceSavingsApiV1SavingsComplianceGet_0**](docs/SavingsApi.md#getcompliancesavingsapiv1savingscomplianceget_0) | **GET** /api/v1/savings/compliance | Get Compliance Savings
*SavingsApi* | [**getRoiMetricApiV1SavingsRoiGet**](docs/SavingsApi.md#getroimetricapiv1savingsroiget) | **GET** /api/v1/savings/roi | Get Roi Metric
*SavingsApi* | [**getRoiMetricApiV1SavingsRoiGet_0**](docs/SavingsApi.md#getroimetricapiv1savingsroiget_0) | **GET** /api/v1/savings/roi | Get Roi Metric
*SavingsApi* | [**getSavingsByBuildingApiV1SavingsBuildingsGet**](docs/SavingsApi.md#getsavingsbybuildingapiv1savingsbuildingsget) | **GET** /api/v1/savings/buildings | Get Savings By Building
*SavingsApi* | [**getSavingsByBuildingApiV1SavingsBuildingsGet_0**](docs/SavingsApi.md#getsavingsbybuildingapiv1savingsbuildingsget_0) | **GET** /api/v1/savings/buildings | Get Savings By Building
*SavingsApi* | [**getSavingsForOrgApiV1SavingsAdminOrgIdGet**](docs/SavingsApi.md#getsavingsfororgapiv1savingsadminorgidget) | **GET** /api/v1/savings/admin/{org_id} | Get Savings For Org
*SavingsApi* | [**getSavingsForOrgApiV1SavingsAdminOrgIdGet_0**](docs/SavingsApi.md#getsavingsfororgapiv1savingsadminorgidget_0) | **GET** /api/v1/savings/admin/{org_id} | Get Savings For Org
*SavingsApi* | [**getSavingsSummaryApiV1SavingsSummaryGet**](docs/SavingsApi.md#getsavingssummaryapiv1savingssummaryget) | **GET** /api/v1/savings/summary | Get Savings Summary
*SavingsApi* | [**getSavingsSummaryApiV1SavingsSummaryGet_0**](docs/SavingsApi.md#getsavingssummaryapiv1savingssummaryget_0) | **GET** /api/v1/savings/summary | Get Savings Summary
*SavingsApi* | [**getSavingsTrendApiV1SavingsTrendGet**](docs/SavingsApi.md#getsavingstrendapiv1savingstrendget) | **GET** /api/v1/savings/trend | Get Savings Trend
*SavingsApi* | [**getSavingsTrendApiV1SavingsTrendGet_0**](docs/SavingsApi.md#getsavingstrendapiv1savingstrendget_0) | **GET** /api/v1/savings/trend | Get Savings Trend
*SettingsApi* | [**changePasswordApiV1AuthChangePasswordPost**](docs/SettingsApi.md#changepasswordapiv1authchangepasswordpost) | **POST** /api/v1/auth/change-password | Change Password
*SettingsApi* | [**changePasswordApiV1AuthChangePasswordPost_0**](docs/SettingsApi.md#changepasswordapiv1authchangepasswordpost_0) | **POST** /api/v1/auth/change-password | Change Password
*SettingsApi* | [**deleteAccountApiV1SettingsAccountDelete**](docs/SettingsApi.md#deleteaccountapiv1settingsaccountdelete) | **DELETE** /api/v1/settings/account | Delete Account
*SettingsApi* | [**deleteAccountApiV1SettingsAccountDelete_0**](docs/SettingsApi.md#deleteaccountapiv1settingsaccountdelete_0) | **DELETE** /api/v1/settings/account | Delete Account
*SettingsApi* | [**disable2faApiV1Settings2faDisablePost**](docs/SettingsApi.md#disable2faapiv1settings2fadisablepost) | **POST** /api/v1/settings/2fa/disable | Disable 2Fa
*SettingsApi* | [**disable2faApiV1Settings2faDisablePost_0**](docs/SettingsApi.md#disable2faapiv1settings2fadisablepost_0) | **POST** /api/v1/settings/2fa/disable | Disable 2Fa
*SettingsApi* | [**exportDataApiV1SettingsExportGet**](docs/SettingsApi.md#exportdataapiv1settingsexportget) | **GET** /api/v1/settings/export | Export Data
*SettingsApi* | [**exportDataApiV1SettingsExportGet_0**](docs/SettingsApi.md#exportdataapiv1settingsexportget_0) | **GET** /api/v1/settings/export | Export Data
*SettingsApi* | [**forgotPasswordApiV1AuthForgotPasswordPost**](docs/SettingsApi.md#forgotpasswordapiv1authforgotpasswordpost) | **POST** /api/v1/auth/forgot-password | Forgot Password
*SettingsApi* | [**forgotPasswordApiV1AuthForgotPasswordPost_0**](docs/SettingsApi.md#forgotpasswordapiv1authforgotpasswordpost_0) | **POST** /api/v1/auth/forgot-password | Forgot Password
*SettingsApi* | [**getDataRetentionApiV1SettingsDataRetentionGet**](docs/SettingsApi.md#getdataretentionapiv1settingsdataretentionget) | **GET** /api/v1/settings/data-retention | Get Data Retention
*SettingsApi* | [**getDataRetentionApiV1SettingsDataRetentionGet_0**](docs/SettingsApi.md#getdataretentionapiv1settingsdataretentionget_0) | **GET** /api/v1/settings/data-retention | Get Data Retention
*SettingsApi* | [**getEmailPreferencesApiV1SettingsEmailPreferencesGet**](docs/SettingsApi.md#getemailpreferencesapiv1settingsemailpreferencesget) | **GET** /api/v1/settings/email-preferences | Get Email Preferences
*SettingsApi* | [**getEmailPreferencesApiV1SettingsEmailPreferencesGet_0**](docs/SettingsApi.md#getemailpreferencesapiv1settingsemailpreferencesget_0) | **GET** /api/v1/settings/email-preferences | Get Email Preferences
*SettingsApi* | [**getPreferencesApiV1SettingsPreferencesGet**](docs/SettingsApi.md#getpreferencesapiv1settingspreferencesget) | **GET** /api/v1/settings/preferences | Get Preferences
*SettingsApi* | [**getPreferencesApiV1SettingsPreferencesGet_0**](docs/SettingsApi.md#getpreferencesapiv1settingspreferencesget_0) | **GET** /api/v1/settings/preferences | Get Preferences
*SettingsApi* | [**getProfileApiV1SettingsProfileGet**](docs/SettingsApi.md#getprofileapiv1settingsprofileget) | **GET** /api/v1/settings/profile | Get Profile
*SettingsApi* | [**getProfileApiV1SettingsProfileGet_0**](docs/SettingsApi.md#getprofileapiv1settingsprofileget_0) | **GET** /api/v1/settings/profile | Get Profile
*SettingsApi* | [**savePreferencesApiV1SettingsPreferencesPut**](docs/SettingsApi.md#savepreferencesapiv1settingspreferencesput) | **PUT** /api/v1/settings/preferences | Save Preferences
*SettingsApi* | [**savePreferencesApiV1SettingsPreferencesPut_0**](docs/SettingsApi.md#savepreferencesapiv1settingspreferencesput_0) | **PUT** /api/v1/settings/preferences | Save Preferences
*SettingsApi* | [**setup2faApiV1Settings2faSetupPost**](docs/SettingsApi.md#setup2faapiv1settings2fasetuppost) | **POST** /api/v1/settings/2fa/setup | Setup 2Fa
*SettingsApi* | [**setup2faApiV1Settings2faSetupPost_0**](docs/SettingsApi.md#setup2faapiv1settings2fasetuppost_0) | **POST** /api/v1/settings/2fa/setup | Setup 2Fa
*SettingsApi* | [**unsubscribeApiV1SettingsUnsubscribeGet**](docs/SettingsApi.md#unsubscribeapiv1settingsunsubscribeget) | **GET** /api/v1/settings/unsubscribe | Unsubscribe
*SettingsApi* | [**unsubscribeApiV1SettingsUnsubscribeGet_0**](docs/SettingsApi.md#unsubscribeapiv1settingsunsubscribeget_0) | **GET** /api/v1/settings/unsubscribe | Unsubscribe
*SettingsApi* | [**updateDataRetentionApiV1SettingsDataRetentionPut**](docs/SettingsApi.md#updatedataretentionapiv1settingsdataretentionput) | **PUT** /api/v1/settings/data-retention | Update Data Retention
*SettingsApi* | [**updateDataRetentionApiV1SettingsDataRetentionPut_0**](docs/SettingsApi.md#updatedataretentionapiv1settingsdataretentionput_0) | **PUT** /api/v1/settings/data-retention | Update Data Retention
*SettingsApi* | [**updateEmailPreferencesApiV1SettingsEmailPreferencesPut**](docs/SettingsApi.md#updateemailpreferencesapiv1settingsemailpreferencesput) | **PUT** /api/v1/settings/email-preferences | Update Email Preferences
*SettingsApi* | [**updateEmailPreferencesApiV1SettingsEmailPreferencesPut_0**](docs/SettingsApi.md#updateemailpreferencesapiv1settingsemailpreferencesput_0) | **PUT** /api/v1/settings/email-preferences | Update Email Preferences
*SettingsApi* | [**updateProfileApiV1SettingsProfilePatch**](docs/SettingsApi.md#updateprofileapiv1settingsprofilepatch) | **PATCH** /api/v1/settings/profile | Update Profile
*SettingsApi* | [**updateProfileApiV1SettingsProfilePatch_0**](docs/SettingsApi.md#updateprofileapiv1settingsprofilepatch_0) | **PATCH** /api/v1/settings/profile | Update Profile
*SettingsApi* | [**verify2faApiV1Settings2faVerifyPost**](docs/SettingsApi.md#verify2faapiv1settings2faverifypost) | **POST** /api/v1/settings/2fa/verify | Verify 2Fa
*SettingsApi* | [**verify2faApiV1Settings2faVerifyPost_0**](docs/SettingsApi.md#verify2faapiv1settings2faverifypost_0) | **POST** /api/v1/settings/2fa/verify | Verify 2Fa
*StaffApi* | [**createStaffApiV1AdminStaffPost**](docs/StaffApi.md#createstaffapiv1adminstaffpost) | **POST** /api/v1/admin/staff | Create Staff
*StaffApi* | [**createStaffApiV1AdminStaffPost_0**](docs/StaffApi.md#createstaffapiv1adminstaffpost_0) | **POST** /api/v1/admin/staff | Create Staff
*StaffApi* | [**deleteStaffApiV1AdminStaffSidDelete**](docs/StaffApi.md#deletestaffapiv1adminstaffsiddelete) | **DELETE** /api/v1/admin/staff/{sid} | Delete Staff
*StaffApi* | [**deleteStaffApiV1AdminStaffSidDelete_0**](docs/StaffApi.md#deletestaffapiv1adminstaffsiddelete_0) | **DELETE** /api/v1/admin/staff/{sid} | Delete Staff
*StaffApi* | [**getActivityApiV1AdminStaffSidActivityGet**](docs/StaffApi.md#getactivityapiv1adminstaffsidactivityget) | **GET** /api/v1/admin/staff/{sid}/activity | Get Activity
*StaffApi* | [**getActivityApiV1AdminStaffSidActivityGet_0**](docs/StaffApi.md#getactivityapiv1adminstaffsidactivityget_0) | **GET** /api/v1/admin/staff/{sid}/activity | Get Activity
*StaffApi* | [**getSessionsApiV1AdminStaffSidSessionsGet**](docs/StaffApi.md#getsessionsapiv1adminstaffsidsessionsget) | **GET** /api/v1/admin/staff/{sid}/sessions | Get Sessions
*StaffApi* | [**getSessionsApiV1AdminStaffSidSessionsGet_0**](docs/StaffApi.md#getsessionsapiv1adminstaffsidsessionsget_0) | **GET** /api/v1/admin/staff/{sid}/sessions | Get Sessions
*StaffApi* | [**getStaffApiV1AdminStaffSidGet**](docs/StaffApi.md#getstaffapiv1adminstaffsidget) | **GET** /api/v1/admin/staff/{sid} | Get Staff
*StaffApi* | [**getStaffApiV1AdminStaffSidGet_0**](docs/StaffApi.md#getstaffapiv1adminstaffsidget_0) | **GET** /api/v1/admin/staff/{sid} | Get Staff
*StaffApi* | [**heartbeatApiV1AdminStaffHeartbeatPost**](docs/StaffApi.md#heartbeatapiv1adminstaffheartbeatpost) | **POST** /api/v1/admin/staff/heartbeat | Heartbeat
*StaffApi* | [**heartbeatApiV1AdminStaffHeartbeatPost_0**](docs/StaffApi.md#heartbeatapiv1adminstaffheartbeatpost_0) | **POST** /api/v1/admin/staff/heartbeat | Heartbeat
*StaffApi* | [**listRolesApiV1AdminStaffRolesListGet**](docs/StaffApi.md#listrolesapiv1adminstaffroleslistget) | **GET** /api/v1/admin/staff/roles/list | List Roles
*StaffApi* | [**listRolesApiV1AdminStaffRolesListGet_0**](docs/StaffApi.md#listrolesapiv1adminstaffroleslistget_0) | **GET** /api/v1/admin/staff/roles/list | List Roles
*StaffApi* | [**listStaffApiV1AdminStaffGet**](docs/StaffApi.md#liststaffapiv1adminstaffget) | **GET** /api/v1/admin/staff | List Staff
*StaffApi* | [**listStaffApiV1AdminStaffGet_0**](docs/StaffApi.md#liststaffapiv1adminstaffget_0) | **GET** /api/v1/admin/staff | List Staff
*StaffApi* | [**loginEventApiV1AdminStaffLoginEventPost**](docs/StaffApi.md#logineventapiv1adminstafflogineventpost) | **POST** /api/v1/admin/staff/login-event | Login Event
*StaffApi* | [**loginEventApiV1AdminStaffLoginEventPost_0**](docs/StaffApi.md#logineventapiv1adminstafflogineventpost_0) | **POST** /api/v1/admin/staff/login-event | Login Event
*StaffApi* | [**logoutEventApiV1AdminStaffLogoutEventPost**](docs/StaffApi.md#logouteventapiv1adminstafflogouteventpost) | **POST** /api/v1/admin/staff/logout-event | Logout Event
*StaffApi* | [**logoutEventApiV1AdminStaffLogoutEventPost_0**](docs/StaffApi.md#logouteventapiv1adminstafflogouteventpost_0) | **POST** /api/v1/admin/staff/logout-event | Logout Event
*StaffApi* | [**updateStaffApiV1AdminStaffSidPatch**](docs/StaffApi.md#updatestaffapiv1adminstaffsidpatch) | **PATCH** /api/v1/admin/staff/{sid} | Update Staff
*StaffApi* | [**updateStaffApiV1AdminStaffSidPatch_0**](docs/StaffApi.md#updatestaffapiv1adminstaffsidpatch_0) | **PATCH** /api/v1/admin/staff/{sid} | Update Staff
*StaffApi* | [**uploadAvatarApiV1AdminStaffSidAvatarPost**](docs/StaffApi.md#uploadavatarapiv1adminstaffsidavatarpost) | **POST** /api/v1/admin/staff/{sid}/avatar | Upload Avatar
*StaffApi* | [**uploadAvatarApiV1AdminStaffSidAvatarPost_0**](docs/StaffApi.md#uploadavatarapiv1adminstaffsidavatarpost_0) | **POST** /api/v1/admin/staff/{sid}/avatar | Upload Avatar
*SystemApi* | [**healthApiV1HealthHead**](docs/SystemApi.md#healthapiv1healthhead) | **GET** /api/v1/health | Health
*SystemApi* | [**healthApiV1HealthHead_0**](docs/SystemApi.md#healthapiv1healthhead_0) | **HEAD** /api/v1/health | Health
*UsageApi* | [**adminOrgDetailEndpointApiV1UsageAdminOrgOrgIdGet**](docs/UsageApi.md#adminorgdetailendpointapiv1usageadminorgorgidget) | **GET** /api/v1/usage/admin/org/{org_id} | Admin Org Detail Endpoint
*UsageApi* | [**adminOrgDetailEndpointApiV1UsageAdminOrgOrgIdGet_0**](docs/UsageApi.md#adminorgdetailendpointapiv1usageadminorgorgidget_0) | **GET** /api/v1/usage/admin/org/{org_id} | Admin Org Detail Endpoint
*UsageApi* | [**adminOverviewEndpointApiV1UsageAdminOverviewGet**](docs/UsageApi.md#adminoverviewendpointapiv1usageadminoverviewget) | **GET** /api/v1/usage/admin/overview | Admin Overview Endpoint
*UsageApi* | [**adminOverviewEndpointApiV1UsageAdminOverviewGet_0**](docs/UsageApi.md#adminoverviewendpointapiv1usageadminoverviewget_0) | **GET** /api/v1/usage/admin/overview | Admin Overview Endpoint
*UsageApi* | [**myHistoryEndpointApiV1UsageMeHistoryGet**](docs/UsageApi.md#myhistoryendpointapiv1usagemehistoryget) | **GET** /api/v1/usage/me/history | My History Endpoint
*UsageApi* | [**myHistoryEndpointApiV1UsageMeHistoryGet_0**](docs/UsageApi.md#myhistoryendpointapiv1usagemehistoryget_0) | **GET** /api/v1/usage/me/history | My History Endpoint
*UsageApi* | [**myUsageEndpointApiV1UsageMeGet**](docs/UsageApi.md#myusageendpointapiv1usagemeget) | **GET** /api/v1/usage/me | My Usage Endpoint
*UsageApi* | [**myUsageEndpointApiV1UsageMeGet_0**](docs/UsageApi.md#myusageendpointapiv1usagemeget_0) | **GET** /api/v1/usage/me | My Usage Endpoint


### Documentation For Models

 - [APIKeyCreatedResponse](docs/APIKeyCreatedResponse.md)
 - [APIKeyResponse](docs/APIKeyResponse.md)
 - [AnomalyLayer](docs/AnomalyLayer.md)
 - [AppRoutersReadingsPushReadingItem](docs/AppRoutersReadingsPushReadingItem.md)
 - [AppSchemasReadingItem](docs/AppSchemasReadingItem.md)
 - [CarbonLayer](docs/CarbonLayer.md)
 - [CarbonRequest](docs/CarbonRequest.md)
 - [CarbonResponse](docs/CarbonResponse.md)
 - [ChatMessageRequest](docs/ChatMessageRequest.md)
 - [ComplianceRequest](docs/ComplianceRequest.md)
 - [CreateAPIKeyRequest](docs/CreateAPIKeyRequest.md)
 - [CreateInvoiceRequest](docs/CreateInvoiceRequest.md)
 - [CreateOrgRequest](docs/CreateOrgRequest.md)
 - [CreateUserRequest](docs/CreateUserRequest.md)
 - [ERICResponse](docs/ERICResponse.md)
 - [ESOSResponse](docs/ESOSResponse.md)
 - [EmailInvoiceRequest](docs/EmailInvoiceRequest.md)
 - [EnergyForecastRequest](docs/EnergyForecastRequest.md)
 - [EngRequest](docs/EngRequest.md)
 - [ForecastRequest](docs/ForecastRequest.md)
 - [ForecastResponse](docs/ForecastResponse.md)
 - [ForgotRequest](docs/ForgotRequest.md)
 - [FuelPovertyLayer](docs/FuelPovertyLayer.md)
 - [HTTPValidationError](docs/HTTPValidationError.md)
 - [HealthResponse](docs/HealthResponse.md)
 - [IngestResponse](docs/IngestResponse.md)
 - [InvoiceStatusRequest](docs/InvoiceStatusRequest.md)
 - [LeadCaptureRequest](docs/LeadCaptureRequest.md)
 - [LocationInner](docs/LocationInner.md)
 - [ManualRequest](docs/ManualRequest.md)
 - [ManualResponse](docs/ManualResponse.md)
 - [OccupancyLayer](docs/OccupancyLayer.md)
 - [OnboardingStatus](docs/OnboardingStatus.md)
 - [OnboardingTask](docs/OnboardingTask.md)
 - [OptimiseRequest](docs/OptimiseRequest.md)
 - [OptimiseResponse](docs/OptimiseResponse.md)
 - [PersonaRequest](docs/PersonaRequest.md)
 - [PushRequest](docs/PushRequest.md)
 - [PushResponse](docs/PushResponse.md)
 - [RegisterRequest](docs/RegisterRequest.md)
 - [ResetRequest](docs/ResetRequest.md)
 - [SECRResponse](docs/SECRResponse.md)
 - [SHDFResponse](docs/SHDFResponse.md)
 - [SimpleOk](docs/SimpleOk.md)
 - [ValidationError](docs/ValidationError.md)


<a id="documentation-for-authorization"></a>
## Documentation For Authorization


Authentication schemes defined for the API:
<a id="OAuth2PasswordBearer"></a>
### OAuth2PasswordBearer

- **Type**: OAuth
- **Flow**: password
- **Authorization URL**: 
- **Scopes**: N/A

<a id="APIKeyHeader"></a>
### APIKeyHeader

- **Type**: API key
- **API key parameter name**: X-API-Key
- **Location**: HTTP header

