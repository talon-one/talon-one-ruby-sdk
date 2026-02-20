# TalonOne::PrismaticEventRecord

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** |  |  |
| **flow_id** | **Integer** |  |  |
| **event_type** | **String** |  |  |
| **event_data** | **Object** |  |  |
| **published_at** | **Time** |  |  |
| **processed_at** | **Time** |  | [optional] |
| **process_after** | **Time** |  |  |
| **_retry** | **Integer** |  |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::PrismaticEventRecord.new(
  id: null,
  flow_id: null,
  event_type: null,
  event_data: null,
  published_at: null,
  processed_at: null,
  process_after: null,
  _retry: null
)
```

