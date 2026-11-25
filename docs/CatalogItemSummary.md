# TalonOne::CatalogItemSummary

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** | The internal ID of the catalog item. |  |
| **catalog_id** | **Integer** | The ID of the catalog the item belongs to. |  |
| **sku** | **String** | The stock keeping unit of the item. |  |
| **price** | **Float** | The price of the item. | [optional] |
| **product_name** | **String** | The name of the product the item belongs to. | [optional] |
| **product_id** | **Integer** | The ID of the product the item is linked to.  **Note:** Only returned when the product catalog integration is enabled.  | [optional] |
| **sku_id** | **Integer** | The ID of the SKU the item is linked to.  **Note:** Only returned when the product catalog integration is enabled.  | [optional] |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::CatalogItemSummary.new(
  id: 6,
  catalog_id: 6,
  sku: SKU1241028,
  price: 99.99,
  product_name: Running shoes,
  product_id: 12,
  sku_id: 34
)
```

