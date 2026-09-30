# TalonOne::GetLoyaltyProgramProfileLedgerTransactions200Response

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **has_more** | **Boolean** |  |  |
| **data** | [**Array&lt;LedgerTransactionLogEntryManagementAPI&gt;**](LedgerTransactionLogEntryManagementAPI.md) |  |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::GetLoyaltyProgramProfileLedgerTransactions200Response.new(
  has_more: true,
  data: null
)
```

