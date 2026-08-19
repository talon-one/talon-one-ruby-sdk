# TalonOne::CatalogActionAddPriceAdjustment

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **type** | **String** | A catalog sync action discriminator of type &#x60;ADD_PRICE_ADJUSTMENT&#x60;. |  |
| **payload** | [**AddPriceAdjustmentCatalogAction**](AddPriceAdjustmentCatalogAction.md) | The payload of sync action. |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::CatalogActionAddPriceAdjustment.new(
  type: null,
  payload: null
)
```

