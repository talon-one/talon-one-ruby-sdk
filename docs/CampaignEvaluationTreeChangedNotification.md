# TalonOne::CampaignEvaluationTreeChangedNotification

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **notification_type** | **String** | The type of the notification |  |
| **total_result_size** | **Integer** | The total size of the result set. |  |
| **data** | [**Array&lt;CampaignEvaluationTreeChangedNotificationData&gt;**](CampaignEvaluationTreeChangedNotificationData.md) | The array of changes. |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::CampaignEvaluationTreeChangedNotification.new(
  notification_type: CampaignEvaluationTreeChanged,
  total_result_size: null,
  data: null
)
```

