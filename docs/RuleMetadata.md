# TalonOne::RuleMetadata

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **title** | **String** | A short description of the rule. |  |
| **display_name** | **String** | A customer-facing name used to identify the reward defined within the rule. | [optional] |
| **display_description** | **String** | A customer-facing description of the reward defined in the rule.   For example, this property can contain details about eligibility requirements, reward timelines, or terms and conditions.  | [optional] |
| **related_data** | **String** | Data related to the reward, such as a vendor name, an image URL, or a content management system (CMS) ID.  | [optional] |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::RuleMetadata.new(
  title: Give discount via coupon,
  display_name: 20% off all shoes!,
  display_description: Get a 20% discount on all shoes during Thanksgiving! Offer valid till Dec 5 only.,
  related_data: https://example.com/discounts/20-off-shoes.png
)
```

