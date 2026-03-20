# TalonOne::IntegrationHubEventPayloadLoyaltyProfileBasedPointsChangedNotificationAction

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **amount** | **Float** |  |  |
| **reason** | **String** |  | [optional] |
| **operation** | **String** |  |  |
| **start_date** | **Time** |  | [optional] |
| **expiry_date** | **Time** |  | [optional] |
| **transaction_uuid** | **String** | The identifier of the transaction in the loyalty ledger. |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::IntegrationHubEventPayloadLoyaltyProfileBasedPointsChangedNotificationAction.new(
  amount: null,
  reason: null,
  operation: null,
  start_date: null,
  expiry_date: null,
  transaction_uuid: null
)
```

