# TalonOne::CatalogActionRemoveMany

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **type** | **String** | A catalog sync action discriminator of type &#x60;REMOVE_MANY&#x60;. |  |
| **payload** | [**RemoveManyItemsCatalogAction**](RemoveManyItemsCatalogAction.md) | The payload of sync action. |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::CatalogActionRemoveMany.new(
  type: null,
  payload: null
)
```

