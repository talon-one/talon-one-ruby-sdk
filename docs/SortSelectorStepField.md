# TalonOne::SortSelectorStepField

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **expression** | **String** | The attribute path the items are sorted by. |  |
| **direction** | **String** | The sort direction for this field. |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::SortSelectorStepField.new(
  expression: $Item.Price,
  direction: asc
)
```

