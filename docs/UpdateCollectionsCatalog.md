# TalonOne::UpdateCollectionsCatalog

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **title** | **String** | The display name for the collection catalog. | [optional] |
| **description** | **String** | A longer, more detailed description of the collection catalog. | [optional] |
| **category** | **String** | Category used to group collection catalogs. | [optional] |
| **rules** | [**Array&lt;CatalogRule&gt;**](CatalogRule.md) | Replaces the stored rules. Rules should only contain title (no description, as description is at the collection catalog level). | [optional] |
| **cart_item_filters** | [**Array&lt;CartItemFilterTemplate&gt;**](CartItemFilterTemplate.md) | Replaces the stored cart item filters. Cart item filters should only contain name (no description, as description is at the collection catalog level). | [optional] |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::UpdateCollectionsCatalog.new(
  title: null,
  description: null,
  category: null,
  rules: null,
  cart_item_filters: null
)
```

