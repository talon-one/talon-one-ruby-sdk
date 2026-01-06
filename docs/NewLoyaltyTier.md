# TalonOne::NewLoyaltyTier

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **name** | **String** | The name of the tier. |  |
| **min_points** | **Float** | The minimum amount of points required to enter the tier. |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::NewLoyaltyTier.new(
  name: Gold,
  min_points: 300
)
```

