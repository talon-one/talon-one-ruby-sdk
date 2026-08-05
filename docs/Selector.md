# TalonOne::Selector

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **name** | **String** | The name of the selector binding. |  |
| **type** | **String** | A binding of type &#x60;selector&#x60;. |  |
| **source** | **String** | The attribute path the pipeline draws items from. |  |
| **steps** | [**Array&lt;SelectorStep&gt;**](SelectorStep.md) | Ordered pipeline steps applied to the source items. |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::Selector.new(
  name: discountedCartItems,
  type: selector,
  source: $Session.CartItems,
  steps: null
)
```

