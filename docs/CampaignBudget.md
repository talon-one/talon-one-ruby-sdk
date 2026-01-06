# TalonOne::CampaignBudget

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **action** | **String** | The limitable action to which this limit applies. For example: - &#x60;setDiscount&#x60; - &#x60;setDiscountEffect&#x60; - &#x60;redeemCoupon&#x60; - &#x60;createCoupon&#x60;  |  |
| **limit** | **Float** | The value to set for the limit. |  |
| **counter** | **Float** | The number of occurrences of the limited action in the context of the campaign. |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::CampaignBudget.new(
  action: createCoupon,
  limit: 1000,
  counter: 42
)
```

