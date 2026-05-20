# EngRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**meter_id** | **string** |  | [optional] [default to undefined]
**readings** | **Array&lt;object&gt;** |  | [optional] [default to undefined]
**annual_kwh** | **number** |  | [optional] [default to undefined]
**floor_area_m2** | **number** |  | [optional] [default to undefined]
**building_type** | **string** |  | [optional] [default to undefined]
**revenue_gbp** | **number** |  | [optional] [default to undefined]
**fte_count** | **number** |  | [optional] [default to undefined]
**outdoor_temps_c** | **Array&lt;number&gt;** |  | [optional] [default to undefined]
**base_temp_c** | **number** |  | [optional] [default to 15.5]
**fuel_type** | **string** |  | [optional] [default to 'electricity']
**investment_gbp** | **number** |  | [optional] [default to undefined]
**annual_saving_gbp** | **number** |  | [optional] [default to undefined]
**discount_rate** | **number** |  | [optional] [default to 0.035]
**project_years** | **number** |  | [optional] [default to 10]
**inflation_rate** | **number** |  | [optional] [default to 0.03]
**wall_area_m2** | **number** |  | [optional] [default to undefined]
**wall_u_value** | **number** |  | [optional] [default to undefined]
**roof_area_m2** | **number** |  | [optional] [default to undefined]
**roof_u_value** | **number** |  | [optional] [default to undefined]
**window_area_m2** | **number** |  | [optional] [default to undefined]
**window_u_value** | **number** |  | [optional] [default to undefined]
**floor_area_ground_m2** | **number** |  | [optional] [default to undefined]
**floor_u_value** | **number** |  | [optional] [default to undefined]
**ventilation_rate** | **number** |  | [optional] [default to undefined]
**indoor_temp_c** | **number** |  | [optional] [default to 21.0]
**outdoor_temp_c** | **number** |  | [optional] [default to 5.0]

## Example

```typescript
import { EngRequest } from '@sensecore/sdk';

const instance: EngRequest = {
    meter_id,
    readings,
    annual_kwh,
    floor_area_m2,
    building_type,
    revenue_gbp,
    fte_count,
    outdoor_temps_c,
    base_temp_c,
    fuel_type,
    investment_gbp,
    annual_saving_gbp,
    discount_rate,
    project_years,
    inflation_rate,
    wall_area_m2,
    wall_u_value,
    roof_area_m2,
    roof_u_value,
    window_area_m2,
    window_u_value,
    floor_area_ground_m2,
    floor_u_value,
    ventilation_rate,
    indoor_temp_c,
    outdoor_temp_c,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
