# TalonOne::SortSelectorStep

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **type** | **String** | A step discriminator of type &#x60;sort&#x60;. |  |
| **fields** | [**Array&lt;SortSelectorStepField&gt;**](SortSelectorStepField.md) | One or more fields to sort by, applied in order. Each field has its own direction. |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::SortSelectorStep.new(
  type: sort,
  fields: null
)
```

