# TalonOne::StrikethroughTrigger

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** | The ID of the event that triggered the strikethrough labeling. |  |
| **type** | **String** | The type of event that triggered the strikethrough labeling. |  |
| **triggered_at** | **Time** | The creation time of the event that triggered the strikethrough labeling. |  |
| **total_affected_items** | **Integer** | The total number of items affected by the event that triggered the strikethrough labeling. |  |
| **payload** | **Object** | The arbitrary properties associated with this trigger type. |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::StrikethroughTrigger.new(
  id: 1,
  type: CATALOG_SYNC,
  triggered_at: 2020-06-10T09:05:27.993483Z,
  total_affected_items: 1500,
  payload: {catalogId&#x3D;2, catalogVersion&#x3D;100}
)
```

