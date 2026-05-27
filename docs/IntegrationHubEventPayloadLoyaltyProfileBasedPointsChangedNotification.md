# TalonOne::IntegrationHubEventPayloadLoyaltyProfileBasedPointsChangedNotification

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **profile_integration_id** | **String** |  |  |
| **loyalty_program_id** | **Integer** |  |  |
| **loyalty_program_name** | **String** | The name of the loyalty program. |  |
| **subledger_id** | **String** |  |  |
| **source_of_event** | **String** |  |  |
| **current_tier** | **String** | The name of the customer&#39;s current tier. |  |
| **employee_name** | **String** |  | [optional] |
| **user_id** | **Integer** |  | [optional] |
| **current_points** | **Float** |  |  |
| **actions** | [**Array&lt;IntegrationHubEventPayloadLoyaltyProfileBasedPointsChangedNotificationAction&gt;**](IntegrationHubEventPayloadLoyaltyProfileBasedPointsChangedNotificationAction.md) |  | [optional] |
| **published_at** | **Time** | Timestamp when the event was published. |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::IntegrationHubEventPayloadLoyaltyProfileBasedPointsChangedNotification.new(
  profile_integration_id: null,
  loyalty_program_id: null,
  loyalty_program_name: null,
  subledger_id: null,
  source_of_event: null,
  current_tier: null,
  employee_name: null,
  user_id: null,
  current_points: null,
  actions: null,
  published_at: null
)
```

