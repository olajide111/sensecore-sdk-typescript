# ForecastRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**meter_id** | **string** |  | [default to undefined]
**readings** | [**Array&lt;AppSchemasReadingItem&gt;**](AppSchemasReadingItem.md) |  | [default to undefined]
**horizon** | **number** |  | [optional] [default to 48]
**include_uncertainty** | **boolean** |  | [optional] [default to true]
**sector** | **string** |  | [optional] [default to undefined]

## Example

```typescript
import { ForecastRequest } from '@sensecore/sdk';

const instance: ForecastRequest = {
    meter_id,
    readings,
    horizon,
    include_uncertainty,
    sector,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
