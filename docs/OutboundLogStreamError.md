# TalonOne::OutboundLogStreamError

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **error** | **String** | Reason the stream ended. |  |
| **id** | **String** | ID of the error. Include it when reporting the error. | [optional] |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::OutboundLogStreamError.new(
  error: internal server error,
  id: 67e55044-10b1-426f-9247-bb680e5fe0c8
)
```

