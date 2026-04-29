# TalonOne::UpdateReward

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **name** | **String** | The name of the reward. |  |
| **description** | **String** | A description of the reward. | [optional] |
| **status** | **String** | The status of the reward. |  |
| **rule** | [**Array&lt;Rule&gt;**](Rule.md) | Rule to apply.  **Note**: The &#x60;bindings&#x60; field inside the rule must not be used in this endpoint. All bindings should be defined at the reward level via the top-level &#x60;bindings&#x60; field.  | [optional] |
| **bindings** | [**Array&lt;Binding&gt;**](Binding.md) | A list of named variables created before the reward&#39;s rules are evaluated.  Each binding pairs a name with a talang expression. The expression is evaluated once  and its result is available by name in any rule condition or effect. Bindings must be defined outside of individual rules. | [optional] |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::UpdateReward.new(
  name: Free Coffee,
  description: This reward gets you one free coffee.,
  status: active,
  rule: null,
  bindings: []
)
```

