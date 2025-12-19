# TalonOne::AnalyticsSKU

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** | The ID of the SKU linked to the Application. |  |
| **sku** | **String** | The SKU linked to the Application. |  |
| **last_updated** | **Time** | Values in UTC for the date the SKU linked to the product was last updated. | [optional] |
| **catalog_id** | **Integer** | The ID of the catalog that contains the SKU. | [optional] |
| **product_id** | **Integer** | The ID of the product that the SKU belongs to. | [optional] |
| **units_sold** | [**AnalyticsDataPointWithTrend**](AnalyticsDataPointWithTrend.md) | The number of times the product or SKU was purchased. | [optional] |

## Example

```ruby
require 'talon_one'

instance = TalonOne::AnalyticsSKU.new(
  id: 1,
  sku: SKU-123,
  last_updated: 2024-02-01T00:00:00Z,
  catalog_id: 1,
  product_id: 1,
  units_sold: null
)
```

