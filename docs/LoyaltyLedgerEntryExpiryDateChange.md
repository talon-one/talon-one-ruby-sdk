# TalonOne::LoyaltyLedgerEntryExpiryDateChange

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **transaction_uuid** | **String** | The identifier of the transaction affected by the extension or update. |  |
| **previous_expiry_date** | **Time** | Expiry date of the transactions before applying the extension or update. | [optional] |
| **new_expiry_date** | **Time** | Expiry date of the transaction after applying the extension or update. |  |

## Example

```ruby
require 'talon_one'

instance = TalonOne::LoyaltyLedgerEntryExpiryDateChange.new(
  transaction_uuid: null,
  previous_expiry_date: null,
  new_expiry_date: null
)
```

