# TalonOne::LoyaltyBalancesWithTiers

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **balance** | [**LoyaltyBalanceWithTier**](LoyaltyBalanceWithTier.md) |  | [optional] |
| **subledger_balances** | [**Hash&lt;String, LoyaltyBalanceWithTier&gt;**](LoyaltyBalanceWithTier.md) | Map of the loyalty balances of the subledgers of a ledger. | [optional] |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::LoyaltyBalancesWithTiers.new(
  balance: null,
  subledger_balances: {mysubledger&#x3D;{activePoints&#x3D;286, pendingPoints&#x3D;50, spentPoints&#x3D;150, expiredPoints&#x3D;25, negativePoints&#x3D;0}}
)
```

