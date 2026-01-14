# TalonOne::ActivateLoyaltyPointsResponse

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **ledger_entries** | [**Array&lt;LoyaltyLedgerEntry&gt;**](LoyaltyLedgerEntry.md) | Updated ledger entries after activation. | [optional] |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::ActivateLoyaltyPointsResponse.new(
  ledger_entries: null
)
```

