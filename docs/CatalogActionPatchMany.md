# TalonOne::CatalogActionPatchMany

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **type** | **String** | A catalog sync action discriminator of type &#x60;PATCH_MANY&#x60;. |  |
| **payload** | [**PatchManyItemsCatalogAction**](PatchManyItemsCatalogAction.md) | The payload of sync action. |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::CatalogActionPatchMany.new(
  type: null,
  payload: null
)
```

