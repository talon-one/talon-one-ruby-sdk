# TalonOne::RewardBudgetWithLimitCounter

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** | The internal ID of this entity. |  |
| **created** | **Time** | The time this entity was created. |  |
| **reward_id** | **Integer** | The ID of the reward this budget applies to. |  |
| **metric** | **String** | The customer action that counts towards the budget. |  |
| **scope** | **String** | The type of count that the budget keeps of how many times the reward has  been unlocked.  - &#x60;perReward&#x60;: Counts how many times the reward has been unlocked by all customers. - &#x60;perProfile&#x60;: Counts how many times each customer profile has unlocked the reward.  |  |
| **period** | **String** | The time frame after which the budget count resets to &#x60;0&#x60;. If you select &#x60;overall&#x60;, the budget never resets.  The count resets at the start of each calendar time frame, not on the day the budget was created. For example, a &#x60;monthly&#x60; budget created on 20 October counts each time the reward is unlocked from 20 to 31 October. On 1 November,  resets to &#x60;0&#x60;.  |  |
| **limit** | **Integer** | The maximum number of times the reward can be unlocked in the time frame. |  |
| **limit_counter** | [**Array&lt;RewardBudgetLimitCounter&gt;**](RewardBudgetLimitCounter.md) | The count of times the reward has been unlocked in the current period, and how many times it can still be unlocked before the limit is reached. It is only returned for budgets with the &#x60;perReward&#x60; scope, because every customer profile has their own count in a &#x60;perProfile&#x60; budget.  The count is stored for each Application. A reward is connected to one Application, so the list always has exactly one item.  | [optional] |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::RewardBudgetWithLimitCounter.new(
  id: 6,
  created: 2020-06-10T09:05:27.993483Z,
  reward_id: 34,
  metric: unlocks,
  scope: perReward,
  period: monthly,
  limit: 5000,
  limit_counter: null
)
```

