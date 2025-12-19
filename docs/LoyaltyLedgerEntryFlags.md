# TalonOne::LoyaltyLedgerEntryFlags

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **creates_negative_balance** | **Boolean** | Set to true if the entry creates negative balance. | [optional] |

## Example

```ruby
require 'talon_one'

instance = TalonOne::LoyaltyLedgerEntryFlags.new(
  creates_negative_balance: null
)
```

