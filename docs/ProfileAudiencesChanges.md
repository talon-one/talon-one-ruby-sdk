# TalonOne::ProfileAudiencesChanges

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **adds** | **Array&lt;Integer&gt;** | The IDs of the audiences for the customer to join. |  |
| **deletes** | **Array&lt;Integer&gt;** | The IDs of the audiences for the customer to leave. |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::ProfileAudiencesChanges.new(
  adds: [2, 4],
  deletes: [7]
)
```

