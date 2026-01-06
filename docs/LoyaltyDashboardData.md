# TalonOne::LoyaltyDashboardData

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **date** | **Time** | Date at which data point was collected. |  |
| **total_active_points** | **Float** | Total of active points for this loyalty program. |  |
| **total_pending_points** | **Float** | Total of pending points for this loyalty program. |  |
| **total_spent_points** | **Float** | Total of spent points for this loyalty program. |  |
| **total_expired_points** | **Float** | Total of expired points for this loyalty program. |  |
| **total_negative_points** | **Float** | Total of negative points for this loyalty program. |  |
| **total_members** | **Float** | Number of loyalty program members. |  |
| **new_members** | **Float** | Number of members who joined on this day. |  |
| **spent_points** | [**LoyaltyDashboardPointsBreakdown**](LoyaltyDashboardPointsBreakdown.md) | Points spent on this day. |  |
| **earned_points** | [**LoyaltyDashboardPointsBreakdown**](LoyaltyDashboardPointsBreakdown.md) | Points that were earned on this day. |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::LoyaltyDashboardData.new(
  date: null,
  total_active_points: 9756,
  total_pending_points: 548,
  total_spent_points: 25668,
  total_expired_points: 1156,
  total_negative_points: 32,
  total_members: 2582,
  new_members: 3,
  spent_points: null,
  earned_points: null
)
```

