# TalonOne::PrismaticPaginatedEventPayload

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **total_result_size** | **Integer** |  |  |
| **batched_at** | **Time** | Timestamp when the batch was created. | [optional] |
| **event_type** | **String** |  |  |
| **data** | **Array&lt;Object&gt;** |  |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::PrismaticPaginatedEventPayload.new(
  total_result_size: null,
  batched_at: null,
  event_type: null,
  data: null
)
```

