# TalonOne::BulkApplicationNotification

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **total_result_size** | **Integer** |  |  |
| **data** | [**Array&lt;CampaignEvaluationTreeChangedNotification&gt;**](CampaignEvaluationTreeChangedNotification.md) |  |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::BulkApplicationNotification.new(
  total_result_size: 1,
  data: null
)
```

