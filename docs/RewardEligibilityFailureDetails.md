# TalonOne::RewardEligibilityFailureDetails

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **failure_code** | **String** | A code identifying why the customer is not eligible for the reward. |  |
| **condition_index** | **Integer** | The index of the eligibility condition that the customer did not meet. | [optional] |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::RewardEligibilityFailureDetails.new(
  failure_code: CONDITION_NOT_MET,
  condition_index: 0
)
```

