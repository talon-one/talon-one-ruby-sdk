# TalonOne::StrikethroughSetDiscountPerItemEffectProps

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **name** | **String** | effect name. |  |
| **value** | **Object** |  |  |
| **exclude_from_best_prior_price_history** | **Boolean** |  | [optional] |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::StrikethroughSetDiscountPerItemEffectProps.new(
  name: 1EuroOff,
  value: null,
  exclude_from_best_prior_price_history: null
)
```

