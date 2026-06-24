# TalonOne::PassthroughBlock

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** | Unique identifier for this block. |  |
| **type** | **String** | The type discriminator for this block. |  |
| **expression** | **Array&lt;Object&gt;** | The raw Talang expression as an array. The first element is the function name; subsequent elements are its arguments, which may themselves be nested expressions. |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::PassthroughBlock.new(
  id: a1b2c3d4-e5f6-7890-abcd-ef1234567890,
  type: null,
  expression: null
)
```

