# TalonOne::NewExportJob

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

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::NewExportJob.new(
  type: null,
  args: {loyaltyProgramID&#x3D;6},
  destination: [{type&#x3D;gcs, bucket&#x3D;acme-exports, compression&#x3D;gzip}],
  cron_schedule: 0 3 * * *,
  timezone: Europe/Berlin,
  enabled: true,
  allow_concurrent_runs: null,
  override_filename: acme-exports
)
```

