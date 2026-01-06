# TalonOne::GetLoyaltyCardPoints200Response

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **has_more** | **Boolean** |  |  |
| **data** | [**Array&lt;CardLedgerPointsEntryIntegrationAPI&gt;**](CardLedgerPointsEntryIntegrationAPI.md) |  |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::GetLoyaltyCardPoints200Response.new(
  has_more: true,
  data: null
)
```

