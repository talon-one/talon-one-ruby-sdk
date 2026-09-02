# TalonOne::CampaignLoyaltyProgram

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** | The ID of the loyalty program. |  |
| **name** | **String** | The name of the loyalty program. |  |
| **tiers** | **Array&lt;String&gt;** | The names of the tiers in the loyalty program. |  |
| **card_based** | **Boolean** | Whether the loyalty program is card-based. |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::CampaignLoyaltyProgram.new(
  id: 5,
  name: My program,
  tiers: [&quot;Silver&quot;,&quot;Gold&quot;,&quot;Platinum&quot;],
  card_based: false
)
```

