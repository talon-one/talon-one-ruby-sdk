# TalonOne::LoyaltyLedger

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **ledger** | [**LoyaltySubLedger**](LoyaltySubLedger.md) | The balance of the main ledger in the loyalty program. |  |
| **sub_ledgers** | [**Hash&lt;String, LoyaltySubLedger&gt;**](LoyaltySubLedger.md) | A map containing a list of all loyalty subledger balances. | [optional] |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::LoyaltyLedger.new(
  ledger: null,
  sub_ledgers: {mysubledger&#x3D;{total&#x3D;0, totalActivePoints&#x3D;286, totalPendingPoints&#x3D;50, totalSpentPoints&#x3D;150, totalExpiredPoints&#x3D;25, totalNegativePoints&#x3D;0}}
)
```

