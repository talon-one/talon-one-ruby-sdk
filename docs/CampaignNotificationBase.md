# TalonOne::CampaignNotificationBase

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **notification_type** | **String** | The type of the notification |  |
| **total_result_size** | **Integer** | The total size of the result set. |  |

## Example

```ruby
require 'talon_one'

instance = TalonOne::CampaignNotificationBase.new(
  notification_type: CampaignNotification,
  total_result_size: null
)
```

