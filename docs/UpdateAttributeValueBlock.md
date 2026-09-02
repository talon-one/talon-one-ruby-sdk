# TalonOne::UpdateAttributeValueBlock

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** | Unique identifier for this block. | [optional][readonly] |
| **type** | **String** | Identifies the block variant and determines which additional properties are present in it. |  |
| **tags** | **Array&lt;String&gt;** | Semantic labels attached to this block. | [optional] |
| **operator** | **String** | The update operation applied to the attribute. |  |
| **attribute** | [**UpdateAttributeValueBlock1Attribute**](UpdateAttributeValueBlock1Attribute.md) |  |  |
| **value** | **Object** | The value of the attribute. Omitted when operator is set to &#x60;toggle&#x60;. | [optional] |
| **target** | [**UpdateAttributeValueBlock1Target**](UpdateAttributeValueBlock1Target.md) |  |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::UpdateAttributeValueBlock.new(
  id: a1b2c3d4-e5f6-7890-abcd-ef1234567890,
  type: null,
  tags: null,
  operator: setTo,
  attribute: null,
  value: 10,
  target: null
)
```

