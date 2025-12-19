# TalonOne::NewInviteEmail

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **email** | **String** | Email address of the user. |  |
| **token** | **String** | Invitation token of the user. |  |

## Example

```ruby
require 'talon_one'

instance = TalonOne::NewInviteEmail.new(
  email: john.doe@example.com,
  token: Gy9b8w1irmQtEPo5RmbMmSPheL5h4
)
```

