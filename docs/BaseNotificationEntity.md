# TalonOne::BaseNotificationEntity

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **policy** | **Object** | Indicates which notification properties to apply. |  |
| **enabled** | **Boolean** | Indicates whether the notification is activated. | [optional][default to true] |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::BaseNotificationEntity.new(
  policy: null,
  enabled: null
)
```

