# CarbonResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**meter_id** | **string** |  | [default to undefined]
**period** | **string** |  | [default to undefined]
**total_kgco2** | **number** |  | [default to undefined]
**total_kwh** | **number** |  | [default to undefined]
**carbon_intensity_gco2_kwh** | **number** |  | [default to undefined]
**scope** | **string** |  | [optional] [default to 'Scope 2']
**reporting_standard** | **string** |  | [optional] [default to 'SECR / EU EED']
**generated_at** | **string** |  | [default to undefined]

## Example

```typescript
import { CarbonResponse } from '@sensecore/sdk';

const instance: CarbonResponse = {
    meter_id,
    period,
    total_kgco2,
    total_kwh,
    carbon_intensity_gco2_kwh,
    scope,
    reporting_standard,
    generated_at,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
