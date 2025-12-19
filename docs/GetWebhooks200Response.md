# TalonOne::GetWebhooks200Response

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **total_result_size** | **Integer** |  |  |
| **data** | [**Array&lt;WebhookWithOutgoingIntegrationDetails&gt;**](WebhookWithOutgoingIntegrationDetails.md) |  |  |

## Example

```ruby
require 'talon_one'

instance = TalonOne::GetWebhooks200Response.new(
  total_result_size: 1,
  data: null
)
```

