# TalonOne::TriggerWebhookBlock

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** | Unique identifier for this block. |  |
| **type** | **String** | Identifies the block variant and determines which additional properties are present in it. |  |
| **tags** | **Array&lt;String&gt;** | Semantic labels attached to this block. | [optional] |
| **webhook** | [**TriggerWebhookBlock1Webhook**](TriggerWebhookBlock1Webhook.md) |  |  |
| **params** | **Hash&lt;String, Object&gt;** | The webhook&#39;s parameters, in configured order. Each property name is the parameter&#39;s title, lowercased with spaces replaced by underscores (for example, &#x60;Order ID&#x60; becomes &#x60;order_id&#x60;); falls back to &#x60;param_0&#x60;, &#x60;param_1&#x60;, and so on if a title is blank or collides with another. | [optional] |
| **on_error** | **Hash&lt;String, Array&lt;PromotionBlock&gt;&gt;** | Named error handlers evaluated when a specific error occurs. | [optional] |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::TriggerWebhookBlock.new(
  id: a1b2c3d4-e5f6-7890-abcd-ef1234567890,
  type: null,
  tags: null,
  webhook: null,
  params: {order_id&#x3D;ORD-10293},
  on_error: null
)
```

