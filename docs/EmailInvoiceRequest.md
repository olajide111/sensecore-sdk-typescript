# EmailInvoiceRequest

Request body for emailing a single invoice.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**recipient_email** | **string** |  | [default to undefined]
**cc_emails** | **string** |  | [optional] [default to undefined]
**message** | **string** |  | [optional] [default to undefined]
**copy_to_sender** | **boolean** |  | [optional] [default to false]

## Example

```typescript
import { EmailInvoiceRequest } from '@sensecore/sdk';

const instance: EmailInvoiceRequest = {
    recipient_email,
    cc_emails,
    message,
    copy_to_sender,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
