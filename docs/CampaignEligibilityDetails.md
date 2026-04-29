# TalonOne::CampaignEligibilityDetails

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **passed** | **Boolean** | Indicates whether the customer was eligible for the campaign in the current session. |  |
| **coupon_code** | **String** | The coupon code used to check a customer&#39;s eligibility for the campaign in the current session, if applicable. | [optional] |
| **details** | [**CampaignEligibilityFailureDetails**](CampaignEligibilityFailureDetails.md) | The details about why the customer was not eligible for the campaign in the current session. Only returned when &#x60;passed&#x60; is &#x60;false&#x60;. | [optional] |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::CampaignEligibilityDetails.new(
  passed: null,
  coupon_code: null,
  details: null
)
```

