# TalonOne::PrismaticFlowConfigResponse

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **worker_count** | **Integer** | Number of Prismatic workers to run in parallel for this flow (maximum 500). | [optional] |
| **max_events_per_message** | **Integer** | Maximum number of events to send in a single message to Prismatic. | [optional] |
| **max_retries** | **Integer** | Maximum number of retries for a Prismatic event before it is ignored. | [optional] |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::PrismaticFlowConfigResponse.new(
  worker_count: null,
  max_events_per_message: null,
  max_retries: null
)
```

