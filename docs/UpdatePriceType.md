# TalonOne::UpdatePriceType

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **title** | **String** | The name displayed in the Campaign Manager for the price type. |  |
| **description** | **String** | A description of the price type. | [optional] |
| **targeted_audiences_ids** | **Array&lt;Integer&gt;** | A list of the IDs of the audiences targeted by this price type. |  |

## Example

```ruby
require 'talon_one'

instance = TalonOne::UpdatePriceType.new(
  title: Member Price,
  description: The price available exclusively to members.,
  targeted_audiences_ids: [1, 2, 3]
)
```

