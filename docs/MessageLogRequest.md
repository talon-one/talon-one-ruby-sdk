# TalonOne::MessageLogRequest

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **created_at** | **Time** | Timestamp when the request was made. |  |
| **request** | **String** | Raw request data. |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::MessageLogRequest.new(
  created_at: 2021-07-20T21:59:00Z,
  request: SGVsbG8sIHdvcmxkIQ&#x3D;&#x3D;
)
```

