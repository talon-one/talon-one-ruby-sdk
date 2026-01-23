# TalonOne::CollectionsCatalog

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** | The internal ID of this collection. |  |
| **account_id** | **Integer** | The ID of the account that owns this collection. |  |
| **application_id** | **Integer** | The ID of the Application that owns this collection. |  |
| **title** | **String** | A short description of the collection catalog. |  |
| **description** | **String** | A longer, more detailed description of the collection catalog. | [optional] |
| **category** | **String** | Category used to group collection catalogs. |  |
| **source** | **String** | Indicates whether the collection is custom or shipped by Talon.One. |  |
| **rules** | [**Array&lt;CatalogRule&gt;**](CatalogRule.md) | Array of rule templates in this collection catalog. Rules only contain title (no description, as description is at the collection catalog level). |  |
| **cart_item_filters** | [**Array&lt;CartItemFilterTemplate&gt;**](CartItemFilterTemplate.md) | Array of cart item filter templates in this collection catalog. Cart item filters only contain name (no description, as description is at the collection catalog level). |  |
| **created** | **Time** | Timestamp when the collection was created. |  |
| **created_by** | **Integer** | ID of the user who created the collection. |  |
| **modified** | **Time** | Timestamp when the collection was last updated. | [optional] |
| **modified_by** | **Integer** | ID of the user who last updated the collection. | [optional] |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::CollectionsCatalog.new(
  id: null,
  account_id: null,
  application_id: null,
  title: High value cart discount,
  description: null,
  category: null,
  source: null,
  rules: null,
  cart_item_filters: null,
  created: null,
  created_by: null,
  modified: null,
  modified_by: null
)
```

