# TalonOne::UpdateRiskNotification

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **entity** | **String** | The entity type to analyze within the given time frame. |  |
| **activity** | **String** | The activity metric to analyze within the given entity. |  |
| **time_frame** | **String** | The rolling time window for risk evaluation. |  |
| **active** | **Boolean** | Indicates whether this risk notification is active. |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::UpdateRiskNotification.new(
  entity: customer_profile,
  activity: loyalty_points_earned,
  time_frame: 1_week,
  active: true
)
```

