# TalonOne::PrismaticEventPayloadLoyaltyProfileBasedNotification

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **profile_integration_id** | **String** |  |  |
| **loyalty_program_id** | **Integer** |  |  |
| **subledger_id** | **String** |  |  |
| **source_of_event** | **String** |  |  |
| **employee_name** | **String** |  | [optional] |
| **user_id** | **Integer** |  | [optional] |
| **current_points** | **Float** |  |  |
| **actions** | [**Array&lt;PrismaticEventPayloadLoyaltyProfileBasedPointsChangedNotificationAction&gt;**](PrismaticEventPayloadLoyaltyProfileBasedPointsChangedNotificationAction.md) |  | [optional] |
| **published_at** | **Time** | Timestamp when the event was published. |  |
| **current_tier** | **String** |  | [optional] |
| **old_tier** | **String** |  | [optional] |
| **tier_expiration_date** | **Time** |  | [optional] |
| **timestamp_of_tier_change** | **Time** |  | [optional] |
| **points_required_to_the_next_tier** | **Float** |  | [optional] |
| **next_tier** | **String** |  | [optional] |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::PrismaticEventPayloadLoyaltyProfileBasedNotification.new(
  profile_integration_id: null,
  loyalty_program_id: null,
  subledger_id: null,
  source_of_event: null,
  employee_name: null,
  user_id: null,
  current_points: null,
  actions: null,
  published_at: null,
  current_tier: null,
  old_tier: null,
  tier_expiration_date: null,
  timestamp_of_tier_change: null,
  points_required_to_the_next_tier: null,
  next_tier: null
)
```

