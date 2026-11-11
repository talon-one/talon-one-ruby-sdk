# TalonOne::OutboundLogs

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **next_cursor** | **String** | Cursor for the next page of results. Omitted when there are no more results. | [optional] |
| **data** | [**Array&lt;OutboundLogsDataInner&gt;**](OutboundLogsDataInner.md) | List of outbound logs. When an error ends the response, an &#x60;OutboundLogStreamError&#x60; is the last item and the response is incomplete. |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::OutboundLogs.new(
  next_cursor: SmJlNERRMHdyNWFsTmRDZDVYU0c&#x3D;,
  data: null
)
```

