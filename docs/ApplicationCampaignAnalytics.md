# TalonOne::ApplicationCampaignAnalytics

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **start_time** | **Time** | The start of the aggregation time frame in UTC. |  |
| **end_time** | **Time** | The end of the aggregation time frame in UTC. |  |
| **campaign_id** | **Integer** | The ID of the campaign. |  |
| **campaign_name** | **String** | The name of the campaign. |  |
| **campaign_tags** | **Array&lt;String&gt;** | A list of tags for the campaign. |  |
| **campaign_state** | **String** | The state of the campaign.  **Note:** A disabled or archived campaign is not evaluated for rules or coupons.  |  |
| **total_revenue** | [**AnalyticsDataPointWithTrendAndInfluencedRate**](AnalyticsDataPointWithTrendAndInfluencedRate.md) | The total, pre-discount value of all items purchased in a customer session. | [optional] |
| **sessions_count** | [**AnalyticsDataPointWithTrendAndInfluencedRate**](AnalyticsDataPointWithTrendAndInfluencedRate.md) | The number of all closed sessions. The &#x60;influenced&#x60; value includes only sessions with at least one applied effect. | [optional] |
| **avg_items_per_session** | [**AnalyticsDataPointWithTrendAndUplift**](AnalyticsDataPointWithTrendAndUplift.md) | The number of items from sessions divided by the number of sessions. The &#x60;influenced&#x60; value includes only sessions with at least one applied effect. | [optional] |
| **avg_session_value** | [**AnalyticsDataPointWithTrendAndUplift**](AnalyticsDataPointWithTrendAndUplift.md) | The average customer session value, calculated by dividing the revenue value by the number of sessions. The &#x60;influenced&#x60; value includes only sessions with at least one applied effect. | [optional] |
| **total_discounts** | [**AnalyticsDataPointWithTrend**](AnalyticsDataPointWithTrend.md) | The total value of discounts given for cart items in influenced sessions. | [optional] |
| **coupons_count** | [**AnalyticsDataPointWithTrend**](AnalyticsDataPointWithTrend.md) | The number of times a coupon was successfully redeemed in influenced sessions. | [optional] |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::ApplicationCampaignAnalytics.new(
  start_time: 2024-02-01T00:00:00Z,
  end_time: 2024-02-01T23:59:99Z,
  campaign_id: 1,
  campaign_name: Summer promotions,
  campaign_tags: [summer],
  campaign_state: running,
  total_revenue: null,
  sessions_count: null,
  avg_items_per_session: null,
  avg_session_value: null,
  total_discounts: null,
  coupons_count: null
)
```

