# TalonOne::History

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** | The ID of the price record. |  |
| **observed_at** | **Time** | The date and time from which the price record is effective. |  |
| **context_ids** | **Array&lt;String&gt;** | The identifiers of the relevant context (the sales events, e.g. \&quot;Spring Sale\&quot;, \&quot;Summer Sale\&quot;) at the time from which the price record is effective. Includes the context IDs of any price adjustments and of the campaigns that influenced the final price.  |  |
| **price** | **Float** | Price of the item. |  |
| **metadata** | [**BestPriorPriceMetadata**](BestPriorPriceMetadata.md) |  |  |
| **target** | [**LabelTarget**](LabelTarget.md) |  |  |
| **excluded_at** | **Time** | The date and time when the price record was excluded. | [optional] |
| **exclusion_reason** | **String** | The reason for excluding this price record. | [optional] |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::History.new(
  id: 1,
  observed_at: 2025-11-10T23:00:00Z,
  context_ids: [SpringSale, SummerSale2025],
  price: 99.99,
  metadata: null,
  target: null,
  excluded_at: 2025-11-10T23:00:00Z,
  exclusion_reason: Incorrect contextID value
)
```

