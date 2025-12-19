# TalonOne::LoyaltyBalances

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **balance** | [**LoyaltyBalance**](LoyaltyBalance.md) |  | [optional] |
| **subledger_balances** | [**Hash&lt;String, LoyaltyBalance&gt;**](LoyaltyBalance.md) | Map of the loyalty balances of the subledgers of a ledger. | [optional] |

## Example

```ruby
require 'talon_one'

instance = TalonOne::LoyaltyBalances.new(
  balance: null,
  subledger_balances: {mysubledger&#x3D;{activePoints&#x3D;286, pendingPoints&#x3D;50, spentPoints&#x3D;150, expiredPoints&#x3D;25, negativePoints&#x3D;0}}
)
```

