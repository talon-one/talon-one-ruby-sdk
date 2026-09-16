# TalonOne::WebhookBlockReference

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** | The unique identifier of the webhook. |  |
| **title** | **String** | The display name of the webhook. |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::WebhookBlockReference.new(
  id: 1,
  title: Thank you for your order.
)
```

