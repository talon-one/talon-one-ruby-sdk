# TalonOne::JoinLoyaltyProgramEffectProps

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **program_id** | **Integer** | The ID of the loyalty program the customer profile is joined to. |  |
| **join_date** | **Time** | The date and time when the customer profile joined the loyalty program. |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::JoinLoyaltyProgramEffectProps.new(
  program_id: 5,
  join_date: 2026-01-02T03:04:05Z
)
```

