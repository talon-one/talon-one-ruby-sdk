# TalonOne::LoginParams

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **email** | **String** | The email address associated with the user profile. |  |
| **password** | **String** | The password for your account. |  |

## Example

```ruby
require 'talon_one'

instance = TalonOne::LoginParams.new(
  email: john.doe@example.com,
  password: admin123456
)
```

