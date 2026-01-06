# TalonOne::AnalyticsDataPointWithTrendAndUplift

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **value** | **Float** |  |  |
| **uplift** | **Float** |  |  |
| **trend** | **Float** |  |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::AnalyticsDataPointWithTrendAndUplift.new(
  value: 12,
  uplift: 3.25,
  trend: 3.25
)
```

