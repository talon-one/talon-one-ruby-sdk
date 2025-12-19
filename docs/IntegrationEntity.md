# TalonOne::IntegrationEntity

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **integration_id** | **String** | The integration ID set by your integration layer. |  |
| **created** | **Time** | The time this entity was created. |  |

## Example

```ruby
require 'talon_one'

instance = TalonOne::IntegrationEntity.new(
  integration_id: URNGV8294NV,
  created: 2020-02-07T08:15:22Z
)
```

