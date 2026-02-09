# TalonOne::Experiment

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** | The internal ID of this entity. |  |
| **created** | **Time** | The time this entity was created. |  |
| **application_id** | **Integer** | The ID of the Application that owns this entity. |  |
| **is_variant_assignment_external** | **Boolean** | The source of the assignment. - false - The assignment to the variant is handled internally by the Talon.Oneandled internally by the Talon.One. - true - The assignment to the variant handled externally.  | [optional] |
| **campaign** | [**Campaign**](Campaign.md) |  | [optional] |
| **activated** | **Time** | The date and time the experiment was activated.  | [optional] |
| **state** | **String** | A disabled experiment is not evaluated for rules or coupons.  | [optional][default to &#39;disabled&#39;] |
| **variants** | [**Array&lt;ExperimentVariant&gt;**](ExperimentVariant.md) |  | [optional] |
| **deletedat** | **Time** | The date and time the experiment was deleted.  | [optional] |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::Experiment.new(
  id: 6,
  created: 2020-06-10T09:05:27.993483Z,
  application_id: 322,
  is_variant_assignment_external: null,
  campaign: null,
  activated: null,
  state: enabled,
  variants: null,
  deletedat: null
)
```

