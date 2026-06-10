# TalonOne::IntegrationHubFlowResponse

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** | ID of the integration hub flow. |  |
| **integration_name** | **String** | Name of the integration. | [optional] |
| **instance_name** | **String** | Name of the integration instance. | [optional] |
| **created_at** | **Time** | Timestamp when the flow was created. |  |
| **disabled_until** | **Time** | Timestamp until which the flow is disabled. Null when the flow is active. | [optional] |
| **application_id** | **Integer** | ID of the application the flow is registered for. | [optional] |
| **loyalty_program_id** | **Integer** | ID of the loyalty program the flow is registered for. | [optional] |
| **event_type** | **String** | The event type we want to register a flow for. |  |
| **integration_hub_flow_url** | **String** | The URL of the integration hub flow that we want to trigger for the event. |  |
| **config** | [**IntegrationHubFlowConfigResponse**](IntegrationHubFlowConfigResponse.md) |  |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::IntegrationHubFlowResponse.new(
  id: null,
  integration_name: null,
  instance_name: null,
  created_at: null,
  disabled_until: null,
  application_id: 54,
  loyalty_program_id: 12,
  event_type: null,
  integration_hub_flow_url: null,
  config: null
)
```

