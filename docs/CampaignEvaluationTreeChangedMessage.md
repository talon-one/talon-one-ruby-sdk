# TalonOne::CampaignEvaluationTreeChangedMessage

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **notification_type** | **String** | The type of the notification |  |
| **total_result_size** | **Integer** | The total size of the result set. |  |
| **data** | [**Array&lt;ApplicationNotification&gt;**](ApplicationNotification.md) | The array of changes. | [optional] |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::CampaignEvaluationTreeChangedMessage.new(
  notification_type: CampaignNotification,
  total_result_size: null,
  data: null
)
```

