# TalonOne::UpdateReward

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **name** | **String** | The name of the reward. |  |
| **description** | **String** | A description of the reward. | [optional] |
| **status** | **String** | The status of the reward. |  |
| **eligibility_conditions** | [**Rule**](Rule.md) | An optional rule that manages who can see this reward. If not specified, the reward is visible to all customers.  **Note:** Only the &#x60;condition&#x60; field is evaluated within this rule. The &#x60;effects&#x60; field must be an empty array, and &#x60;bindings&#x60; are not supported.  | [optional] |
| **rule** | [**Rule**](Rule.md) | Rule to apply.  **Note**: The &#x60;bindings&#x60; field inside the rule must not be used in this endpoint. All bindings should be defined at the reward level via the top-level &#x60;bindings&#x60; field.  | [optional] |
| **bindings** | [**Array&lt;Binding&gt;**](Binding.md) | A list of named variables created before the reward&#39;s rules are evaluated.  Each binding pairs a name with a talang expression. The expression is evaluated once  and its result is available by name in any rule condition or effect. Bindings must be defined outside of individual rules. | [optional] |
| **points_required** | [**Array&lt;RewardPointsRequired&gt;**](RewardPointsRequired.md) | The loyalty points required to activate the reward. Each object defines the specific loyalty program and subledger from which points are deducted when activating the reward.  **Note:** - Objects with an &#x60;id&#x60; are updated. - Objects without an &#x60;id&#x60; are created. - Existing objects omitted from the payload are deleted.  | [optional] |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::UpdateReward.new(
  name: Free Coffee,
  description: This reward gets you one free coffee.,
  status: active,
  eligibility_conditions: null,
  rule: null,
  bindings: [],
  points_required: null
)
```

