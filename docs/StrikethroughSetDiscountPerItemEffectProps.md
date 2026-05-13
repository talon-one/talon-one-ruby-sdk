# TalonOne::StrikethroughSetDiscountPerItemEffectProps

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **name** | **String** | The effect name. |  |
| **value** | **Object** |  |  |
| **excluded_from_price_history** | **Boolean** | When set to &#x60;true&#x60;, the applied discount is excluded from the item&#39;s price history. | [optional] |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::StrikethroughSetDiscountPerItemEffectProps.new(
  name: 1EuroOff,
  value: null,
  excluded_from_price_history: null
)
```

