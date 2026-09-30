# TalonOne::OutboundLogs

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **next_cursor** | **String** | Cursor for the next page of results. Omitted when there are no more results. | [optional] |
| **data** | [**Array&lt;OutboundLog&gt;**](OutboundLog.md) | List of outbound logs. |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::OutboundLogs.new(
  next_cursor: SmJlNERRMHdyNWFsTmRDZDVYU0c&#x3D;,
  data: null
)
```

