# BuildingsMapApi

All URIs are relative to *https://api.sensecoreai.com*

|Method | HTTP request | Description|
|------------- | ------------- | -------------|
|[**geocodeOneBuildingApiV1BuildingsBuildingIdGeocodePost**](#geocodeonebuildingapiv1buildingsbuildingidgeocodepost) | **POST** /api/v1/buildings/{building_id}/geocode | Geocode One Building|
|[**getBuildingsForMapApiV1BuildingsMapGet**](#getbuildingsformapapiv1buildingsmapget) | **GET** /api/v1/buildings/map | Get Buildings For Map|

# **geocodeOneBuildingApiV1BuildingsBuildingIdGeocodePost**
> any geocodeOneBuildingApiV1BuildingsBuildingIdGeocodePost()

Force geocoding for one building. Useful when a postcode is added after creation or an earlier geocoding attempt failed.  Auth: building must belong to the caller\'s org.

### Example

```typescript
import {
    BuildingsMapApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new BuildingsMapApi(configuration);

let buildingId: string; // (default to undefined)

const { status, data } = await apiInstance.geocodeOneBuildingApiV1BuildingsBuildingIdGeocodePost(
    buildingId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **buildingId** | [**string**] |  | defaults to undefined|


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

# **getBuildingsForMapApiV1BuildingsMapGet**
> any getBuildingsForMapApiV1BuildingsMapGet()

Return all mapped buildings for the current org with computed RAG status.  Response shape:     {       \"portfolio_type\": \"Commercial Estate\" | \"Residential Portfolio\",       \"summary\": { total, red, amber, green, grey, mapped },       \"buildings\": [         { id, name, address, postcode, latitude, longitude,           building_type, floor_area_m2, eui, benchmark_eui,           annual_kwh, annual_cost_gbp, anomaly_count,           energy_types, rag_status }       ]     }

### Example

```typescript
import {
    BuildingsMapApi,
    Configuration
} from '@sensecore/sdk';

const configuration = new Configuration();
const apiInstance = new BuildingsMapApi(configuration);

const { status, data } = await apiInstance.getBuildingsForMapApiV1BuildingsMapGet();
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

