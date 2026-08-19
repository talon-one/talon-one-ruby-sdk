# TalonOne::CatalogActionAdd

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **type** | **String** | A catalog sync action discriminator of type &#x60;ADD&#x60;. |  |
| **payload** | [**AddItemCatalogAction**](AddItemCatalogAction.md) | The payload of sync action. |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::CatalogActionAdd.new(
  type: null,
  payload: null
)
```

