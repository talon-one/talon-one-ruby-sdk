# TalonOne::InfluencingCampaignDetails

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **campaign_id** | **Integer** | Identifier of the campaign that influenced the final price. |  |
| **discount_value** | **Float** | Discount value applied by the campaign. |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::InfluencingCampaignDetails.new(
  campaign_id: null,
  discount_value: null
)
```

