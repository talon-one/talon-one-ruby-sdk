# TalonOne::NewCollectionsCatalog

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **title** | **String** | The display name for the collection catalog. |  |
| **description** | **String** | A longer, more detailed description of the collection catalog. | [optional] |
| **category** | **String** | Category used to group collection catalogs. | [optional][default to &#39;custom&#39;] |
| **rules** | [**Array&lt;CatalogRule&gt;**](CatalogRule.md) | Array of rules to store in this collection catalog. Rules should only contain title (no description, as description is at the collection catalog level). At least one rule or cart item filter is required. | [optional] |
| **cart_item_filters** | [**Array&lt;CartItemFilterTemplate&gt;**](CartItemFilterTemplate.md) | Array of cart item filters to store in this collection catalog. If not provided, will be extracted from the rules. Cart item filters should only contain name (no description, as description is at the collection catalog level). | [optional] |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::NewCollectionsCatalog.new(
  title: Customer loyalty boost,
  description: null,
  category: null,
  rules: null,
  cart_item_filters: null
)
```

