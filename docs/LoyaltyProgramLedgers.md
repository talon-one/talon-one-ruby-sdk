# TalonOne::LoyaltyProgramLedgers

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** | The internal ID of loyalty program. |  |
| **title** | **String** | Visible name of loyalty program. |  |
| **name** | **String** | Internal name of loyalty program. |  |
| **join_date** | **Time** | The date on which the customer joined the loyalty program in RFC3339.  **Note**: This is in the loyalty program&#39;s time zone.  | [optional] |
| **ledger** | [**LedgerInfo**](LedgerInfo.md) | Information about the main ledger in the loyalty program. |  |
| **sub_ledgers** | [**Hash&lt;String, LedgerInfo&gt;**](LedgerInfo.md) | A map containing information about each loyalty subledger. | [optional] |

## Example

```ruby
require 'talon_one'

instance = TalonOne::LoyaltyProgramLedgers.new(
  id: 5,
  title: My loyalty program,
  name: program1,
  join_date: 2024-04-30T15:04:05Z07:00,
  ledger: null,
  sub_ledgers: null
)
```

