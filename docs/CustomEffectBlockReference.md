# TalonOne::CustomEffectBlockReference

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** | The unique identifier of the custom effect. |  |
| **name** | **String** | The name of the custom effect, as used in API requests. |  |
| **title** | **String** | The display name of the custom effect. |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::CustomEffectBlockReference.new(
  id: 1,
  name: sendEmail,
  title: Send email
)
```

