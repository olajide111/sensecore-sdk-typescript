# ComplianceApi

All URIs are relative to *https://api.sensecoreai.com*

|Method | HTTP request | Description|
|------------- | ------------- | -------------|
|[**generateEricApiV1ComplianceEricPost**](#generateericapiv1complianceericpost) | **POST** /api/v1/compliance/eric | Generate Eric|
|[**generateEricApiV1ComplianceEricPost_0**](#generateericapiv1complianceericpost_0) | **POST** /api/v1/compliance/eric | Generate Eric|
|[**generateEsosApiV1ComplianceEsosPost**](#generateesosapiv1complianceesospost) | **POST** /api/v1/compliance/esos | Generate Esos|
|[**generateEsosApiV1ComplianceEsosPost_0**](#generateesosapiv1complianceesospost_0) | **POST** /api/v1/compliance/esos | Generate Esos|
|[**generateSecrApiV1ComplianceSecrPost**](#generatesecrapiv1compliancesecrpost) | **POST** /api/v1/compliance/secr | Generate Secr|
|[**generateSecrApiV1ComplianceSecrPost_0**](#generatesecrapiv1compliancesecrpost_0) | **POST** /api/v1/compliance/secr | Generate Secr|
|[**generateShdfApiV1ComplianceShdfPost**](#generateshdfapiv1complianceshdfpost) | **POST** /api/v1/compliance/shdf | Generate Shdf|
|[**generateShdfApiV1ComplianceShdfPost_0**](#generateshdfapiv1complianceshdfpost_0) | **POST** /api/v1/compliance/shdf | Generate Shdf|
|[**getEpcTrackingApiV1ComplianceEpcGet**](#getepctrackingapiv1complianceepcget) | **GET** /api/v1/compliance/epc | Get Epc Tracking|
|[**getEpcTrackingApiV1ComplianceEpcGet_0**](#getepctrackingapiv1complianceepcget_0) | **GET** /api/v1/compliance/epc | Get Epc Tracking|

# **generateEricApiV1ComplianceEricPost**
> ERICResponse generateEricApiV1ComplianceEricPost(complianceRequest)

Generate NHS Estates Returns Information Collection (ERIC) energy data. ERIC requires: electricity, gas, oil, coal, steam, hot water consumption in kWh and GJ, plus CO2 emissions, floor area, and energy cost.

### Example

```typescript
import {
    ComplianceApi,
    Configuration,
    ComplianceRequest
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new ComplianceApi(configuration);

let complianceRequest: ComplianceRequest; //
let xAPIKey: string; // (optional) (default to undefined)

const { status, data } = await apiInstance.generateEricApiV1ComplianceEricPost(
    complianceRequest,
    xAPIKey
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **complianceRequest** | **ComplianceRequest**|  | |
| **xAPIKey** | [**string**] |  | (optional) defaults to undefined|


### Return type

**ERICResponse**

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

# **generateEricApiV1ComplianceEricPost_0**
> ERICResponse generateEricApiV1ComplianceEricPost_0(complianceRequest)

Generate NHS Estates Returns Information Collection (ERIC) energy data. ERIC requires: electricity, gas, oil, coal, steam, hot water consumption in kWh and GJ, plus CO2 emissions, floor area, and energy cost.

### Example

```typescript
import {
    ComplianceApi,
    Configuration,
    ComplianceRequest
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new ComplianceApi(configuration);

let complianceRequest: ComplianceRequest; //
let xAPIKey: string; // (optional) (default to undefined)

const { status, data } = await apiInstance.generateEricApiV1ComplianceEricPost_0(
    complianceRequest,
    xAPIKey
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **complianceRequest** | **ComplianceRequest**|  | |
| **xAPIKey** | [**string**] |  | (optional) defaults to undefined|


### Return type

**ERICResponse**

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

# **generateEsosApiV1ComplianceEsosPost**
> ESOSResponse generateEsosApiV1ComplianceEsosPost(complianceRequest)

Generate ESOS Phase 4 evidence pack. ESOS requires energy audits covering at least 90% of total energy, identification of energy savings opportunities, and lead assessor sign-off.

### Example

```typescript
import {
    ComplianceApi,
    Configuration,
    ComplianceRequest
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new ComplianceApi(configuration);

let complianceRequest: ComplianceRequest; //
let xAPIKey: string; // (optional) (default to undefined)

const { status, data } = await apiInstance.generateEsosApiV1ComplianceEsosPost(
    complianceRequest,
    xAPIKey
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **complianceRequest** | **ComplianceRequest**|  | |
| **xAPIKey** | [**string**] |  | (optional) defaults to undefined|


### Return type

**ESOSResponse**

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

# **generateEsosApiV1ComplianceEsosPost_0**
> ESOSResponse generateEsosApiV1ComplianceEsosPost_0(complianceRequest)

Generate ESOS Phase 4 evidence pack. ESOS requires energy audits covering at least 90% of total energy, identification of energy savings opportunities, and lead assessor sign-off.

### Example

```typescript
import {
    ComplianceApi,
    Configuration,
    ComplianceRequest
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new ComplianceApi(configuration);

let complianceRequest: ComplianceRequest; //
let xAPIKey: string; // (optional) (default to undefined)

const { status, data } = await apiInstance.generateEsosApiV1ComplianceEsosPost_0(
    complianceRequest,
    xAPIKey
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **complianceRequest** | **ComplianceRequest**|  | |
| **xAPIKey** | [**string**] |  | (optional) defaults to undefined|


### Return type

**ESOSResponse**

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

# **generateSecrApiV1ComplianceSecrPost**
> SECRResponse generateSecrApiV1ComplianceSecrPost(complianceRequest)

Generate Streamlined Energy and Carbon Report. SECR requires: Scope 1+2 emissions, at least one intensity ratio, prior year comparatives, and energy efficiency narrative.

### Example

```typescript
import {
    ComplianceApi,
    Configuration,
    ComplianceRequest
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new ComplianceApi(configuration);

let complianceRequest: ComplianceRequest; //
let xAPIKey: string; // (optional) (default to undefined)

const { status, data } = await apiInstance.generateSecrApiV1ComplianceSecrPost(
    complianceRequest,
    xAPIKey
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **complianceRequest** | **ComplianceRequest**|  | |
| **xAPIKey** | [**string**] |  | (optional) defaults to undefined|


### Return type

**SECRResponse**

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

# **generateSecrApiV1ComplianceSecrPost_0**
> SECRResponse generateSecrApiV1ComplianceSecrPost_0(complianceRequest)

Generate Streamlined Energy and Carbon Report. SECR requires: Scope 1+2 emissions, at least one intensity ratio, prior year comparatives, and energy efficiency narrative.

### Example

```typescript
import {
    ComplianceApi,
    Configuration,
    ComplianceRequest
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new ComplianceApi(configuration);

let complianceRequest: ComplianceRequest; //
let xAPIKey: string; // (optional) (default to undefined)

const { status, data } = await apiInstance.generateSecrApiV1ComplianceSecrPost_0(
    complianceRequest,
    xAPIKey
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **complianceRequest** | **ComplianceRequest**|  | |
| **xAPIKey** | [**string**] |  | (optional) defaults to undefined|


### Return type

**SECRResponse**

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

# **generateShdfApiV1ComplianceShdfPost**
> SHDFResponse generateShdfApiV1ComplianceShdfPost(complianceRequest)

Generate Social Housing Decarbonisation Fund (SHDF) readiness assessment. Uses FPRS scores to identify properties eligible for Wave 2 funding.

### Example

```typescript
import {
    ComplianceApi,
    Configuration,
    ComplianceRequest
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new ComplianceApi(configuration);

let complianceRequest: ComplianceRequest; //
let xAPIKey: string; // (optional) (default to undefined)

const { status, data } = await apiInstance.generateShdfApiV1ComplianceShdfPost(
    complianceRequest,
    xAPIKey
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **complianceRequest** | **ComplianceRequest**|  | |
| **xAPIKey** | [**string**] |  | (optional) defaults to undefined|


### Return type

**SHDFResponse**

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

# **generateShdfApiV1ComplianceShdfPost_0**
> SHDFResponse generateShdfApiV1ComplianceShdfPost_0(complianceRequest)

Generate Social Housing Decarbonisation Fund (SHDF) readiness assessment. Uses FPRS scores to identify properties eligible for Wave 2 funding.

### Example

```typescript
import {
    ComplianceApi,
    Configuration,
    ComplianceRequest
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new ComplianceApi(configuration);

let complianceRequest: ComplianceRequest; //
let xAPIKey: string; // (optional) (default to undefined)

const { status, data } = await apiInstance.generateShdfApiV1ComplianceShdfPost_0(
    complianceRequest,
    xAPIKey
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **complianceRequest** | **ComplianceRequest**|  | |
| **xAPIKey** | [**string**] |  | (optional) defaults to undefined|


### Return type

**SHDFResponse**

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

# **getEpcTrackingApiV1ComplianceEpcGet**
> any getEpcTrackingApiV1ComplianceEpcGet()

Get EPC band tracking for all buildings in the organisation. Returns current bands, target bands, and recommendations.

### Example

```typescript
import {
    ComplianceApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new ComplianceApi(configuration);

let xAPIKey: string; // (optional) (default to undefined)

const { status, data } = await apiInstance.getEpcTrackingApiV1ComplianceEpcGet(
    xAPIKey
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **xAPIKey** | [**string**] |  | (optional) defaults to undefined|


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

# **getEpcTrackingApiV1ComplianceEpcGet_0**
> any getEpcTrackingApiV1ComplianceEpcGet_0()

Get EPC band tracking for all buildings in the organisation. Returns current bands, target bands, and recommendations.

### Example

```typescript
import {
    ComplianceApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new ComplianceApi(configuration);

let xAPIKey: string; // (optional) (default to undefined)

const { status, data } = await apiInstance.getEpcTrackingApiV1ComplianceEpcGet_0(
    xAPIKey
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **xAPIKey** | [**string**] |  | (optional) defaults to undefined|


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

