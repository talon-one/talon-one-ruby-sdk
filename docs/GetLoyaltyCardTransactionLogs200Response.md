# TalonOne::GetLoyaltyCardTransactionLogs200Response

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **has_more** | **Boolean** | true means there is more data in the source collection to request.. |  |
| **data** | [**Array&lt;CardLedgerTransactionLogEntry&gt;**](CardLedgerTransactionLogEntry.md) | List of loyalty card transaction logs. |  |

## Example

```ruby
require 'talon_one'

instance = TalonOne::GetLoyaltyCardTransactionLogs200Response.new(
  has_more: true,
  data: null
)
```

