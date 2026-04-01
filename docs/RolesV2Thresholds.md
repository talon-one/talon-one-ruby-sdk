# TalonOne::RolesV2Thresholds

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **loyalty_points_limit** | **Integer** | Maximum number of loyalty points a support user can award without approval. | [optional] |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::RolesV2Thresholds.new(
  loyalty_points_limit: 100
)
```

