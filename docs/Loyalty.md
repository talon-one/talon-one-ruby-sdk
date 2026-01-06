# TalonOne::Loyalty

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **cards** | [**Array&lt;LoyaltyCard&gt;**](LoyaltyCard.md) | Displays information about the balances of the loyalty cards. | [optional] |
| **programs** | [**Hash&lt;String, LoyaltyProgramLedgers&gt;**](LoyaltyProgramLedgers.md) | Displays information about point balances in profile-based programs. |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::Loyalty.new(
  cards: null,
  programs: null
)
```

