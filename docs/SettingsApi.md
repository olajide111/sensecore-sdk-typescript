# SettingsApi

All URIs are relative to *https://api.sensecoreai.com*

|Method | HTTP request | Description|
|------------- | ------------- | -------------|
|[**changePasswordApiV1AuthChangePasswordPost**](#changepasswordapiv1authchangepasswordpost) | **POST** /api/v1/auth/change-password | Change Password|
|[**changePasswordApiV1AuthChangePasswordPost_0**](#changepasswordapiv1authchangepasswordpost_0) | **POST** /api/v1/auth/change-password | Change Password|
|[**deleteAccountApiV1SettingsAccountDelete**](#deleteaccountapiv1settingsaccountdelete) | **DELETE** /api/v1/settings/account | Delete Account|
|[**deleteAccountApiV1SettingsAccountDelete_0**](#deleteaccountapiv1settingsaccountdelete_0) | **DELETE** /api/v1/settings/account | Delete Account|
|[**disable2faApiV1Settings2faDisablePost**](#disable2faapiv1settings2fadisablepost) | **POST** /api/v1/settings/2fa/disable | Disable 2Fa|
|[**disable2faApiV1Settings2faDisablePost_0**](#disable2faapiv1settings2fadisablepost_0) | **POST** /api/v1/settings/2fa/disable | Disable 2Fa|
|[**exportDataApiV1SettingsExportGet**](#exportdataapiv1settingsexportget) | **GET** /api/v1/settings/export | Export Data|
|[**exportDataApiV1SettingsExportGet_0**](#exportdataapiv1settingsexportget_0) | **GET** /api/v1/settings/export | Export Data|
|[**forgotPasswordApiV1AuthForgotPasswordPost**](#forgotpasswordapiv1authforgotpasswordpost) | **POST** /api/v1/auth/forgot-password | Forgot Password|
|[**forgotPasswordApiV1AuthForgotPasswordPost_0**](#forgotpasswordapiv1authforgotpasswordpost_0) | **POST** /api/v1/auth/forgot-password | Forgot Password|
|[**getDataRetentionApiV1SettingsDataRetentionGet**](#getdataretentionapiv1settingsdataretentionget) | **GET** /api/v1/settings/data-retention | Get Data Retention|
|[**getDataRetentionApiV1SettingsDataRetentionGet_0**](#getdataretentionapiv1settingsdataretentionget_0) | **GET** /api/v1/settings/data-retention | Get Data Retention|
|[**getEmailPreferencesApiV1SettingsEmailPreferencesGet**](#getemailpreferencesapiv1settingsemailpreferencesget) | **GET** /api/v1/settings/email-preferences | Get Email Preferences|
|[**getEmailPreferencesApiV1SettingsEmailPreferencesGet_0**](#getemailpreferencesapiv1settingsemailpreferencesget_0) | **GET** /api/v1/settings/email-preferences | Get Email Preferences|
|[**getPreferencesApiV1SettingsPreferencesGet**](#getpreferencesapiv1settingspreferencesget) | **GET** /api/v1/settings/preferences | Get Preferences|
|[**getPreferencesApiV1SettingsPreferencesGet_0**](#getpreferencesapiv1settingspreferencesget_0) | **GET** /api/v1/settings/preferences | Get Preferences|
|[**getProfileApiV1SettingsProfileGet**](#getprofileapiv1settingsprofileget) | **GET** /api/v1/settings/profile | Get Profile|
|[**getProfileApiV1SettingsProfileGet_0**](#getprofileapiv1settingsprofileget_0) | **GET** /api/v1/settings/profile | Get Profile|
|[**savePreferencesApiV1SettingsPreferencesPut**](#savepreferencesapiv1settingspreferencesput) | **PUT** /api/v1/settings/preferences | Save Preferences|
|[**savePreferencesApiV1SettingsPreferencesPut_0**](#savepreferencesapiv1settingspreferencesput_0) | **PUT** /api/v1/settings/preferences | Save Preferences|
|[**setup2faApiV1Settings2faSetupPost**](#setup2faapiv1settings2fasetuppost) | **POST** /api/v1/settings/2fa/setup | Setup 2Fa|
|[**setup2faApiV1Settings2faSetupPost_0**](#setup2faapiv1settings2fasetuppost_0) | **POST** /api/v1/settings/2fa/setup | Setup 2Fa|
|[**unsubscribeApiV1SettingsUnsubscribeGet**](#unsubscribeapiv1settingsunsubscribeget) | **GET** /api/v1/settings/unsubscribe | Unsubscribe|
|[**unsubscribeApiV1SettingsUnsubscribeGet_0**](#unsubscribeapiv1settingsunsubscribeget_0) | **GET** /api/v1/settings/unsubscribe | Unsubscribe|
|[**updateDataRetentionApiV1SettingsDataRetentionPut**](#updatedataretentionapiv1settingsdataretentionput) | **PUT** /api/v1/settings/data-retention | Update Data Retention|
|[**updateDataRetentionApiV1SettingsDataRetentionPut_0**](#updatedataretentionapiv1settingsdataretentionput_0) | **PUT** /api/v1/settings/data-retention | Update Data Retention|
|[**updateEmailPreferencesApiV1SettingsEmailPreferencesPut**](#updateemailpreferencesapiv1settingsemailpreferencesput) | **PUT** /api/v1/settings/email-preferences | Update Email Preferences|
|[**updateEmailPreferencesApiV1SettingsEmailPreferencesPut_0**](#updateemailpreferencesapiv1settingsemailpreferencesput_0) | **PUT** /api/v1/settings/email-preferences | Update Email Preferences|
|[**updateProfileApiV1SettingsProfilePatch**](#updateprofileapiv1settingsprofilepatch) | **PATCH** /api/v1/settings/profile | Update Profile|
|[**updateProfileApiV1SettingsProfilePatch_0**](#updateprofileapiv1settingsprofilepatch_0) | **PATCH** /api/v1/settings/profile | Update Profile|
|[**verify2faApiV1Settings2faVerifyPost**](#verify2faapiv1settings2faverifypost) | **POST** /api/v1/settings/2fa/verify | Verify 2Fa|
|[**verify2faApiV1Settings2faVerifyPost_0**](#verify2faapiv1settings2faverifypost_0) | **POST** /api/v1/settings/2fa/verify | Verify 2Fa|

# **changePasswordApiV1AuthChangePasswordPost**
> any changePasswordApiV1AuthChangePasswordPost(body)


### Example

```typescript
import {
    SettingsApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new SettingsApi(configuration);

let body: object; //

const { status, data } = await apiInstance.changePasswordApiV1AuthChangePasswordPost(
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

# **changePasswordApiV1AuthChangePasswordPost_0**
> any changePasswordApiV1AuthChangePasswordPost_0(body)


### Example

```typescript
import {
    SettingsApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new SettingsApi(configuration);

let body: object; //

const { status, data } = await apiInstance.changePasswordApiV1AuthChangePasswordPost_0(
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

# **deleteAccountApiV1SettingsAccountDelete**
> any deleteAccountApiV1SettingsAccountDelete(body)


### Example

```typescript
import {
    SettingsApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new SettingsApi(configuration);

let body: object; //

const { status, data } = await apiInstance.deleteAccountApiV1SettingsAccountDelete(
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

# **deleteAccountApiV1SettingsAccountDelete_0**
> any deleteAccountApiV1SettingsAccountDelete_0(body)


### Example

```typescript
import {
    SettingsApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new SettingsApi(configuration);

let body: object; //

const { status, data } = await apiInstance.deleteAccountApiV1SettingsAccountDelete_0(
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

# **disable2faApiV1Settings2faDisablePost**
> any disable2faApiV1Settings2faDisablePost(body)


### Example

```typescript
import {
    SettingsApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new SettingsApi(configuration);

let body: object; //

const { status, data } = await apiInstance.disable2faApiV1Settings2faDisablePost(
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

# **disable2faApiV1Settings2faDisablePost_0**
> any disable2faApiV1Settings2faDisablePost_0(body)


### Example

```typescript
import {
    SettingsApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new SettingsApi(configuration);

let body: object; //

const { status, data } = await apiInstance.disable2faApiV1Settings2faDisablePost_0(
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

# **exportDataApiV1SettingsExportGet**
> any exportDataApiV1SettingsExportGet()


### Example

```typescript
import {
    SettingsApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new SettingsApi(configuration);

const { status, data } = await apiInstance.exportDataApiV1SettingsExportGet();
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

# **exportDataApiV1SettingsExportGet_0**
> any exportDataApiV1SettingsExportGet_0()


### Example

```typescript
import {
    SettingsApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new SettingsApi(configuration);

const { status, data } = await apiInstance.exportDataApiV1SettingsExportGet_0();
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

# **forgotPasswordApiV1AuthForgotPasswordPost**
> any forgotPasswordApiV1AuthForgotPasswordPost(body)


### Example

```typescript
import {
    SettingsApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new SettingsApi(configuration);

let body: object; //

const { status, data } = await apiInstance.forgotPasswordApiV1AuthForgotPasswordPost(
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

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | Successful Response |  -  |
|**422** | Validation Error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **forgotPasswordApiV1AuthForgotPasswordPost_0**
> any forgotPasswordApiV1AuthForgotPasswordPost_0(body)


### Example

```typescript
import {
    SettingsApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new SettingsApi(configuration);

let body: object; //

const { status, data } = await apiInstance.forgotPasswordApiV1AuthForgotPasswordPost_0(
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

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | Successful Response |  -  |
|**422** | Validation Error |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **getDataRetentionApiV1SettingsDataRetentionGet**
> any getDataRetentionApiV1SettingsDataRetentionGet()


### Example

```typescript
import {
    SettingsApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new SettingsApi(configuration);

const { status, data } = await apiInstance.getDataRetentionApiV1SettingsDataRetentionGet();
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

# **getDataRetentionApiV1SettingsDataRetentionGet_0**
> any getDataRetentionApiV1SettingsDataRetentionGet_0()


### Example

```typescript
import {
    SettingsApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new SettingsApi(configuration);

const { status, data } = await apiInstance.getDataRetentionApiV1SettingsDataRetentionGet_0();
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

# **getEmailPreferencesApiV1SettingsEmailPreferencesGet**
> any getEmailPreferencesApiV1SettingsEmailPreferencesGet()


### Example

```typescript
import {
    SettingsApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new SettingsApi(configuration);

const { status, data } = await apiInstance.getEmailPreferencesApiV1SettingsEmailPreferencesGet();
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

# **getEmailPreferencesApiV1SettingsEmailPreferencesGet_0**
> any getEmailPreferencesApiV1SettingsEmailPreferencesGet_0()


### Example

```typescript
import {
    SettingsApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new SettingsApi(configuration);

const { status, data } = await apiInstance.getEmailPreferencesApiV1SettingsEmailPreferencesGet_0();
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

# **getPreferencesApiV1SettingsPreferencesGet**
> any getPreferencesApiV1SettingsPreferencesGet()


### Example

```typescript
import {
    SettingsApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new SettingsApi(configuration);

const { status, data } = await apiInstance.getPreferencesApiV1SettingsPreferencesGet();
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

# **getPreferencesApiV1SettingsPreferencesGet_0**
> any getPreferencesApiV1SettingsPreferencesGet_0()


### Example

```typescript
import {
    SettingsApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new SettingsApi(configuration);

const { status, data } = await apiInstance.getPreferencesApiV1SettingsPreferencesGet_0();
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

# **getProfileApiV1SettingsProfileGet**
> any getProfileApiV1SettingsProfileGet()


### Example

```typescript
import {
    SettingsApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new SettingsApi(configuration);

const { status, data } = await apiInstance.getProfileApiV1SettingsProfileGet();
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

# **getProfileApiV1SettingsProfileGet_0**
> any getProfileApiV1SettingsProfileGet_0()


### Example

```typescript
import {
    SettingsApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new SettingsApi(configuration);

const { status, data } = await apiInstance.getProfileApiV1SettingsProfileGet_0();
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

# **savePreferencesApiV1SettingsPreferencesPut**
> any savePreferencesApiV1SettingsPreferencesPut(body)


### Example

```typescript
import {
    SettingsApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new SettingsApi(configuration);

let body: object; //

const { status, data } = await apiInstance.savePreferencesApiV1SettingsPreferencesPut(
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

# **savePreferencesApiV1SettingsPreferencesPut_0**
> any savePreferencesApiV1SettingsPreferencesPut_0(body)


### Example

```typescript
import {
    SettingsApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new SettingsApi(configuration);

let body: object; //

const { status, data } = await apiInstance.savePreferencesApiV1SettingsPreferencesPut_0(
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

# **setup2faApiV1Settings2faSetupPost**
> any setup2faApiV1Settings2faSetupPost()


### Example

```typescript
import {
    SettingsApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new SettingsApi(configuration);

const { status, data } = await apiInstance.setup2faApiV1Settings2faSetupPost();
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

# **setup2faApiV1Settings2faSetupPost_0**
> any setup2faApiV1Settings2faSetupPost_0()


### Example

```typescript
import {
    SettingsApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new SettingsApi(configuration);

const { status, data } = await apiInstance.setup2faApiV1Settings2faSetupPost_0();
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

# **unsubscribeApiV1SettingsUnsubscribeGet**
> any unsubscribeApiV1SettingsUnsubscribeGet()


### Example

```typescript
import {
    SettingsApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new SettingsApi(configuration);

let token: string; // (optional) (default to '')

const { status, data } = await apiInstance.unsubscribeApiV1SettingsUnsubscribeGet(
    token
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **token** | [**string**] |  | (optional) defaults to ''|


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

# **unsubscribeApiV1SettingsUnsubscribeGet_0**
> any unsubscribeApiV1SettingsUnsubscribeGet_0()


### Example

```typescript
import {
    SettingsApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new SettingsApi(configuration);

let token: string; // (optional) (default to '')

const { status, data } = await apiInstance.unsubscribeApiV1SettingsUnsubscribeGet_0(
    token
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **token** | [**string**] |  | (optional) defaults to ''|


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

# **updateDataRetentionApiV1SettingsDataRetentionPut**
> any updateDataRetentionApiV1SettingsDataRetentionPut(body)


### Example

```typescript
import {
    SettingsApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new SettingsApi(configuration);

let body: object; //

const { status, data } = await apiInstance.updateDataRetentionApiV1SettingsDataRetentionPut(
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

# **updateDataRetentionApiV1SettingsDataRetentionPut_0**
> any updateDataRetentionApiV1SettingsDataRetentionPut_0(body)


### Example

```typescript
import {
    SettingsApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new SettingsApi(configuration);

let body: object; //

const { status, data } = await apiInstance.updateDataRetentionApiV1SettingsDataRetentionPut_0(
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

# **updateEmailPreferencesApiV1SettingsEmailPreferencesPut**
> any updateEmailPreferencesApiV1SettingsEmailPreferencesPut(body)


### Example

```typescript
import {
    SettingsApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new SettingsApi(configuration);

let body: object; //

const { status, data } = await apiInstance.updateEmailPreferencesApiV1SettingsEmailPreferencesPut(
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

# **updateEmailPreferencesApiV1SettingsEmailPreferencesPut_0**
> any updateEmailPreferencesApiV1SettingsEmailPreferencesPut_0(body)


### Example

```typescript
import {
    SettingsApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new SettingsApi(configuration);

let body: object; //

const { status, data } = await apiInstance.updateEmailPreferencesApiV1SettingsEmailPreferencesPut_0(
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

# **updateProfileApiV1SettingsProfilePatch**
> any updateProfileApiV1SettingsProfilePatch(body)


### Example

```typescript
import {
    SettingsApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new SettingsApi(configuration);

let body: object; //

const { status, data } = await apiInstance.updateProfileApiV1SettingsProfilePatch(
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

# **updateProfileApiV1SettingsProfilePatch_0**
> any updateProfileApiV1SettingsProfilePatch_0(body)


### Example

```typescript
import {
    SettingsApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new SettingsApi(configuration);

let body: object; //

const { status, data } = await apiInstance.updateProfileApiV1SettingsProfilePatch_0(
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

# **verify2faApiV1Settings2faVerifyPost**
> any verify2faApiV1Settings2faVerifyPost(body)


### Example

```typescript
import {
    SettingsApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new SettingsApi(configuration);

let body: object; //

const { status, data } = await apiInstance.verify2faApiV1Settings2faVerifyPost(
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

# **verify2faApiV1Settings2faVerifyPost_0**
> any verify2faApiV1Settings2faVerifyPost_0(body)


### Example

```typescript
import {
    SettingsApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new SettingsApi(configuration);

let body: object; //

const { status, data } = await apiInstance.verify2faApiV1Settings2faVerifyPost_0(
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

