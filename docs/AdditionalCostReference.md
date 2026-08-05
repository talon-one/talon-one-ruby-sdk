# TalonOne::AdditionalCostReference

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** | The internal identifier of the additional cost. |  |
| **name** | **String** | The additional cost name as used in API requests. |  |
| **title** | **String** | The human-readable title of the additional cost. | [optional] |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::AdditionalCostReference.new(
  id: 42,
  name: shipping,
  title: Shipping
)
```

