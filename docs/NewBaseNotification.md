# TalonOne::NewBaseNotification

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **policy** | **Object** | Indicates which notification properties to apply. |  |
| **enabled** | **Boolean** | Indicates whether the notification is activated. | [optional][default to true] |
| **webhook** | [**NewNotificationWebhook**](NewNotificationWebhook.md) |  |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::NewBaseNotification.new(
  policy: null,
  enabled: null,
  webhook: null
)
```

