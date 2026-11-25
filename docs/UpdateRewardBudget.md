# TalonOne::UpdateRewardBudget

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **limit** | **Integer** | The new limit for the maximum number of times the reward can be unlocked in the given period. |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::UpdateRewardBudget.new(
  limit: 8000
)
```

