# TalonOne::AwardDiscountAllItemsTarget

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **type** | **String** | A target discriminator of type &#x60;allItems&#x60;. |  |
| **prorated** | **Boolean** | Whether to distribute the discount proportionally across the targeted items. | [optional] |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::AwardDiscountAllItemsTarget.new(
  type: null,
  prorated: true
)
```

