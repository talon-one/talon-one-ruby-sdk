# TalonOne::FilterSelectorStep

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **type** | **String** | A step discriminator of type &#x60;filter&#x60;. |  |
| **predicate** | [**SelectorBlock**](SelectorBlock.md) |  |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::FilterSelectorStep.new(
  type: filter,
  predicate: null
)
```

