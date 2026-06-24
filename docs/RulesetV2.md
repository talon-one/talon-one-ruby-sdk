# TalonOne::RulesetV2

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** | Internal ID of this entity. |  |
| **created** | **Time** | The time this entity was created. |  |
| **user_id** | **Integer** | The ID of the user that created this ruleset. |  |
| **campaign_id** | **Integer** | The ID of the campaign that owns this entity. | [optional] |
| **template_id** | **Integer** | The ID of the campaign template that owns this entity. | [optional] |
| **activated_at** | **Time** | Timestamp indicating when this ruleset was activated. | [optional] |
| **promotion_rules** | [**Array&lt;PromotionRuleV2&gt;**](PromotionRuleV2.md) | Set of promotion rules. |  |
| **strikethrough_rules** | [**Array&lt;StrikethroughRuleV2&gt;**](StrikethroughRuleV2.md) | Set of strikethrough rules. |  |
| **selectors** | **Array&lt;Hash&lt;String, Object&gt;&gt;** | Variable bindings of type selector. | [optional] |
| **bundles** | **Array&lt;Hash&lt;String, Object&gt;&gt;** | Variable bindings of type bundle. | [optional] |
| **parameters** | **Array&lt;Hash&lt;String, Object&gt;&gt;** | Variable bindings of type template parameter. | [optional] |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::RulesetV2.new(
  id: 6,
  created: null,
  user_id: 385,
  campaign_id: 320,
  template_id: 3,
  activated_at: null,
  promotion_rules: null,
  strikethrough_rules: null,
  selectors: null,
  bundles: null,
  parameters: null
)
```

