# TalonOne::RewardBudgetLimitCounter

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **counter** | **Integer** | The number of times the reward has been unlocked in the current period. It is &#x60;0&#x60; if the reward has not been unlocked by any profile yet. |  |
| **remaining** | **Integer** | The number of times the reward can still be unlocked. It is never negative. |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::RewardBudgetLimitCounter.new(
  counter: 120,
  remaining: 4880
)
```

