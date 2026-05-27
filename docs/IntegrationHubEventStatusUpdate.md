# TalonOne::IntegrationHubEventStatusUpdate

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **event_id** | **Integer** | The ID of the integration hub event. |  |
| **status** | **String** | The delivery outcome for the event. |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::IntegrationHubEventStatusUpdate.new(
  event_id: 123,
  status: null
)
```

