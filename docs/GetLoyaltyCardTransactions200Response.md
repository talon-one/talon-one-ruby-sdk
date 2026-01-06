# TalonOne::GetLoyaltyCardTransactions200Response

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **has_more** | **Boolean** |  |  |
| **data** | [**Array&lt;CardLedgerTransactionLogEntryIntegrationAPI&gt;**](CardLedgerTransactionLogEntryIntegrationAPI.md) |  |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::GetLoyaltyCardTransactions200Response.new(
  has_more: true,
  data: null
)
```

