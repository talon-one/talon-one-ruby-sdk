# TalonOne::IntegrationUnlockRewardResponse

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **customer_profile** | [**CustomerProfile**](CustomerProfile.md) | The customer profile that unlocked the reward. | [optional] |
| **loyalty** | [**Loyalty**](Loyalty.md) | The loyalty information of the customer profile or loyalty card that unlocked the reward. | [optional] |
| **effects** | [**Array&lt;Effect&gt;**](Effect.md) | The effects generated when evaluating this reward unlock, after the reward&#39;s eligibility conditions are met. See [API effects](https://docs.talon.one/docs/dev/integration-api/api-effects). |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::IntegrationUnlockRewardResponse.new(
  customer_profile: null,
  loyalty: null,
  effects: null
)
```

