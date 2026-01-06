# TalonOne::CampaignEvaluationTreeChangedNotification

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **application_id** | **Integer** | The ID of the Application whose campaign evaluation tree changed. |  |
| **old_evaluation_tree** | [**CampaignSet**](CampaignSet.md) | The previous campaign evaluation tree. | [optional] |
| **evaluation_tree** | [**CampaignSet**](CampaignSet.md) | The new campaign evaluation tree. |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::CampaignEvaluationTreeChangedNotification.new(
  application_id: 78,
  old_evaluation_tree: null,
  evaluation_tree: null
)
```

