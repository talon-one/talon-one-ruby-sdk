# TalonOne::RiskNotification

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** | The internal ID of this entity. |  |
| **created** | **Time** | The time this entity was created. |  |
| **entity** | **String** | The entity type to analyze within the given time frame. |  |
| **activity** | **String** | The activity metric to analyze within the given entity. |  |
| **time_frame** | **String** | The rolling time window for risk evaluation. |  |
| **active** | **Boolean** | Indicates whether this risk notification is active. |  |
| **modified** | **Time** | Timestamp of the most recent update. |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::RiskNotification.new(
  id: 6,
  created: 2020-06-10T09:05:27.993483Z,
  entity: customer_profile,
  activity: loyalty_points_earned,
  time_frame: 1_week,
  active: true,
  modified: 2026-04-16T09:05:27.993483Z
)
```

