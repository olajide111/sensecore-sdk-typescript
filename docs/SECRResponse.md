# SECRResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**report_type** | **string** |  | [optional] [default to 'SECR']
**organisation** | **string** |  | [default to undefined]
**period** | **string** |  | [default to undefined]
**year** | **number** |  | [default to undefined]
**generated_at** | **string** |  | [default to undefined]
**scope1_kgco2e** | **number** |  | [default to undefined]
**scope1_source** | **string** |  | [default to undefined]
**scope2_kgco2e** | **number** |  | [default to undefined]
**scope2_source** | **string** |  | [default to undefined]
**total_kgco2e** | **number** |  | [default to undefined]
**total_tco2e** | **number** |  | [default to undefined]
**total_kwh** | **number** |  | [default to undefined]
**intensity_revenue** | **number** |  | [optional] [default to undefined]
**intensity_area** | **number** |  | [optional] [default to undefined]
**intensity_fte** | **number** |  | [optional] [default to undefined]
**previous_year_tco2e** | **number** |  | [optional] [default to undefined]
**yoy_change_pct** | **number** |  | [optional] [default to undefined]
**defra_year** | **number** |  | [default to undefined]
**defra_electricity_factor** | **number** |  | [default to undefined]
**defra_gas_factor** | **number** |  | [default to undefined]
**methodology** | **string** |  | [default to undefined]
**recommendations** | **Array&lt;object&gt;** |  | [default to undefined]
**status** | **string** |  | [optional] [default to 'complete']

## Example

```typescript
import { SECRResponse } from '@sensecore/sdk';

const instance: SECRResponse = {
    report_type,
    organisation,
    period,
    year,
    generated_at,
    scope1_kgco2e,
    scope1_source,
    scope2_kgco2e,
    scope2_source,
    total_kgco2e,
    total_tco2e,
    total_kwh,
    intensity_revenue,
    intensity_area,
    intensity_fte,
    previous_year_tco2e,
    yoy_change_pct,
    defra_year,
    defra_electricity_factor,
    defra_gas_factor,
    methodology,
    recommendations,
    status,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
