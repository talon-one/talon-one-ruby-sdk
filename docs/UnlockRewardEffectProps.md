# TalonOne::UnlockRewardEffectProps

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **integration_id** | **String** | The integration ID assigned to the customer reward unlock. |  |
| **reward_id** | **Integer** | The internal ID of the reward that was unlocked. |  |
| **application_id** | **Integer** | The internal ID of the application the reward belongs to. |  |
| **profile_integration_id** | **String** | The integration ID of the customer profile that unlocked the reward. |  |
| **unlocked_at** | **Time** | The time the reward was unlocked. |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::UnlockRewardEffectProps.new(
  integration_id: reward-unlock-123,
  reward_id: 5,
  application_id: 1,
  profile_integration_id: customer1,
  unlocked_at: 2024-05-29T15:04:05Z
)
```

