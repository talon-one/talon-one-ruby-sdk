# TalonOne::CampaignDeletedNotificationItem

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **event** | **String** | The type of the event. Can be one of the following: [&#39;campaign_state_changed&#39;, &#39;campaign_ruleset_changed&#39;, &#39;campaign_edited&#39;, &#39;campaign_created&#39;, &#39;campaign_deleted&#39;]  |  |
| **campaign** | [**Campaign**](Campaign.md) | The campaign whose state changed. |  |
| **deleted_at** | **Time** | Time when the campaign was deleted. |  |

## Example

```ruby
require 'talon_one'

instance = TalonOne::CampaignDeletedNotificationItem.new(
  event: campaign_state_changed,
  campaign: null,
  deleted_at: 2022-11-10T23:00:00Z
)
```

