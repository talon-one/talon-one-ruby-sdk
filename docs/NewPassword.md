# TalonOne::NewPassword

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **password** | **String** | The new password for your account. |  |
| **reset_token** | **String** |  |  |

## Example

```ruby
require 'talon_one'

instance = TalonOne::NewPassword.new(
  password: Admin&amp;12943!7,
  reset_token: Z2VgacVNkexLKBUIzsRDDZSGxnIkC53y
)
```

