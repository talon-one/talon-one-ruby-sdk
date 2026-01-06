# TalonOne::ExpiringCardPointsNotification

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **total_result_size** | **Integer** |  |  |
| **data** | [**Array&lt;ExpiringCardPointsData&gt;**](ExpiringCardPointsData.md) | The array of expiring points. |  |
| **notification_type** | **String** | The type of notification. |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::ExpiringCardPointsNotification.new(
  total_result_size: 1,
  data: null,
  notification_type: null
)
```

