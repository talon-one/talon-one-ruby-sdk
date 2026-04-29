# TalonOne::RuleEligibility

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **passed** | **Boolean** | Indicates whether the customer was eligible for the rule in the current session, based on whether all of the rule&#39;s conditions were met. |  |
| **coupon_code** | **String** | The coupon code used to check a customer&#39;s eligibility for the rule in the current session, if applicable. | [optional] |
| **details** | [**RuleEligibilityFailureDetails**](RuleEligibilityFailureDetails.md) | The details about why the customer was not eligible for the rule in the current session. Only returned when &#x60;passed&#x60; is &#x60;false&#x60;. | [optional] |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::RuleEligibility.new(
  passed: true,
  coupon_code: null,
  details: null
)
```

