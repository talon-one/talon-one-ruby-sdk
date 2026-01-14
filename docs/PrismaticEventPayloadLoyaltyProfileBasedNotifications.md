# TalonOne::PrismaticEventPayloadLoyaltyProfileBasedNotifications

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **profile_integration_id** | **String** |  |  |
| **loyalty_program_id** | **Integer** |  |  |
| **subledger_id** | **String** |  |  |
| **source_of_event** | **String** |  |  |
| **employee_name** | **String** |  | [optional] |
| **user_id** | **Integer** |  | [optional] |
| **session_integration_id** | **String** |  | [optional] |
| **current_tier** | **String** |  | [optional] |
| **current_points** | **Float** |  |  |
| **old_tier** | **String** |  | [optional] |
| **points_required_to_the_next_tier** | **Float** |  | [optional] |
| **next_tier** | **String** |  | [optional] |
| **tier_expiration_date** | **Time** |  | [optional] |
| **timestamp_of_tier_change** | **Time** |  | [optional] |
| **actions** | [**Array&lt;PrismaticEventPayloadLoyaltyProfileBasedNotificationsAction&gt;**](PrismaticEventPayloadLoyaltyProfileBasedNotificationsAction.md) |  | [optional] |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::PrismaticEventPayloadLoyaltyProfileBasedNotifications.new(
  profile_integration_id: null,
  loyalty_program_id: null,
  subledger_id: null,
  source_of_event: null,
  employee_name: null,
  user_id: null,
  session_integration_id: null,
  current_tier: null,
  current_points: null,
  old_tier: null,
  points_required_to_the_next_tier: null,
  next_tier: null,
  tier_expiration_date: null,
  timestamp_of_tier_change: null,
  actions: null
)
```

