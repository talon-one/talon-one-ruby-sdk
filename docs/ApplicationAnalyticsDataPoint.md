# TalonOne::ApplicationAnalyticsDataPoint

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **start_time** | **Time** | The start of the aggregation time frame in UTC. |  |
| **end_time** | **Time** | The end of the aggregation time frame in UTC. |  |
| **total_revenue** | [**AnalyticsDataPoint**](AnalyticsDataPoint.md) | The total, pre-discount value of all items purchased in a customer session. | [optional] |
| **sessions_count** | [**AnalyticsDataPoint**](AnalyticsDataPoint.md) | The number of all closed sessions. The &#x60;influenced&#x60; value includes only sessions with at least one applied effect. | [optional] |
| **avg_items_per_session** | [**AnalyticsDataPoint**](AnalyticsDataPoint.md) | The number of items from sessions divided by the number of sessions. The &#x60;influenced&#x60; value includes only sessions with at least one applied effect. | [optional] |
| **avg_session_value** | [**AnalyticsDataPoint**](AnalyticsDataPoint.md) | The average customer session value, calculated by dividing the revenue value by the number of sessions. The &#x60;influenced&#x60; value includes only sessions with at least one applied effect. | [optional] |
| **total_discounts** | **Float** | The total value of discounts given for cart items in influenced sessions. | [optional] |
| **coupons_count** | **Float** | The number of times a coupon was successfully redeemed in influenced sessions. | [optional] |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::ApplicationAnalyticsDataPoint.new(
  start_time: 2024-02-01T00:00:00Z,
  end_time: 2024-02-01T23:59:99Z,
  total_revenue: null,
  sessions_count: null,
  avg_items_per_session: null,
  avg_session_value: null,
  total_discounts: 10,
  coupons_count: 12
)
```

