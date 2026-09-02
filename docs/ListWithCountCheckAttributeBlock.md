# TalonOne::ListWithCountCheckAttributeBlock

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **operator** | **String** | The list membership operator with a count threshold applied to the attribute. | [optional] |
| **values** | **Object** | The set of values to match against. |  |
| **count** | **Object** | The count threshold for this operator. |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::ListWithCountCheckAttributeBlock.new(
  operator: null,
  values: null,
  count: 2
)
```

