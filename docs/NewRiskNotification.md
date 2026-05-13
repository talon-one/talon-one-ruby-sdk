# TalonOne::NewRiskNotification

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **entity** | **String** | The entity type to analyze within the given time frame. |  |
| **activity** | **String** | The activity metric to analyze within the given entity. |  |
| **time_frame** | **String** | The rolling time window for risk evaluation. |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::NewRiskNotification.new(
  entity: customer_profile,
  activity: loyalty_points_earned,
  time_frame: 1_week
)
```

