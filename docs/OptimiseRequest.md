# OptimiseRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**meter_id** | **string** |  | [default to undefined]
**readings** | [**Array&lt;AppSchemasReadingItem&gt;**](AppSchemasReadingItem.md) |  | [default to undefined]
**tariffs** | **Array&lt;string&gt;** |  | [optional] [default to undefined]
**sector** | **string** |  | [optional] [default to undefined]

## Example

```typescript
import { OptimiseRequest } from '@sensecore/sdk';

const instance: OptimiseRequest = {
    meter_id,
    readings,
    tariffs,
    sector,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
