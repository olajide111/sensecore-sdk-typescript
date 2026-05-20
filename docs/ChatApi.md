# ChatApi

All URIs are relative to *https://api.sensecoreai.com*

|Method | HTTP request | Description|
|------------- | ------------- | -------------|
|[**adminChatStatsApiV1ChatAdminStatsGet**](#adminchatstatsapiv1chatadminstatsget) | **GET** /api/v1/chat/admin/stats | Admin Chat Stats|
|[**adminConversationDetailApiV1ChatAdminConversationsConversationIdGet**](#adminconversationdetailapiv1chatadminconversationsconversationidget) | **GET** /api/v1/chat/admin/conversations/{conversation_id} | Admin Conversation Detail|
|[**adminGetChatConfigApiV1ChatAdminConfigGet**](#admingetchatconfigapiv1chatadminconfigget) | **GET** /api/v1/chat/admin/config | Admin Get Chat Config|
|[**adminGetWidgetsApiV1ChatAdminWidgetsGet**](#admingetwidgetsapiv1chatadminwidgetsget) | **GET** /api/v1/chat/admin/widgets | Admin Get Widgets|
|[**adminListConversationsApiV1ChatAdminConversationsGet**](#adminlistconversationsapiv1chatadminconversationsget) | **GET** /api/v1/chat/admin/conversations | Admin List Conversations|
|[**adminListLeadsApiV1ChatAdminLeadsGet**](#adminlistleadsapiv1chatadminleadsget) | **GET** /api/v1/chat/admin/leads | Admin List Leads|
|[**adminUpdateChatConfigApiV1ChatAdminConfigPut**](#adminupdatechatconfigapiv1chatadminconfigput) | **PUT** /api/v1/chat/admin/config | Admin Update Chat Config|
|[**adminUpdateLeadStatusApiV1ChatAdminLeadsLeadIdStatusPut**](#adminupdateleadstatusapiv1chatadminleadsleadidstatusput) | **PUT** /api/v1/chat/admin/leads/{lead_id}/status | Admin Update Lead Status|
|[**adminUpdateWidgetPromptApiV1ChatAdminWidgetsWidgetIdPromptPut**](#adminupdatewidgetpromptapiv1chatadminwidgetswidgetidpromptput) | **PUT** /api/v1/chat/admin/widgets/{widget_id}/prompt | Admin Update Widget Prompt|
|[**captureChatLeadApiV1ChatLeadPost**](#capturechatleadapiv1chatleadpost) | **POST** /api/v1/chat/lead | Capture Chat Lead|
|[**chatMessageApiV1ChatMessagePost**](#chatmessageapiv1chatmessagepost) | **POST** /api/v1/chat/message | Chat Message|
|[**chatMessageAuthenticatedApiV1ChatMessageAuthenticatedPost**](#chatmessageauthenticatedapiv1chatmessageauthenticatedpost) | **POST** /api/v1/chat/message/authenticated | Chat Message Authenticated|
|[**getChatConfigApiV1ChatConfigGet**](#getchatconfigapiv1chatconfigget) | **GET** /api/v1/chat/config | Get Chat Config|
|[**getChatHistoryApiV1ChatHistorySessionIdGet**](#getchathistoryapiv1chathistorysessionidget) | **GET** /api/v1/chat/history/{session_id} | Get Chat History|

# **adminChatStatsApiV1ChatAdminStatsGet**
> object adminChatStatsApiV1ChatAdminStatsGet()

Admin: chat dashboard stats.

### Example

```typescript
import {
    ChatApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new ChatApi(configuration);

const { status, data } = await apiInstance.adminChatStatsApiV1ChatAdminStatsGet();
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

# **adminConversationDetailApiV1ChatAdminConversationsConversationIdGet**
> object adminConversationDetailApiV1ChatAdminConversationsConversationIdGet()

Admin: view a specific conversation with messages.

### Example

```typescript
import {
    ChatApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new ChatApi(configuration);

let conversationId: string; // (default to undefined)

const { status, data } = await apiInstance.adminConversationDetailApiV1ChatAdminConversationsConversationIdGet(
    conversationId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **conversationId** | [**string**] |  | defaults to undefined|


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

# **adminGetChatConfigApiV1ChatAdminConfigGet**
> object adminGetChatConfigApiV1ChatAdminConfigGet()


### Example

```typescript
import {
    ChatApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new ChatApi(configuration);

const { status, data } = await apiInstance.adminGetChatConfigApiV1ChatAdminConfigGet();
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

# **adminGetWidgetsApiV1ChatAdminWidgetsGet**
> object adminGetWidgetsApiV1ChatAdminWidgetsGet()

Admin: list all chat widgets with their system prompts.

### Example

```typescript
import {
    ChatApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new ChatApi(configuration);

const { status, data } = await apiInstance.adminGetWidgetsApiV1ChatAdminWidgetsGet();
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

# **adminListConversationsApiV1ChatAdminConversationsGet**
> object adminListConversationsApiV1ChatAdminConversationsGet()

Admin: list all conversations.

### Example

```typescript
import {
    ChatApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new ChatApi(configuration);

let limit: number; // (optional) (default to 50)
let offset: number; // (optional) (default to 0)
let source: string; // (optional) (default to undefined)
let hasLead: boolean; // (optional) (default to undefined)

const { status, data } = await apiInstance.adminListConversationsApiV1ChatAdminConversationsGet(
    limit,
    offset,
    source,
    hasLead
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **limit** | [**number**] |  | (optional) defaults to 50|
| **offset** | [**number**] |  | (optional) defaults to 0|
| **source** | [**string**] |  | (optional) defaults to undefined|
| **hasLead** | [**boolean**] |  | (optional) defaults to undefined|


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

# **adminListLeadsApiV1ChatAdminLeadsGet**
> object adminListLeadsApiV1ChatAdminLeadsGet()

Admin: list all captured leads.

### Example

```typescript
import {
    ChatApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new ChatApi(configuration);

let limit: number; // (optional) (default to 50)
let offset: number; // (optional) (default to 0)
let status: string; // (optional) (default to undefined)

const { status, data } = await apiInstance.adminListLeadsApiV1ChatAdminLeadsGet(
    limit,
    offset,
    status
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **limit** | [**number**] |  | (optional) defaults to 50|
| **offset** | [**number**] |  | (optional) defaults to 0|
| **status** | [**string**] |  | (optional) defaults to undefined|


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

# **adminUpdateChatConfigApiV1ChatAdminConfigPut**
> object adminUpdateChatConfigApiV1ChatAdminConfigPut()

Admin: update chat settings.

### Example

```typescript
import {
    ChatApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new ChatApi(configuration);

const { status, data } = await apiInstance.adminUpdateChatConfigApiV1ChatAdminConfigPut();
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

# **adminUpdateLeadStatusApiV1ChatAdminLeadsLeadIdStatusPut**
> object adminUpdateLeadStatusApiV1ChatAdminLeadsLeadIdStatusPut()

Admin: update lead status.

### Example

```typescript
import {
    ChatApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new ChatApi(configuration);

let leadId: string; // (default to undefined)

const { status, data } = await apiInstance.adminUpdateLeadStatusApiV1ChatAdminLeadsLeadIdStatusPut(
    leadId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **leadId** | [**string**] |  | defaults to undefined|


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

# **adminUpdateWidgetPromptApiV1ChatAdminWidgetsWidgetIdPromptPut**
> object adminUpdateWidgetPromptApiV1ChatAdminWidgetsWidgetIdPromptPut()

Admin: update a widget\'s system_prompt. Takes effect on next message.

### Example

```typescript
import {
    ChatApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new ChatApi(configuration);

let widgetId: string; // (default to undefined)

const { status, data } = await apiInstance.adminUpdateWidgetPromptApiV1ChatAdminWidgetsWidgetIdPromptPut(
    widgetId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **widgetId** | [**string**] |  | defaults to undefined|


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

# **captureChatLeadApiV1ChatLeadPost**
> object captureChatLeadApiV1ChatLeadPost(leadCaptureRequest)

Capture a lead from the chat widget.

### Example

```typescript
import {
    ChatApi,
    Configuration,
    LeadCaptureRequest
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new ChatApi(configuration);

let leadCaptureRequest: LeadCaptureRequest; //

const { status, data } = await apiInstance.captureChatLeadApiV1ChatLeadPost(
    leadCaptureRequest
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **leadCaptureRequest** | **LeadCaptureRequest**|  | |


### Return type

**object**

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

# **chatMessageApiV1ChatMessagePost**
> object chatMessageApiV1ChatMessagePost(chatMessageRequest)

Send a message and get AI response. No auth required for marketing widget.

### Example

```typescript
import {
    ChatApi,
    Configuration,
    ChatMessageRequest
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new ChatApi(configuration);

let chatMessageRequest: ChatMessageRequest; //

const { status, data } = await apiInstance.chatMessageApiV1ChatMessagePost(
    chatMessageRequest
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **chatMessageRequest** | **ChatMessageRequest**|  | |


### Return type

**object**

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

# **chatMessageAuthenticatedApiV1ChatMessageAuthenticatedPost**
> object chatMessageAuthenticatedApiV1ChatMessageAuthenticatedPost(chatMessageRequest)

Send a message from an authenticated dashboard user.

### Example

```typescript
import {
    ChatApi,
    Configuration,
    ChatMessageRequest
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new ChatApi(configuration);

let chatMessageRequest: ChatMessageRequest; //

const { status, data } = await apiInstance.chatMessageAuthenticatedApiV1ChatMessageAuthenticatedPost(
    chatMessageRequest
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **chatMessageRequest** | **ChatMessageRequest**|  | |


### Return type

**object**

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

# **getChatConfigApiV1ChatConfigGet**
> object getChatConfigApiV1ChatConfigGet()

Public endpoint: get chat widget configuration.

### Example

```typescript
import {
    ChatApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new ChatApi(configuration);

const { status, data } = await apiInstance.getChatConfigApiV1ChatConfigGet();
```

### Parameters
This endpoint does not have any parameters.


### Return type

**object**

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

# **getChatHistoryApiV1ChatHistorySessionIdGet**
> object getChatHistoryApiV1ChatHistorySessionIdGet()

Get conversation history by session ID (for widget reload).

### Example

```typescript
import {
    ChatApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new ChatApi(configuration);

let sessionId: string; // (default to undefined)

const { status, data } = await apiInstance.getChatHistoryApiV1ChatHistorySessionIdGet(
    sessionId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **sessionId** | [**string**] |  | defaults to undefined|


### Return type

**object**

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

