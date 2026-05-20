# SHDFResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**report_type** | **string** |  | [optional] [default to 'SHDF Wave 2']
**organisation** | **string** |  | [default to undefined]
**generated_at** | **string** |  | [default to undefined]
**properties_assessed** | **number** |  | [default to undefined]
**average_fprs** | **number** |  | [default to undefined]
**high_risk_count** | **number** |  | [default to undefined]
**medium_risk_count** | **number** |  | [default to undefined]
**low_risk_count** | **number** |  | [default to undefined]
**epc_distribution** | **object** |  | [default to undefined]
**below_band_c_count** | **number** |  | [default to undefined]
**shdf_eligible_count** | **number** |  | [default to undefined]
**estimated_funding_gbp** | **number** |  | [default to undefined]
**retrofit_measures** | **Array&lt;object&gt;** |  | [default to undefined]
**estimated_carbon_saving_tco2e** | **number** |  | [default to undefined]
**estimated_cost_saving_gbp** | **number** |  | [default to undefined]
**status** | **string** |  | [optional] [default to 'assessment']

## Example

```typescript
import { SHDFResponse } from '@sensecore/sdk';

const instance: SHDFResponse = {
    report_type,
    organisation,
    generated_at,
    properties_assessed,
    average_fprs,
    high_risk_count,
    medium_risk_count,
    low_risk_count,
    epc_distribution,
    below_band_c_count,
    shdf_eligible_count,
    estimated_funding_gbp,
    retrofit_measures,
    estimated_carbon_saving_tco2e,
    estimated_cost_saving_gbp,
    status,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
