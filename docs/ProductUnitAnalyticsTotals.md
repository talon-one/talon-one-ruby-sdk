# TalonOne::ProductUnitAnalyticsTotals

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **units_sold** | [**AnalyticsDataPointWithTrend**](AnalyticsDataPointWithTrend.md) | The number of times the product or SKU was purchased. | [optional] |

## Example

```ruby
require 'talon_one'

instance = TalonOne::ProductUnitAnalyticsTotals.new(
  units_sold: null
)
```

