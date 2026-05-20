# OnboardingApi

All URIs are relative to *https://api.sensecoreai.com*

|Method | HTTP request | Description|
|------------- | ------------- | -------------|
|[**completeTourApiV1OnboardingCompleteTourPost**](#completetourapiv1onboardingcompletetourpost) | **POST** /api/v1/onboarding/complete-tour | Complete Tour|
|[**dismissChecklistApiV1OnboardingDismissPost**](#dismisschecklistapiv1onboardingdismisspost) | **POST** /api/v1/onboarding/dismiss | Dismiss Checklist|
|[**getStatusApiV1OnboardingStatusGet**](#getstatusapiv1onboardingstatusget) | **GET** /api/v1/onboarding/status | Get Status|
|[**markForecastRunApiV1OnboardingMarkForecastRunPost**](#markforecastrunapiv1onboardingmarkforecastrunpost) | **POST** /api/v1/onboarding/mark-forecast-run | Mark Forecast Run|
|[**reopenChecklistApiV1OnboardingReopenPost**](#reopenchecklistapiv1onboardingreopenpost) | **POST** /api/v1/onboarding/reopen | Reopen Checklist|
|[**setPersonaApiV1OnboardingPersonaPost**](#setpersonaapiv1onboardingpersonapost) | **POST** /api/v1/onboarding/persona | Set Persona|

# **completeTourApiV1OnboardingCompleteTourPost**
> SimpleOk completeTourApiV1OnboardingCompleteTourPost()

Mark the spotlight tour as completed/skipped so it never reappears.

### Example

```typescript
import {
    OnboardingApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new OnboardingApi(configuration);

const { status, data } = await apiInstance.completeTourApiV1OnboardingCompleteTourPost();
```

### Parameters
This endpoint does not have any parameters.


### Return type

**SimpleOk**

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

# **dismissChecklistApiV1OnboardingDismissPost**
> SimpleOk dismissChecklistApiV1OnboardingDismissPost()

Mark the floating checklist as dismissed (it can still be reopened).

### Example

```typescript
import {
    OnboardingApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new OnboardingApi(configuration);

const { status, data } = await apiInstance.dismissChecklistApiV1OnboardingDismissPost();
```

### Parameters
This endpoint does not have any parameters.


### Return type

**SimpleOk**

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

# **getStatusApiV1OnboardingStatusGet**
> OnboardingStatus getStatusApiV1OnboardingStatusGet()

Return current onboarding state for the authenticated user.

### Example

```typescript
import {
    OnboardingApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new OnboardingApi(configuration);

const { status, data } = await apiInstance.getStatusApiV1OnboardingStatusGet();
```

### Parameters
This endpoint does not have any parameters.


### Return type

**OnboardingStatus**

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

# **markForecastRunApiV1OnboardingMarkForecastRunPost**
> SimpleOk markForecastRunApiV1OnboardingMarkForecastRunPost()

Set the flag indicating the user clicked Run Forecast at least once. Used as a fallback when forecast_results table is unavailable.

### Example

```typescript
import {
    OnboardingApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new OnboardingApi(configuration);

const { status, data } = await apiInstance.markForecastRunApiV1OnboardingMarkForecastRunPost();
```

### Parameters
This endpoint does not have any parameters.


### Return type

**SimpleOk**

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

# **reopenChecklistApiV1OnboardingReopenPost**
> SimpleOk reopenChecklistApiV1OnboardingReopenPost()

Clear the dismissed flag so the checklist reappears.

### Example

```typescript
import {
    OnboardingApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new OnboardingApi(configuration);

const { status, data } = await apiInstance.reopenChecklistApiV1OnboardingReopenPost();
```

### Parameters
This endpoint does not have any parameters.


### Return type

**SimpleOk**

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

# **setPersonaApiV1OnboardingPersonaPost**
> SimpleOk setPersonaApiV1OnboardingPersonaPost(personaRequest)

Record the user\'s persona and optionally seed sector-specific demo buildings.

### Example

```typescript
import {
    OnboardingApi,
    Configuration,
    PersonaRequest
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new OnboardingApi(configuration);

let personaRequest: PersonaRequest; //

const { status, data } = await apiInstance.setPersonaApiV1OnboardingPersonaPost(
    personaRequest
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **personaRequest** | **PersonaRequest**|  | |


### Return type

**SimpleOk**

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

