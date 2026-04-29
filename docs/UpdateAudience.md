# TalonOne::UpdateAudience

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **name** | **String** | The human-friendly display name for this audience. |  |
| **subscribed_applications_ids** | **Array&lt;Integer&gt;** | A list of the IDs of the Applications that are connected to this audience. | [optional] |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::UpdateAudience.new(
  name: Travel audience,
  subscribed_applications_ids: [3, 13]
)
```

