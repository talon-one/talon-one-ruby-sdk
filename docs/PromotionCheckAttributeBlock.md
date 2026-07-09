# TalonOne::PromotionCheckAttributeBlock

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **on_failure** | **Array&lt;Object&gt;** | Promotion blocks evaluated when this block fails or returns false. | [optional] |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::PromotionCheckAttributeBlock.new(
  on_failure: null
)
```

