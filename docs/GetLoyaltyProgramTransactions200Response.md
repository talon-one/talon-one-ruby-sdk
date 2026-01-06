# TalonOne::GetLoyaltyProgramTransactions200Response

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **has_more** | **Boolean** |  |  |
| **data** | [**Array&lt;LoyaltyProgramTransaction&gt;**](LoyaltyProgramTransaction.md) |  |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::GetLoyaltyProgramTransactions200Response.new(
  has_more: true,
  data: null
)
```

