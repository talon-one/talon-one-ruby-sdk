# TalonOne::NewInternalAudience

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **name** | **String** | The human-friendly display name for this audience. |  |
| **sandbox** | **Boolean** | Indicates if this is a live or sandbox Application. | [optional] |
| **description** | **String** | A description of the audience. | [optional] |

## Example

```ruby
require 'talon_one'

instance = TalonOne::NewInternalAudience.new(
  name: Travel audience,
  sandbox: true,
  description: Travel audience 18-27
)
```

