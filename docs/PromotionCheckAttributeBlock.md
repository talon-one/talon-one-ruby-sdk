# TalonOne::PromotionCheckAttributeBlock

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** | Unique identifier for this block. |  |
| **type** | **String** | Identifies the block variant and determines which additional properties are present in it. |  |
| **tags** | **Array&lt;String&gt;** | Semantic labels attached to this block. | [optional] |
| **operator** | **String** | The comparison operator applied to the attribute. |  |
| **attribute** | **Object** |  |  |
| **value** | **Object** |  | [optional] |
| **min** | **Object** |  | [optional] |
| **max** | **Object** |  | [optional] |
| **start** | **Object** |  | [optional] |
| **_end** | **Object** |  | [optional] |
| **start_inclusive** | **Boolean** | When &#x60;true&#x60;, the &#x60;start&#x60; value is included in the range for the &#x60;within&#x60; operator. | [optional] |
| **end_inclusive** | **Boolean** | When &#x60;true&#x60;, the &#x60;end&#x60; value is included in the range for the &#x60;within&#x60; operator. | [optional] |
| **timezone_insensitive** | **Boolean** | Indicates whether the &#x60;within&#x60; operator ignores time zones and compares the wall-clock time only. When &#x60;false&#x60;, time zones are taken into account. | [optional] |
| **values** | **Object** |  | [optional] |
| **count** | **Object** |  | [optional] |
| **on_failure** | [**Array&lt;PromotionBlock&gt;**](PromotionBlock.md) | Promotion blocks evaluated when this block fails or returns false. | [optional] |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::PromotionCheckAttributeBlock.new(
  id: a1b2c3d4-e5f6-7890-abcd-ef1234567890,
  type: null,
  tags: null,
  operator: greaterThan,
  attribute: null,
  value: null,
  min: null,
  max: null,
  start: null,
  _end: null,
  start_inclusive: true,
  end_inclusive: true,
  timezone_insensitive: false,
  values: null,
  count: null,
  on_failure: null
)
```

