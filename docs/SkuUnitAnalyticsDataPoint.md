# TalonOne::SkuUnitAnalyticsDataPoint

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **start_time** | **Time** | The start of the aggregation time frame in UTC. |  |
| **end_time** | **Time** | The end of the aggregation time frame in UTC. |  |
| **units_sold** | [**AnalyticsDataPointWithTrend**](AnalyticsDataPointWithTrend.md) | The number of times the product or SKU was purchased. |  |
| **sku** | **String** | The SKU linked to the application. |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::SkuUnitAnalyticsDataPoint.new(
  start_time: 2024-02-01T00:00:00Z,
  end_time: 2024-02-01T23:59:99Z,
  units_sold: null,
  sku: SKU-123
)
```

