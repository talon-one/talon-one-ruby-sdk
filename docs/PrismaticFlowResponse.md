# TalonOne::PrismaticFlowResponse

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** | ID of the prismatic flow. |  |
| **application_id** | **Integer** | ID of application the flow is registered for. | [optional] |
| **event_type** | **String** | The event type we want to register a flow for. |  |
| **prismatic_flow_url** | **String** | The URL of the prismatic flow that we want to trigger for the event. |  |
| **config** | [**PrismaticFlowConfigResponse**](PrismaticFlowConfigResponse.md) |  |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::PrismaticFlowResponse.new(
  id: null,
  application_id: 54,
  event_type: null,
  prismatic_flow_url: null,
  config: null
)
```

