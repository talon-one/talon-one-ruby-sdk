# TalonOne::CheckTierBlock1Tier

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** | The ID of the tier. |  |
| **name** | **String** | The display name of the tier. |  |
| **min_points** | **Float** | The minimum amount of points required to enter the tier. |  |
| **upper_limit** | **Float** |  | [optional] |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::CheckTierBlock1Tier.new(
  id: 42,
  name: Bronze,
  min_points: 150,
  upper_limit: null
)
```

