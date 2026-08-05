# TalonOne::AwardDiscountAdditionalCostTarget

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **type** | **String** | A target discriminator of type &#x60;additionalCost&#x60;. |  |
| **additional_cost** | [**AdditionalCostReference**](AdditionalCostReference.md) |  |  |
| **target** | [**AwardDiscountAdditionalCostTargetTarget**](AwardDiscountAdditionalCostTargetTarget.md) |  |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::AwardDiscountAdditionalCostTarget.new(
  type: null,
  additional_cost: null,
  target: null
)
```

