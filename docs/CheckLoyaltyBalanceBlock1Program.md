# TalonOne::CheckLoyaltyBalanceBlock1Program

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** | The ID of the loyalty program. |  |
| **name** | **String** | The internal name of the loyalty program. |  |
| **title** | **String** | The display name of the loyalty program. |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::CheckLoyaltyBalanceBlock1Program.new(
  id: 10,
  name: MainProgram,
  title: Main Loyalty Program
)
```

