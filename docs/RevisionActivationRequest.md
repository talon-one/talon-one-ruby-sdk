# TalonOne::RevisionActivationRequest

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **user_ids** | **Array&lt;Integer&gt;** | The list of IDs of the users who will receive the activation request. |  |
| **activate_at** | **Time** | Time when the revisions are finalized after the &#x60;activate_revision&#x60; operation. The current time is used when left blank.  **Note:** It must be an RFC3339 timestamp string.  | [optional] |

## Example

```ruby
require 'talon_one'

instance = TalonOne::RevisionActivationRequest.new(
  user_ids: [1,2,3],
  activate_at: 2025-10-01T16:00:05Z07:00
)
```

