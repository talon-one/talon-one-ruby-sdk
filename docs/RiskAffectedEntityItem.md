# TalonOne::RiskAffectedEntityItem

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **entity_id** | **String** | The integration ID of the affected entity. |  |
| **activity_value** | **Float** | The observed value of the monitored activity metric for this entity. |  |
| **threshold** | **Float** | The anomaly threshold computed for the entity&#39;s Application group. |  |
| **severity_ratio** | **Float** | The ratio of the observed value to the threshold. |  |
| **criticality** | **String** | The critical classification bucket of this entity. |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::RiskAffectedEntityItem.new(
  entity_id: 174165415,
  activity_value: 2898.2,
  threshold: 60,
  severity_ratio: 48.3,
  criticality: critical
)
```

