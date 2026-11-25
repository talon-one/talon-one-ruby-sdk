# TalonOne::ExportJob

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **type** | [**ExportJobType**](ExportJobType.md) |  |  |
| **args** | **Hash&lt;String, Object&gt;** | Arguments for the exporter. Their structure depends on &#x60;type&#x60; and is validated by the service. |  |
| **destination** | [**Array&lt;ExportJobDestination&gt;**](ExportJobDestination.md) | Destinations for the export job. |  |
| **cron_schedule** | **String** | Schedule in standard 5-field cron format. |  |
| **timezone** | **String** | A string containing an IANA timezone descriptor. | [optional][default to &#39;UTC&#39;] |
| **enabled** | **Boolean** | Whether the export job is enabled. | [optional][default to false] |
| **allow_concurrent_runs** | **Boolean** | Whether to allow concurrent runs of the job. | [optional][default to false] |
| **override_filename** | **String** | Filename that replaces the generated export filename, without extension. | [optional] |
| **id** | **Integer** | The internal ID of this entity. |  |
| **account_id** | **Integer** | The ID of the account that owns this entity. |  |
| **status** | [**ExportJobStatus**](ExportJobStatus.md) |  | [default to &#39;idle&#39;] |
| **created** | **Time** | The time this entity was created. |  |
| **modified** | **Time** | The time this entity was modified. | [optional] |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::ExportJob.new(
  type: null,
  args: {loyaltyProgramID&#x3D;6},
  destination: [{type&#x3D;gcs, bucket&#x3D;acme-exports, compression&#x3D;gzip}],
  cron_schedule: 0 3 * * *,
  timezone: Europe/Berlin,
  enabled: true,
  allow_concurrent_runs: null,
  override_filename: acme-exports,
  id: 6,
  account_id: 3886,
  status: null,
  created: 2020-06-10T09:05:27.993483Z,
  modified: 2020-06-10T09:05:27.993483Z
)
```

