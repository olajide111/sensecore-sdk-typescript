# EnergyForecastRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**meter_id** | **string** |  | [optional] [default to 'METER-BDG2-001']
**readings** | **Array&lt;object&gt;** |  | [optional] [default to undefined]
**horizon** | **number** |  | [optional] [default to 48]
**include_uncertainty** | **boolean** |  | [optional] [default to true]
**sector** | **string** |  | [optional] [default to 'commercial']

## Example

```typescript
import { EnergyForecastRequest } from '@sensecore/sdk';

const instance: EnergyForecastRequest = {
    meter_id,
    readings,
    horizon,
    include_uncertainty,
    sector,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
