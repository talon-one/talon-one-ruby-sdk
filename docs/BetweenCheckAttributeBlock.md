# TalonOne::BetweenCheckAttributeBlock

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **operator** | **String** | The range comparison operator. Must be &#x60;between&#x60;. | [optional] |
| **min** | **Object** | The minimum value allowed for the &#x60;between&#x60; operator. |  |
| **max** | **Object** | The maximum value allowed for the &#x60;between&#x60; operator. |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::BetweenCheckAttributeBlock.new(
  operator: null,
  min: 10,
  max: 100
)
```

