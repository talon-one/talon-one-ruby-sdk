# TalonOne::ChangeProfilePassword

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **password** | **String** | Your old password. |  |
| **new_password** | **String** | Your new password. |  |

## Example

```ruby
require 'talon_one'

instance = TalonOne::ChangeProfilePassword.new(
  password: Admin&amp;12943!7,
  new_password: Admin*4552$70
)
```

