# TalonOne::CampaignEligibility

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** | Unique ID of Campaign. |  |
| **application_id** | **Integer** | The ID of the Application that owns this entity. |  |
| **name** | **String** | The name of the campaign. |  |
| **description** | **String** | A detailed description of the campaign. | [optional] |
| **start_time** | **Time** | Timestamp when the campaign will become active. | [optional] |
| **end_time** | **Time** | Timestamp when the campaign will become inactive. | [optional] |
| **attributes** | **Object** | Arbitrary properties associated with this campaign. | [optional] |
| **state** | **String** | The state of the campaign.  | [default to &#39;enabled&#39;] |
| **tags** | **Array&lt;String&gt;** | A list of tags for the campaign. |  |
| **features** | **Array&lt;String&gt;** | The features enabled in this campaign. |  |
| **rules** | [**Array&lt;RuleMetadata&gt;**](RuleMetadata.md) | A list of rules containing customer-facing details of the rewards defined in the campaign. | [optional] |
| **eligibility** | [**Array&lt;CampaignEligibilityDetails&gt;**](CampaignEligibilityDetails.md) | The customer&#39;s eligibility for each campaign in the current customer session. |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::CampaignEligibility.new(
  id: 4,
  application_id: 322,
  name: Summer promotions,
  description: Campaign for all summer 2021 promotions,
  start_time: 2021-07-20T22:00:00Z,
  end_time: 2021-09-22T22:00:00Z,
  attributes: null,
  state: enabled,
  tags: [summer],
  features: [coupons, referrals],
  rules: null,
  eligibility: null
)
```

