# TalonOne::LoyaltyBalance

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **active_points** | **Float** | Total amount of points awarded to this customer and available to spend. | [optional] |
| **pending_points** | **Float** | Total amount of points awarded to this customer but not available until their start date. | [optional] |
| **spent_points** | **Float** | Total amount of points already spent by this customer. | [optional] |
| **expired_points** | **Float** | Total amount of points awarded but never redeemed. They cannot be used anymore. | [optional] |
| **negative_points** | **Float** | Total amount of negative points. This implies that &#x60;activePoints&#x60; is &#x60;0&#x60;. | [optional] |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::LoyaltyBalance.new(
  active_points: 286,
  pending_points: 50,
  spent_points: 150,
  expired_points: 286,
  negative_points: 286
)
```

