# TalonOne::CartItem

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **name** | **String** | Name of item. | [optional] |
| **sku** | **String** | Stock keeping unit of item. |  |
| **quantity** | **Integer** | Number of units of this item. Due to [cart item flattening](https://docs.talon.one/docs/product/rules/understanding-cart-item-flattening), if you provide a quantity greater than 1, the item will be split in as many items as the provided quantity. This will impact the number of **per-item** effects triggered from your campaigns.  |  |
| **returned_quantity** | **Integer** | Number of returned items, calculated internally based on returns of this item. | [optional] |
| **remaining_quantity** | **Integer** | Remaining quantity of the item, calculated internally based on returns of this item. | [optional] |
| **price** | **Float** | Price of the item in the currency defined by your Application. This field is required if this item is not part of a [catalog](https://docs.talon.one/docs/product/account/dev-tools/managing-cart-item-catalogs). If it is part of a catalog, setting a price here overrides the price from the catalog.  | [optional] |
| **category** | **String** | Type, group or model of the item. | [optional] |
| **product** | [**Product**](Product.md) |  | [optional] |
| **weight** | **Float** | Weight of item in grams. | [optional] |
| **height** | **Float** | Height of item in mm. | [optional] |
| **width** | **Float** | Width of item in mm. | [optional] |
| **length** | **Float** | Length of item in mm. | [optional] |
| **position** | **Float** | Position of the Cart Item in the Cart (calculated internally). | [optional] |
| **attributes** | **Object** | Use this property to set a value for the attributes of your choice. [Attributes](https://docs.talon.one/docs/dev/concepts/attributes) represent any information to attach to this cart item.  Custom _cart item_ attributes must be created in the Campaign Manager before you set them with this property.  **Note:** Any previously defined attributes that you do not include in the array will be removed.  | [optional] |
| **additional_costs** | [**Hash&lt;String, AdditionalCost&gt;**](AdditionalCost.md) | Use this property to set a value for the additional costs of this item, such as a shipping cost. They must be created in the Campaign Manager before you set them with this property. See [Managing additional costs](https://docs.talon.one/docs/product/account/dev-tools/managing-additional-costs).  | [optional] |
| **catalog_item_id** | **Integer** | The catalog item ID. | [optional] |
| **selected_price_type** | **String** | The selected price type for this cart item (e.g. the price for members only). | [optional] |
| **adjustment_reference_id** | **String** | The reference ID of the selected price adjustment for this cart item. Only returned if the selected price resulted from a price adjustment. | [optional] |
| **adjustment_effective_from** | **Time** | The date and time from which the price adjustment is effective. Only returned if the selected price resulted from a price adjustment that contains this field. | [optional] |
| **adjustment_effective_until** | **Time** | The date and time until which the price adjustment is effective. Only returned if the selected price resulted from a price adjustment that contains this field. | [optional] |
| **prices** | [**Hash&lt;String, PriceDetail&gt;**](PriceDetail.md) | A map of keys and values representing the price types and related price adjustment details for this cart item. The keys correspond to the &#x60;priceType&#x60; names.  | [optional] |

## Example

```ruby
require 'talon_one'

instance = TalonOne::CartItem.new(
  name: Air Glide,
  sku: SKU1241028,
  quantity: 1,
  returned_quantity: 1,
  remaining_quantity: 1,
  price: 99.99,
  category: shoes,
  product: null,
  weight: 1130,
  height: null,
  width: null,
  length: null,
  position: null,
  attributes: {image&#x3D;11.jpeg, material&#x3D;leather},
  additional_costs: {shipping&#x3D;{price&#x3D;9}},
  catalog_item_id: null,
  selected_price_type: member,
  adjustment_reference_id: 68851723-e6fa-488f-ace9-112581e6c19b,
  adjustment_effective_from: 2021-09-12T10:12:42Z,
  adjustment_effective_until: 2021-09-12T10:12:42Z,
  prices: {member&#x3D;{price&#x3D;90, adjustmentReferenceId&#x3D;68851723-e6fa-488f-ace9-112581e6c19b, effectiveFrom&#x3D;2025-05-25T00:00:00Z, effectiveUntil&#x3D;2025-05-30T00:00:00Z}, base&#x3D;{price&#x3D;100}}
)
```

