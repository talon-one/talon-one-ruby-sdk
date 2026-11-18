# TalonOne::NewRewardBudget

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **metric** | **String** | The customer action that counts towards the budget. | [optional][default to &#39;unlocks&#39;] |
| **scope** | **String** | The type of count that the budget keeps of how many times the reward has  been unlocked.   - &#x60;perReward&#x60;: Counts how many times the reward has been unlocked by all customers. - &#x60;perProfile&#x60;: Counts how many times each customer profile has unlocked the reward.  |  |
| **period** | **String** | The time frame after which the budget count resets to &#x60;0&#x60;. If you select &#x60;overall&#x60;, the budget never resets.  The count resets at the start of each calendar time frame, not on the day the budget was created. For example, a &#x60;monthly&#x60; budget created on 20 October counts the unlocks from 20 to 31 October. On 1 November, the count resets to &#x60;0&#x60;.  |  |
| **limit** | **Integer** | The maximum number of times the reward can be unlocked in the time frame. |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::NewRewardBudget.new(
  metric: unlocks,
  scope: perReward,
  period: monthly,
  limit: 5000
)
```

