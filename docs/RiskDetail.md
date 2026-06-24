# TalonOne::RiskDetail

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** | The internal ID of this entity. |  |
| **created** | **Time** | The time this entity was created. |  |
| **notification_id** | **Integer** | The ID of the risk notification rule that flagged this risk. |  |
| **run_date** | **Date** | The date of the ML pipeline run that detected this risk. |  |
| **group_key** | **String** | The Application group this risk was detected in. Contains the Application ID, or &#x60;__GLOBAL__&#x60; for metrics that are not grouped by Application.  |  |
| **application_id** | **Integer** | The ID of the Application this risk belongs to. Absent for global metrics. | [optional] |
| **status** | **String** | The triage lifecycle status of this risk. |  |
| **criticality** | **String** | The critical classification bucket of this risk. |  |
| **entity** | **String** | The entity type the risk was detected in. |  |
| **activity** | **String** | The activity metric the risk was detected in. |  |
| **time_frame** | **String** | The rolling time window of the risk evaluation. |  |
| **reported_date** | **Time** | The time the ML service reported this risk. |  |
| **affected_entity_count** | **Integer** | The total number of entities affected by this risk. |  |
| **description** | **String** | Human-readable description of the detected anomaly. | [optional] |
| **modified** | **Time** | Timestamp of the most recent update. |  |
| **affected_entities** | [**Array&lt;RiskAffectedEntityItem&gt;**](RiskAffectedEntityItem.md) | The affected entities with the highest severity ratios, in descending order. |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::RiskDetail.new(
  id: 6,
  created: 2020-06-10T09:05:27.993483Z,
  notification_id: 3,
  run_date: 2026-06-05,
  group_key: 7,
  application_id: 7,
  status: active,
  criticality: critical,
  entity: customer_profile,
  activity: discounted_amount,
  time_frame: 1_week,
  reported_date: 2026-06-05T06:26:13.698884Z,
  affected_entity_count: 4437,
  description: Unusual discount usage detected for 4437 customer profiles.,
  modified: 2026-06-05T06:26:13.698884Z,
  affected_entities: null
)
```

