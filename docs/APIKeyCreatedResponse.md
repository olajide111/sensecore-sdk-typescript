# APIKeyCreatedResponse

Returned ONLY by create + rotate — contains the plaintext key. Frontend must show it once and warn the user to copy it now.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **string** |  | [default to undefined]
**name** | **string** |  | [default to undefined]
**prefix** | **string** |  | [default to undefined]
**last_used_at** | **string** |  | [optional] [default to undefined]
**revoked_at** | **string** |  | [optional] [default to undefined]
**created_at** | **string** |  | [optional] [default to undefined]
**created_by** | **string** |  | [optional] [default to undefined]
**full_key** | **string** | Plaintext key. Shown ONCE — store it immediately. | [default to undefined]

## Example

```typescript
import { APIKeyCreatedResponse } from '@sensecore/sdk';

const instance: APIKeyCreatedResponse = {
    id,
    name,
    prefix,
    last_used_at,
    revoked_at,
    created_at,
    created_by,
    full_key,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
