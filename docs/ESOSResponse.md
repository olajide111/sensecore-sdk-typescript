# ESOSResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**report_type** | **string** |  | [optional] [default to 'ESOS Phase 4']
**organisation** | **string** |  | [default to undefined]
**period** | **string** |  | [default to undefined]
**year** | **number** |  | [default to undefined]
**generated_at** | **string** |  | [default to undefined]
**total_energy_kwh** | **number** |  | [default to undefined]
**significant_energy_consumption** | **Array&lt;object&gt;** |  | [default to undefined]
**energy_audits** | **Array&lt;object&gt;** |  | [default to undefined]
**recommendations** | **Array&lt;object&gt;** |  | [default to undefined]
**compliance_route** | **string** |  | [default to undefined]
**lead_assessor_required** | **boolean** |  | [optional] [default to true]
**status** | **string** |  | [optional] [default to 'evidence_pack']

## Example

```typescript
import { ESOSResponse } from '@sensecore/sdk';

const instance: ESOSResponse = {
    report_type,
    organisation,
    period,
    year,
    generated_at,
    total_energy_kwh,
    significant_energy_consumption,
    energy_audits,
    recommendations,
    compliance_route,
    lead_assessor_required,
    status,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
