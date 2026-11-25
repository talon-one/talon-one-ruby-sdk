# TalonOne::ExportJobDestination

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **type** | **String** | Destination type can be Google Cloud Storage (gcs) or file. |  |
| **compression** | **String** | Compression applied to the exported file. | [optional][default to &#39;none&#39;] |
| **path** | **String** | Directory on the exporter host where the file is written. Required for file destinations; must be omitted for gcs. | [optional] |
| **bucket** | **String** | GCS bucket name for storage. Absent for file. | [optional] |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::ExportJobDestination.new(
  type: gcs,
  compression: gzip,
  path: exports/loyalty,
  bucket: acme-exports
)
```

