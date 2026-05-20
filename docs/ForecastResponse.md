# ForecastResponse

Full SenseCore AI intelligence bundle — one response per meter request

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**meter_id** | **string** |  | [default to undefined]
**forecast_kwh** | **Array&lt;number&gt;** |  | [default to undefined]
**lower_80** | **Array&lt;number&gt;** |  | [default to undefined]
**upper_80** | **Array&lt;number&gt;** |  | [default to undefined]
**mape_benchmark** | **number** |  | [default to undefined]
**model_version** | **string** |  | [default to undefined]
**generated_at** | **string** |  | [default to undefined]
**carbon** | [**CarbonLayer**](CarbonLayer.md) |  | [default to undefined]
**anomaly** | [**AnomalyLayer**](AnomalyLayer.md) |  | [default to undefined]
**fuel_poverty** | [**FuelPovertyLayer**](FuelPovertyLayer.md) |  | [default to undefined]
**occupancy** | [**OccupancyLayer**](OccupancyLayer.md) |  | [default to undefined]
**estimated_cost_gbp** | **number** |  | [default to undefined]
**annual_cost_gbp** | **number** |  | [default to undefined]

## Example

```typescript
import { ForecastResponse } from '@sensecore/sdk';

const instance: ForecastResponse = {
    meter_id,
    forecast_kwh,
    lower_80,
    upper_80,
    mape_benchmark,
    model_version,
    generated_at,
    carbon,
    anomaly,
    fuel_poverty,
    occupancy,
    estimated_cost_gbp,
    annual_cost_gbp,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
