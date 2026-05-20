# CreateUserRequest

Admin: create a new user.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**full_name** | **string** |  | [default to undefined]
**email** | **string** |  | [default to undefined]
**password** | **string** |  | [default to undefined]
**role** | **string** |  | [optional] [default to 'viewer']
**organisation_id** | **string** |  | [optional] [default to undefined]

## Example

```typescript
import { CreateUserRequest } from '@sensecore/sdk';

const instance: CreateUserRequest = {
    full_name,
    email,
    password,
    role,
    organisation_id,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
