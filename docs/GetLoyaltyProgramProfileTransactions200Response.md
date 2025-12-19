# TalonOne::GetLoyaltyProgramProfileTransactions200Response

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **has_more** | **Boolean** |  |  |
| **data** | [**Array&lt;LedgerTransactionLogEntryIntegrationAPI&gt;**](LedgerTransactionLogEntryIntegrationAPI.md) |  |  |

## Example

```ruby
require 'talon_one'

instance = TalonOne::GetLoyaltyProgramProfileTransactions200Response.new(
  has_more: true,
  data: null
)
```

