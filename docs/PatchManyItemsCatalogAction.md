# TalonOne::PatchManyItemsCatalogAction

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **price** | **Float** | Price of the item. | [optional] |
| **filters** | [**Array&lt;CatalogActionFilter&gt;**](CatalogActionFilter.md) | The list of filters used to select the items to patch, joined by &#x60;AND&#x60;.  **Note:** Every item in the catalog will be modified if there are no filters.  | [optional] |
| **attributes** | **Object** | The attributes of the items to patch. | [optional] |

## Example

```ruby
require 'talon_one'

instance = TalonOne::PatchManyItemsCatalogAction.new(
  price: 99.99,
  filters: null,
  attributes: null
)
```

