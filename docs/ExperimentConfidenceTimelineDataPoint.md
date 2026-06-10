# TalonOne::ExperimentConfidenceTimelineDataPoint

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **date** | **Time** | The date-time this data point represents. |  |
| **confidence** | [**ExperimentVariantResultConfidence**](ExperimentVariantResultConfidence.md) |  |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::ExperimentConfidenceTimelineDataPoint.new(
  date: 2024-01-15T00:00:00+07:00,
  confidence: null
)
```

