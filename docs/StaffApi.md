# StaffApi

All URIs are relative to *https://api.sensecoreai.com*

|Method | HTTP request | Description|
|------------- | ------------- | -------------|
|[**createStaffApiV1AdminStaffPost**](#createstaffapiv1adminstaffpost) | **POST** /api/v1/admin/staff | Create Staff|
|[**createStaffApiV1AdminStaffPost_0**](#createstaffapiv1adminstaffpost_0) | **POST** /api/v1/admin/staff | Create Staff|
|[**deleteStaffApiV1AdminStaffSidDelete**](#deletestaffapiv1adminstaffsiddelete) | **DELETE** /api/v1/admin/staff/{sid} | Delete Staff|
|[**deleteStaffApiV1AdminStaffSidDelete_0**](#deletestaffapiv1adminstaffsiddelete_0) | **DELETE** /api/v1/admin/staff/{sid} | Delete Staff|
|[**getActivityApiV1AdminStaffSidActivityGet**](#getactivityapiv1adminstaffsidactivityget) | **GET** /api/v1/admin/staff/{sid}/activity | Get Activity|
|[**getActivityApiV1AdminStaffSidActivityGet_0**](#getactivityapiv1adminstaffsidactivityget_0) | **GET** /api/v1/admin/staff/{sid}/activity | Get Activity|
|[**getSessionsApiV1AdminStaffSidSessionsGet**](#getsessionsapiv1adminstaffsidsessionsget) | **GET** /api/v1/admin/staff/{sid}/sessions | Get Sessions|
|[**getSessionsApiV1AdminStaffSidSessionsGet_0**](#getsessionsapiv1adminstaffsidsessionsget_0) | **GET** /api/v1/admin/staff/{sid}/sessions | Get Sessions|
|[**getStaffApiV1AdminStaffSidGet**](#getstaffapiv1adminstaffsidget) | **GET** /api/v1/admin/staff/{sid} | Get Staff|
|[**getStaffApiV1AdminStaffSidGet_0**](#getstaffapiv1adminstaffsidget_0) | **GET** /api/v1/admin/staff/{sid} | Get Staff|
|[**heartbeatApiV1AdminStaffHeartbeatPost**](#heartbeatapiv1adminstaffheartbeatpost) | **POST** /api/v1/admin/staff/heartbeat | Heartbeat|
|[**heartbeatApiV1AdminStaffHeartbeatPost_0**](#heartbeatapiv1adminstaffheartbeatpost_0) | **POST** /api/v1/admin/staff/heartbeat | Heartbeat|
|[**listRolesApiV1AdminStaffRolesListGet**](#listrolesapiv1adminstaffroleslistget) | **GET** /api/v1/admin/staff/roles/list | List Roles|
|[**listRolesApiV1AdminStaffRolesListGet_0**](#listrolesapiv1adminstaffroleslistget_0) | **GET** /api/v1/admin/staff/roles/list | List Roles|
|[**listStaffApiV1AdminStaffGet**](#liststaffapiv1adminstaffget) | **GET** /api/v1/admin/staff | List Staff|
|[**listStaffApiV1AdminStaffGet_0**](#liststaffapiv1adminstaffget_0) | **GET** /api/v1/admin/staff | List Staff|
|[**loginEventApiV1AdminStaffLoginEventPost**](#logineventapiv1adminstafflogineventpost) | **POST** /api/v1/admin/staff/login-event | Login Event|
|[**loginEventApiV1AdminStaffLoginEventPost_0**](#logineventapiv1adminstafflogineventpost_0) | **POST** /api/v1/admin/staff/login-event | Login Event|
|[**logoutEventApiV1AdminStaffLogoutEventPost**](#logouteventapiv1adminstafflogouteventpost) | **POST** /api/v1/admin/staff/logout-event | Logout Event|
|[**logoutEventApiV1AdminStaffLogoutEventPost_0**](#logouteventapiv1adminstafflogouteventpost_0) | **POST** /api/v1/admin/staff/logout-event | Logout Event|
|[**updateStaffApiV1AdminStaffSidPatch**](#updatestaffapiv1adminstaffsidpatch) | **PATCH** /api/v1/admin/staff/{sid} | Update Staff|
|[**updateStaffApiV1AdminStaffSidPatch_0**](#updatestaffapiv1adminstaffsidpatch_0) | **PATCH** /api/v1/admin/staff/{sid} | Update Staff|
|[**uploadAvatarApiV1AdminStaffSidAvatarPost**](#uploadavatarapiv1adminstaffsidavatarpost) | **POST** /api/v1/admin/staff/{sid}/avatar | Upload Avatar|
|[**uploadAvatarApiV1AdminStaffSidAvatarPost_0**](#uploadavatarapiv1adminstaffsidavatarpost_0) | **POST** /api/v1/admin/staff/{sid}/avatar | Upload Avatar|

# **createStaffApiV1AdminStaffPost**
> any createStaffApiV1AdminStaffPost(body)


### Example

```typescript
import {
    StaffApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new StaffApi(configuration);

let body: object; //

const { status, data } = await apiInstance.createStaffApiV1AdminStaffPost(
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

# **createStaffApiV1AdminStaffPost_0**
> any createStaffApiV1AdminStaffPost_0(body)


### Example

```typescript
import {
    StaffApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new StaffApi(configuration);

let body: object; //

const { status, data } = await apiInstance.createStaffApiV1AdminStaffPost_0(
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

# **deleteStaffApiV1AdminStaffSidDelete**
> any deleteStaffApiV1AdminStaffSidDelete()


### Example

```typescript
import {
    StaffApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new StaffApi(configuration);

let sid: string; // (default to undefined)

const { status, data } = await apiInstance.deleteStaffApiV1AdminStaffSidDelete(
    sid
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **sid** | [**string**] |  | defaults to undefined|


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

# **deleteStaffApiV1AdminStaffSidDelete_0**
> any deleteStaffApiV1AdminStaffSidDelete_0()


### Example

```typescript
import {
    StaffApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new StaffApi(configuration);

let sid: string; // (default to undefined)

const { status, data } = await apiInstance.deleteStaffApiV1AdminStaffSidDelete_0(
    sid
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **sid** | [**string**] |  | defaults to undefined|


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

# **getActivityApiV1AdminStaffSidActivityGet**
> any getActivityApiV1AdminStaffSidActivityGet()


### Example

```typescript
import {
    StaffApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new StaffApi(configuration);

let sid: string; // (default to undefined)

const { status, data } = await apiInstance.getActivityApiV1AdminStaffSidActivityGet(
    sid
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **sid** | [**string**] |  | defaults to undefined|


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

# **getActivityApiV1AdminStaffSidActivityGet_0**
> any getActivityApiV1AdminStaffSidActivityGet_0()


### Example

```typescript
import {
    StaffApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new StaffApi(configuration);

let sid: string; // (default to undefined)

const { status, data } = await apiInstance.getActivityApiV1AdminStaffSidActivityGet_0(
    sid
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **sid** | [**string**] |  | defaults to undefined|


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

# **getSessionsApiV1AdminStaffSidSessionsGet**
> any getSessionsApiV1AdminStaffSidSessionsGet()

Get login session history for a staff member.

### Example

```typescript
import {
    StaffApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new StaffApi(configuration);

let sid: string; // (default to undefined)

const { status, data } = await apiInstance.getSessionsApiV1AdminStaffSidSessionsGet(
    sid
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **sid** | [**string**] |  | defaults to undefined|


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

# **getSessionsApiV1AdminStaffSidSessionsGet_0**
> any getSessionsApiV1AdminStaffSidSessionsGet_0()

Get login session history for a staff member.

### Example

```typescript
import {
    StaffApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new StaffApi(configuration);

let sid: string; // (default to undefined)

const { status, data } = await apiInstance.getSessionsApiV1AdminStaffSidSessionsGet_0(
    sid
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **sid** | [**string**] |  | defaults to undefined|


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

# **getStaffApiV1AdminStaffSidGet**
> any getStaffApiV1AdminStaffSidGet()


### Example

```typescript
import {
    StaffApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new StaffApi(configuration);

let sid: string; // (default to undefined)

const { status, data } = await apiInstance.getStaffApiV1AdminStaffSidGet(
    sid
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **sid** | [**string**] |  | defaults to undefined|


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

# **getStaffApiV1AdminStaffSidGet_0**
> any getStaffApiV1AdminStaffSidGet_0()


### Example

```typescript
import {
    StaffApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new StaffApi(configuration);

let sid: string; // (default to undefined)

const { status, data } = await apiInstance.getStaffApiV1AdminStaffSidGet_0(
    sid
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **sid** | [**string**] |  | defaults to undefined|


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

# **heartbeatApiV1AdminStaffHeartbeatPost**
> any heartbeatApiV1AdminStaffHeartbeatPost()

Update last_active. Decodes JWT directly, no FastAPI auth dep.

### Example

```typescript
import {
    StaffApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new StaffApi(configuration);

let body: object; // (optional)

const { status, data } = await apiInstance.heartbeatApiV1AdminStaffHeartbeatPost(
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

# **heartbeatApiV1AdminStaffHeartbeatPost_0**
> any heartbeatApiV1AdminStaffHeartbeatPost_0()

Update last_active. Decodes JWT directly, no FastAPI auth dep.

### Example

```typescript
import {
    StaffApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new StaffApi(configuration);

let body: object; // (optional)

const { status, data } = await apiInstance.heartbeatApiV1AdminStaffHeartbeatPost_0(
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

# **listRolesApiV1AdminStaffRolesListGet**
> any listRolesApiV1AdminStaffRolesListGet()


### Example

```typescript
import {
    StaffApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new StaffApi(configuration);

const { status, data } = await apiInstance.listRolesApiV1AdminStaffRolesListGet();
```

### Parameters
This endpoint does not have any parameters.


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

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **listRolesApiV1AdminStaffRolesListGet_0**
> any listRolesApiV1AdminStaffRolesListGet_0()


### Example

```typescript
import {
    StaffApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new StaffApi(configuration);

const { status, data } = await apiInstance.listRolesApiV1AdminStaffRolesListGet_0();
```

### Parameters
This endpoint does not have any parameters.


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

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **listStaffApiV1AdminStaffGet**
> any listStaffApiV1AdminStaffGet()

List all staff with current online status.

### Example

```typescript
import {
    StaffApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new StaffApi(configuration);

const { status, data } = await apiInstance.listStaffApiV1AdminStaffGet();
```

### Parameters
This endpoint does not have any parameters.


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

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **listStaffApiV1AdminStaffGet_0**
> any listStaffApiV1AdminStaffGet_0()

List all staff with current online status.

### Example

```typescript
import {
    StaffApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new StaffApi(configuration);

const { status, data } = await apiInstance.listStaffApiV1AdminStaffGet_0();
```

### Parameters
This endpoint does not have any parameters.


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

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **loginEventApiV1AdminStaffLoginEventPost**
> any loginEventApiV1AdminStaffLoginEventPost()

Record a new login session.

### Example

```typescript
import {
    StaffApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new StaffApi(configuration);

let body: object; // (optional)

const { status, data } = await apiInstance.loginEventApiV1AdminStaffLoginEventPost(
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

# **loginEventApiV1AdminStaffLoginEventPost_0**
> any loginEventApiV1AdminStaffLoginEventPost_0()

Record a new login session.

### Example

```typescript
import {
    StaffApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new StaffApi(configuration);

let body: object; // (optional)

const { status, data } = await apiInstance.loginEventApiV1AdminStaffLoginEventPost_0(
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

# **logoutEventApiV1AdminStaffLogoutEventPost**
> any logoutEventApiV1AdminStaffLogoutEventPost()

Close active session.

### Example

```typescript
import {
    StaffApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new StaffApi(configuration);

const { status, data } = await apiInstance.logoutEventApiV1AdminStaffLogoutEventPost();
```

### Parameters
This endpoint does not have any parameters.


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

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **logoutEventApiV1AdminStaffLogoutEventPost_0**
> any logoutEventApiV1AdminStaffLogoutEventPost_0()

Close active session.

### Example

```typescript
import {
    StaffApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new StaffApi(configuration);

const { status, data } = await apiInstance.logoutEventApiV1AdminStaffLogoutEventPost_0();
```

### Parameters
This endpoint does not have any parameters.


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

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **updateStaffApiV1AdminStaffSidPatch**
> any updateStaffApiV1AdminStaffSidPatch(body)


### Example

```typescript
import {
    StaffApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new StaffApi(configuration);

let sid: string; // (default to undefined)
let body: object; //

const { status, data } = await apiInstance.updateStaffApiV1AdminStaffSidPatch(
    sid,
    body
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **body** | **object**|  | |
| **sid** | [**string**] |  | defaults to undefined|


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

# **updateStaffApiV1AdminStaffSidPatch_0**
> any updateStaffApiV1AdminStaffSidPatch_0(body)


### Example

```typescript
import {
    StaffApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new StaffApi(configuration);

let sid: string; // (default to undefined)
let body: object; //

const { status, data } = await apiInstance.updateStaffApiV1AdminStaffSidPatch_0(
    sid,
    body
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **body** | **object**|  | |
| **sid** | [**string**] |  | defaults to undefined|


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

# **uploadAvatarApiV1AdminStaffSidAvatarPost**
> any uploadAvatarApiV1AdminStaffSidAvatarPost(body)

Upload avatar as base64 data URL. Max 500KB.

### Example

```typescript
import {
    StaffApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new StaffApi(configuration);

let sid: string; // (default to undefined)
let body: object; //

const { status, data } = await apiInstance.uploadAvatarApiV1AdminStaffSidAvatarPost(
    sid,
    body
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **body** | **object**|  | |
| **sid** | [**string**] |  | defaults to undefined|


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

# **uploadAvatarApiV1AdminStaffSidAvatarPost_0**
> any uploadAvatarApiV1AdminStaffSidAvatarPost_0(body)

Upload avatar as base64 data URL. Max 500KB.

### Example

```typescript
import {
    StaffApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new StaffApi(configuration);

let sid: string; // (default to undefined)
let body: object; //

const { status, data } = await apiInstance.uploadAvatarApiV1AdminStaffSidAvatarPost_0(
    sid,
    body
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **body** | **object**|  | |
| **sid** | [**string**] |  | defaults to undefined|


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

