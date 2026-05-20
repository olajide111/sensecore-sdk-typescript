# InvoiceStatusRequest

Admin: update invoice status.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**invoice_id** | **string** |  | [default to undefined]
**status** | **string** |  | [default to undefined]
**amount_paid** | **number** |  | [optional] [default to undefined]

## Example

```typescript
import { InvoiceStatusRequest } from '@sensecore/sdk';

const instance: InvoiceStatusRequest = {
    invoice_id,
    status,
    amount_paid,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
