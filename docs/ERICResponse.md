# ERICResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**report_type** | **string** |  | [optional] [default to 'NHS ERIC']
**organisation** | **string** |  | [default to undefined]
**period** | **string** |  | [default to undefined]
**year** | **number** |  | [default to undefined]
**generated_at** | **string** |  | [default to undefined]
**electricity_kwh** | **number** |  | [default to undefined]
**gas_kwh** | **number** |  | [default to undefined]
**oil_kwh** | **number** |  | [default to undefined]
**coal_kwh** | **number** |  | [default to undefined]
**steam_kwh** | **number** |  | [default to undefined]
**hot_water_kwh** | **number** |  | [default to undefined]
**total_energy_kwh** | **number** |  | [default to undefined]
**total_energy_gj** | **number** |  | [default to undefined]
**co2_emissions_tonnes** | **number** |  | [default to undefined]
**floor_area_m2** | **number** |  | [optional] [default to undefined]
**energy_cost_gbp** | **number** |  | [optional] [default to undefined]
**renewable_generation_kwh** | **number** |  | [optional] [default to 0]
**chp_kwh** | **number** |  | [optional] [default to 0]
**backlog_maintenance_gbp** | **number** |  | [optional] [default to undefined]
**status** | **string** |  | [optional] [default to 'complete']

## Example

```typescript
import { ERICResponse } from '@sensecore/sdk';

const instance: ERICResponse = {
    report_type,
    organisation,
    period,
    year,
    generated_at,
    electricity_kwh,
    gas_kwh,
    oil_kwh,
    coal_kwh,
    steam_kwh,
    hot_water_kwh,
    total_energy_kwh,
    total_energy_gj,
    co2_emissions_tonnes,
    floor_area_m2,
    energy_cost_gbp,
    renewable_generation_kwh,
    chp_kwh,
    backlog_maintenance_gbp,
    status,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
