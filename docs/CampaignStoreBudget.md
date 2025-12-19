# TalonOne::CampaignStoreBudget

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** | The internal ID of this entity. |  |
| **created** | **Time** | The time this entity was created. |  |
| **campaign_id** | **Integer** | The ID of the campaign that owns this entity. |  |
| **store_id** | **Integer** | The ID of the store. |  |
| **limits** | [**Array&lt;CampaignStoreBudgetLimitConfig&gt;**](CampaignStoreBudgetLimitConfig.md) | The set of budget limits for stores linked to the campaign. |  |

## Example

```ruby
require 'talon_one'

instance = TalonOne::CampaignStoreBudget.new(
  id: 6,
  created: 2020-06-10T09:05:27.993483Z,
  campaign_id: 322,
  store_id: null,
  limits: null
)
```

