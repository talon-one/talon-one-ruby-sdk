# TalonOne::CatalogActionRemove

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **type** | **String** | A catalog sync action discriminator of type &#x60;REMOVE&#x60;. |  |
| **payload** | [**RemoveItemCatalogAction**](RemoveItemCatalogAction.md) | The payload of sync action. |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::CatalogActionRemove.new(
  type: null,
  payload: null
)
```

