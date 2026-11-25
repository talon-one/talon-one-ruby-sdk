# TalonOne::RuleEligibilityFailureDetails

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **failure_code** | **String** | A code identifying why the customer was not eligible for the rule in the current session.  - &#x60;CONDITION_NOT_MET&#x60;: One or more conditions of the rule did not evaluate  to &#x60;true&#x60; for the customer.  - &#x60;EFFECT_FAILED&#x60;: The conditions of the rule were met but one of its effects  could not be applied.  |  |
| **coupon_id** | **Integer** | The ID of the coupon that was being evaluated when the rule failed.  | [optional] |
| **coupon_value** | **String** | The coupon code that was being evaluated when the rule failed.  | [optional] |
| **referral_id** | **Integer** | The ID of the referral that was being evaluated when the rule failed.  | [optional] |
| **referral_value** | **String** | The referral code that was being evaluated when the rule failed.  | [optional] |
| **condition_index** | **Integer** | The index of the condition that caused the rule to fail. | [optional] |
| **effect_index** | **Integer** | The index of the effect that caused the rule to fail. | [optional] |
| **rule_index** | **Integer** | The index of the rule that failed within the ruleset. | [optional] |
| **ruleset_id** | **Integer** | The ID of the ruleset containing the rule that failed. | [optional] |
| **details** | **String** | Additional details about the failure. |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::RuleEligibilityFailureDetails.new(
  failure_code: null,
  coupon_id: 4928,
  coupon_value: null,
  referral_id: null,
  referral_value: null,
  condition_index: null,
  effect_index: null,
  rule_index: 0,
  ruleset_id: 123,
  details: null
)
```

