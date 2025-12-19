# TalonOne::CampaignActivationRequest

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **user_ids** | **Array&lt;Integer&gt;** | The list of IDs of the users who will receive the activation request. |  |

## Example

```ruby
require 'talon_one'

instance = TalonOne::CampaignActivationRequest.new(
  user_ids: [1, 2, 3]
)
```

