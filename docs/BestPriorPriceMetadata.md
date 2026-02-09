# TalonOne::BestPriorPriceMetadata

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **influencing_campaign_details** | [**Array&lt;InfluencingCampaignDetails&gt;**](InfluencingCampaignDetails.md) | Details about campaigns that influenced the final price. |  |
| **adjustment_details** | [**AdjustmentDetails**](AdjustmentDetails.md) | Details about the applied price adjustment. | [optional] |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::BestPriorPriceMetadata.new(
  influencing_campaign_details: null,
  adjustment_details: null
)
```

