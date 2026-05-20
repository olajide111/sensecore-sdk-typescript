# NotificationsApi

All URIs are relative to *https://api.sensecoreai.com*

|Method | HTTP request | Description|
|------------- | ------------- | -------------|
|[**clearNotificationsApiV1NotificationsDelete**](#clearnotificationsapiv1notificationsdelete) | **DELETE** /api/v1/notifications | Clear Notifications|
|[**clearNotificationsApiV1NotificationsDelete_0**](#clearnotificationsapiv1notificationsdelete_0) | **DELETE** /api/v1/notifications | Clear Notifications|
|[**listNotificationsApiV1NotificationsGet**](#listnotificationsapiv1notificationsget) | **GET** /api/v1/notifications | List Notifications|
|[**listNotificationsApiV1NotificationsGet_0**](#listnotificationsapiv1notificationsget_0) | **GET** /api/v1/notifications | List Notifications|
|[**markReadApiV1NotificationsReadPost**](#markreadapiv1notificationsreadpost) | **POST** /api/v1/notifications/read | Mark Read|
|[**markReadApiV1NotificationsReadPost_0**](#markreadapiv1notificationsreadpost_0) | **POST** /api/v1/notifications/read | Mark Read|
|[**unreadCountApiV1NotificationsUnreadCountGet**](#unreadcountapiv1notificationsunreadcountget) | **GET** /api/v1/notifications/unread-count | Unread Count|
|[**unreadCountApiV1NotificationsUnreadCountGet_0**](#unreadcountapiv1notificationsunreadcountget_0) | **GET** /api/v1/notifications/unread-count | Unread Count|

# **clearNotificationsApiV1NotificationsDelete**
> any clearNotificationsApiV1NotificationsDelete()


### Example

```typescript
import {
    NotificationsApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new NotificationsApi(configuration);

const { status, data } = await apiInstance.clearNotificationsApiV1NotificationsDelete();
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

# **clearNotificationsApiV1NotificationsDelete_0**
> any clearNotificationsApiV1NotificationsDelete_0()


### Example

```typescript
import {
    NotificationsApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new NotificationsApi(configuration);

const { status, data } = await apiInstance.clearNotificationsApiV1NotificationsDelete_0();
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

# **listNotificationsApiV1NotificationsGet**
> any listNotificationsApiV1NotificationsGet()


### Example

```typescript
import {
    NotificationsApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new NotificationsApi(configuration);

let limit: number; // (optional) (default to 50)

const { status, data } = await apiInstance.listNotificationsApiV1NotificationsGet(
    limit
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **limit** | [**number**] |  | (optional) defaults to 50|


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

# **listNotificationsApiV1NotificationsGet_0**
> any listNotificationsApiV1NotificationsGet_0()


### Example

```typescript
import {
    NotificationsApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new NotificationsApi(configuration);

let limit: number; // (optional) (default to 50)

const { status, data } = await apiInstance.listNotificationsApiV1NotificationsGet_0(
    limit
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **limit** | [**number**] |  | (optional) defaults to 50|


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

# **markReadApiV1NotificationsReadPost**
> any markReadApiV1NotificationsReadPost(body)


### Example

```typescript
import {
    NotificationsApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new NotificationsApi(configuration);

let body: object; //

const { status, data } = await apiInstance.markReadApiV1NotificationsReadPost(
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

# **markReadApiV1NotificationsReadPost_0**
> any markReadApiV1NotificationsReadPost_0(body)


### Example

```typescript
import {
    NotificationsApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new NotificationsApi(configuration);

let body: object; //

const { status, data } = await apiInstance.markReadApiV1NotificationsReadPost_0(
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

# **unreadCountApiV1NotificationsUnreadCountGet**
> any unreadCountApiV1NotificationsUnreadCountGet()


### Example

```typescript
import {
    NotificationsApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new NotificationsApi(configuration);

const { status, data } = await apiInstance.unreadCountApiV1NotificationsUnreadCountGet();
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

# **unreadCountApiV1NotificationsUnreadCountGet_0**
> any unreadCountApiV1NotificationsUnreadCountGet_0()


### Example

```typescript
import {
    NotificationsApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new NotificationsApi(configuration);

const { status, data } = await apiInstance.unreadCountApiV1NotificationsUnreadCountGet_0();
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

