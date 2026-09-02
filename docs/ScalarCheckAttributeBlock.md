# TalonOne::ScalarCheckAttributeBlock

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **operator** | **String** | The comparison operator applied to the attribute. | [optional] |
| **value** | **Object** | The comparison value for this operator. |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::ScalarCheckAttributeBlock.new(
  operator: null,
  value: 100
)
```

