# TalonOne::AddPriceAdjustmentCatalogAction

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **sku** | **String** | The SKU of the item for which the price is being adjusted. |  |
| **adjustments** | [**Array&lt;NewPriceAdjustment&gt;**](NewPriceAdjustment.md) | A list of adjustments to apply to a given item. |  |

## Example

```ruby
require 'talon_one'

instance = TalonOne::AddPriceAdjustmentCatalogAction.new(
  sku: SKU1241028,
  adjustments: null
)
```

