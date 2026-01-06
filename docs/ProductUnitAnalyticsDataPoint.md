# TalonOne::ProductUnitAnalyticsDataPoint

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **start_time** | **Time** | The start of the aggregation time frame in UTC. |  |
| **end_time** | **Time** | The end of the aggregation time frame in UTC. |  |
| **units_sold** | [**AnalyticsDataPointWithTrend**](AnalyticsDataPointWithTrend.md) | The number of times the product or SKU was purchased. |  |
| **product_id** | **Integer** | The ID of the product. |  |
| **product_name** | **String** | The name of the product. |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::ProductUnitAnalyticsDataPoint.new(
  start_time: 2024-02-01T00:00:00Z,
  end_time: 2024-02-01T23:59:99Z,
  units_sold: null,
  product_id: 1,
  product_name: MyProduct
)
```

