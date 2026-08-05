# TalonOne::AwardDiscountBlock

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** | Unique identifier for this block. |  |
| **type** | **String** | Identifies the block variant and determines which additional properties are present in it. |  |
| **tags** | **Array&lt;String&gt;** | Semantic labels attached to this block. | [optional] |
| **name** | **String** | The human-readable label attached to the discount. |  |
| **value** | [**AwardDiscountBlock1Value**](AwardDiscountBlock1Value.md) |  |  |
| **partial** | **Boolean** | Whether to apply a partial discount when the requested value exceeds the configured budget. |  |
| **target** | [**AwardDiscountTarget**](AwardDiscountTarget.md) |  |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::AwardDiscountBlock.new(
  id: a1b2c3d4-e5f6-7890-abcd-ef1234567890,
  type: null,
  tags: null,
  name: 10% Off,
  value: null,
  partial: false,
  target: null
)
```

