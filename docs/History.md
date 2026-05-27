# TalonOne::History

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** | The ID of the historical price. |  |
| **observed_at** | **Time** | The date and time when the price was observed. |  |
| **context_ids** | **Array&lt;String&gt;** | The identifiers of the relevant context at the time the price was observed. Includes the context IDs of any price adjustments and of the campaigns that influenced the final price.  |  |
| **context_id** | **String** | This property is **deprecated**. Use &#x60;contextIds&#x60; instead. Defaults to an empty string.  | [optional][default to &#39;&#39;] |
| **price** | **Float** | Price of the item. |  |
| **metadata** | [**BestPriorPriceMetadata**](BestPriorPriceMetadata.md) |  |  |
| **target** | **Object** |  |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::History.new(
  id: 1,
  observed_at: 2025-11-10T23:00:00Z,
  context_ids: [SpringSale, SummerSale2025],
  context_id: ,
  price: 99.99,
  metadata: null,
  target: null
)
```

