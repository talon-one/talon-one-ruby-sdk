# TalonOne::CampaignCreatedNotificationItem

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **event** | **String** | The type of the event. Can be one of the following: [&#39;campaign_state_changed&#39;, &#39;campaign_ruleset_changed&#39;, &#39;campaign_edited&#39;, &#39;campaign_created&#39;, &#39;campaign_deleted&#39;]  |  |
| **campaign** | **Object** | The campaign whose state changed. |  |
| **ruleset** | **Object** | The current ruleset. | [optional] |
| **evaluation_position** | **Object** | The campaign position within the evaluation tree. |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::CampaignCreatedNotificationItem.new(
  event: campaign_state_changed,
  campaign: null,
  ruleset: null,
  evaluation_position: null
)
```

