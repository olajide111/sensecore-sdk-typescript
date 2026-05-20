# CreateOrgRequest

Admin: create a new organisation.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **string** |  | [default to undefined]
**sector** | **string** |  | [optional] [default to 'commercial']
**plan_tier** | **string** |  | [optional] [default to 'starter']
**billing_email** | **string** |  | [optional] [default to undefined]

## Example

```typescript
import { CreateOrgRequest } from '@sensecore/sdk';

const instance: CreateOrgRequest = {
    name,
    sector,
    plan_tier,
    billing_email,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
