# TalonOne::PrismaticFlowConfig

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **api_key** | **String** |  |  |
| **worker_count** | **Integer** | Number of Prismatic workers to run in parallel for this flow (maximum 500). | [optional][default to 10] |
| **max_events_per_message** | **Integer** | Maximum number of events to send in a single message to Prismatic. | [optional][default to 1000] |
| **max_retries** | **Integer** | Maximum number of retries for a Prismatic event before it is ignored. | [optional][default to 10] |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::PrismaticFlowConfig.new(
  api_key: null,
  worker_count: null,
  max_events_per_message: null,
  max_retries: null
)
```

