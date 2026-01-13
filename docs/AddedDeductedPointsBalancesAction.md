# TalonOne::AddedDeductedPointsBalancesAction

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **amount** | **Float** | The amount of added or deducted loyalty points. |  |
| **reason** | **String** | The reason for the points addition or deduction. |  |
| **operation** | **String** | The action (addition or deduction) made with loyalty points. |  |
| **start_date** | **Time** | The start date for loyalty points. | [optional] |
| **expiry_date** | **Time** | The expiration date for loyalty points. | [optional] |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::AddedDeductedPointsBalancesAction.new(
  amount: 10.99,
  reason: Compensation,
  operation: null,
  start_date: 2023-01-24T14:15:22Z,
  expiry_date: 2024-01-24T14:15:22Z
)
```

