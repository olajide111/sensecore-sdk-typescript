# ComplianceRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**meter_id** | **string** |  | [optional] [default to undefined]
**org_id** | **string** |  | [optional] [default to undefined]
**period** | **string** |  | [optional] [default to 'annual']
**year** | **number** |  | [optional] [default to undefined]
**readings** | **Array&lt;object&gt;** |  | [optional] [default to undefined]
**revenue_gbp** | **number** |  | [optional] [default to undefined]
**floor_area_m2** | **number** |  | [optional] [default to undefined]
**fte_count** | **number** |  | [optional] [default to undefined]

## Example

```typescript
import { ComplianceRequest } from '@sensecore/sdk';

const instance: ComplianceRequest = {
    meter_id,
    org_id,
    period,
    year,
    readings,
    revenue_gbp,
    floor_area_m2,
    fte_count,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
