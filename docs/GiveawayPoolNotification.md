# TalonOne::GiveawayPoolNotification

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **total_result_size** | **Integer** |  |  |
| **data** | [**Array&lt;GiveawayPoolNotificationData&gt;**](GiveawayPoolNotificationData.md) | The array of giveaway pool notifications. |  |
| **notification_type** | **String** | The type of notification. |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::GiveawayPoolNotification.new(
  total_result_size: 1,
  data: null,
  notification_type: null
)
```

