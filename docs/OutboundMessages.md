# TalonOne::OutboundMessages

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **next_cursor** | **String** | Cursor for the next page of results. Omitted when there are no more results. | [optional] |
| **data** | [**Array&lt;OutboundMessage&gt;**](OutboundMessage.md) | List of outbound messages. |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::OutboundMessages.new(
  next_cursor: SmJlNERRMHdyNWFsTmRDZDVYU0c&#x3D;,
  data: null
)
```

