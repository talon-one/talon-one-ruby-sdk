# TalonOne::CatalogActionPatch

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **type** | **String** | A catalog sync action discriminator of type &#x60;PATCH&#x60;. |  |
| **payload** | [**PatchItemCatalogAction**](PatchItemCatalogAction.md) | The payload of sync action. |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::CatalogActionPatch.new(
  type: null,
  payload: null
)
```

