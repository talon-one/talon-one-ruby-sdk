# TalonOne::ExportJobLog

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** | The internal ID of this entity. |  |
| **export_job_id** | **Integer** | The internal ID of the connected export job. |  |
| **type** | [**ExportJobType**](ExportJobType.md) |  |  |
| **result** | [**ExportJobLogResult**](ExportJobLogResult.md) |  |  |
| **filename** | **String** | Name of the exported file, without extension. |  |
| **log** | **String** | The log text. |  |
| **started_at** | **Time** | Time when the export job run started. |  |
| **finished_at** | **Time** | Time when the export job run finished. | [optional] |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::ExportJobLog.new(
  id: 6,
  export_job_id: 6,
  type: null,
  result: null,
  filename: 6_loyalty_ledger_entries_2026-11-10,
  log: 1 rows exported to 1 destinations,
  started_at: 2020-06-10T09:05:27.993483Z,
  finished_at: 2020-06-10T09:05:27.993483Z
)
```

