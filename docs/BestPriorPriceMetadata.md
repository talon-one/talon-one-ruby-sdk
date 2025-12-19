# TalonOne::BestPriorPriceMetadata

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **influencing_campaign_ids** | **Array&lt;Integer&gt;** |  | [optional] |
| **adjustment_reference_id** | **String** | Identifier related to the &#x60;referenceId&#x60; used during a &#x60;ADD_PRICE_ADJUSTMENT&#x60; action  using the [Sync cart item catalog endpoint](https://docs.talon.one/integration-api#tag/Catalogs/operation/syncCatalog). | [optional] |

## Example

```ruby
require 'talon_one'

instance = TalonOne::BestPriorPriceMetadata.new(
  influencing_campaign_ids: null,
  adjustment_reference_id: null
)
```

