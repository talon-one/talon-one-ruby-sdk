# TalonOne::CheckAttributeBlock

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** | Unique identifier for this block. |  |
| **type** | **String** | Identifies the block variant and determines which additional properties are present in it. |  |
| **tags** | **Array&lt;String&gt;** | Semantic labels attached to this block. | [optional] |
| **operator** | **String** | The comparison operator applied to the attribute. |  |
| **attribute** | **String** | The attribute path identifier (e.g. \&quot;$Session.Total\&quot;). |  |
| **value** | **Object** |  | [optional] |
| **min** | **Object** |  | [optional] |
| **max** | **Object** |  | [optional] |
| **values** | **Object** |  | [optional] |
| **count** | **Object** |  | [optional] |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::CheckAttributeBlock.new(
  id: a1b2c3d4-e5f6-7890-abcd-ef1234567890,
  type: null,
  tags: null,
  operator: greaterThan,
  attribute: $Session.Total,
  value: null,
  min: null,
  max: null,
  values: null,
  count: null
)
```

