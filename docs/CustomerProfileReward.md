# TalonOne::CustomerProfileReward

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** | The ID of the customer reward instance. A customer profile can have multiple instances of the same reward. |  |
| **reward_id** | **Integer** | The ID of the reward this instance belongs to. |  |
| **reward_name** | **String** | The name of the reward. |  |
| **status** | **String** | The status of the customer reward: - &#x60;unlocked&#x60;: The reward is available for use. - &#x60;used&#x60;: The reward has been used.  |  |
| **unlocked_at** | **Time** | The date and time when the reward was unlocked. |  |
| **unlocked_by_integration_id** | **String** | The integration ID of the customer profile that unlocked the reward.   For rewards unlocked with a loyalty card, this can be any customer profile  linked to that loyalty card.  | [optional] |
| **used_at** | **Time** | The date and time when the reward was used. | [optional] |
| **used_by_integration_id** | **String** | The integration ID of the customer profile that used the reward.   For rewards unlocked with a loyalty card, this can be any customer profile  linked to that loyalty card.   Only returned when the reward has been used.  | [optional] |
| **loyalty_program_id** | **Integer** | The ID of the loyalty program that the loyalty card belongs to. Only returned for rewards unlocked with a loyalty card. | [optional] |
| **loyalty_card_identifier** | **String** | The identifier of the loyalty card that the reward was unlocked with. Only returned for rewards unlocked with a loyalty card. | [optional] |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::CustomerProfileReward.new(
  id: 6,
  reward_id: 12,
  reward_name: Free coffee,
  status: unlocked,
  unlocked_at: 2026-07-01T09:00:00Z,
  unlocked_by_integration_id: customer2839,
  used_at: 2026-07-02T10:30:00Z,
  used_by_integration_id: customer2840,
  loyalty_program_id: 9,
  loyalty_card_identifier: summer-loyalty-card-0543
)
```

