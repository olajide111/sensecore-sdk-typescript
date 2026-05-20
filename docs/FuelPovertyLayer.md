# FuelPovertyLayer

Fuel poverty risk scoring (FPRS) — 5-signal index

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**fprs_score** | **number** |  | [default to undefined]
**risk_level** | **string** |  | [default to undefined]
**signal_safe_heating** | **number** |  | [default to undefined]
**signal_self_rationing** | **number** |  | [default to undefined]
**signal_evening_suppression** | **number** |  | [default to undefined]
**signal_weekend_pattern** | **number** |  | [default to undefined]
**signal_long_absence** | **number** |  | [default to undefined]
**flagged_for_review** | **boolean** |  | [default to undefined]

## Example

```typescript
import { FuelPovertyLayer } from '@sensecore/sdk';

const instance: FuelPovertyLayer = {
    fprs_score,
    risk_level,
    signal_safe_heating,
    signal_self_rationing,
    signal_evening_suppression,
    signal_weekend_pattern,
    signal_long_absence,
    flagged_for_review,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
