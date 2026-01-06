# TalonOne::PatchItemCatalogAction

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **sku** | **String** | The unique SKU of the item to patch. |  |
| **price** | **Float** | Price of the item. | [optional] |
| **attributes** | **Object** | The attributes of the item to patch. | [optional] |
| **product** | [**Product**](Product.md) |  | [optional] |
| **create_if_not_exists** | **Boolean** | Indicates whether to create an item if the SKU does not exist. | [optional][default to false] |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::PatchItemCatalogAction.new(
  sku: null,
  price: 99.99,
  attributes: null,
  product: null,
  create_if_not_exists: null
)
```

