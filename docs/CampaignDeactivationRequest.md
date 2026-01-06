# TalonOne::CampaignDeactivationRequest

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **user_ids** | **Array&lt;Integer&gt;** | The list of IDs of the users receiving the deactivation request emails. |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::CampaignDeactivationRequest.new(
  user_ids: [1,2,3]
)
```

