# TalonOne::CreateMCPKey

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **name** | **String** | Name for the MCP key. |  |
| **expiry_date** | **Time** | The date the MCP key expires. |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::CreateMCPKey.new(
  name: My MCP key,
  expiry_date: 2026-08-24T14:00:00Z
)
```

