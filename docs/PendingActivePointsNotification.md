# TalonOne::PendingActivePointsNotification

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **total_result_size** | **Integer** |  |  |
| **data** | [**Array&lt;PendingActivePointsData&gt;**](PendingActivePointsData.md) | The array of pending points. |  |
| **notification_type** | **String** | The type of notification. |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::PendingActivePointsNotification.new(
  total_result_size: 1,
  data: null,
  notification_type: null
)
```

