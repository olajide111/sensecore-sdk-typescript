# CreateInvoiceRequest

Admin: generate a new invoice for an organisation.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**org_id** | **string** |  | [default to undefined]
**amount** | **number** |  | [optional] [default to 0]
**plan** | **string** |  | [optional] [default to 'custom']
**billing_cycle** | **string** |  | [optional] [default to 'monthly']
**description** | **string** |  | [optional] [default to 'SenseCore AI Platform']
**client_address** | **string** |  | [optional] [default to undefined]
**client_phone** | **string** |  | [optional] [default to undefined]

## Example

```typescript
import { CreateInvoiceRequest } from '@sensecore/sdk';

const instance: CreateInvoiceRequest = {
    org_id,
    amount,
    plan,
    billing_cycle,
    description,
    client_address,
    client_phone,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
