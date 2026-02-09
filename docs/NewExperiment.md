# TalonOne::NewExperiment

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **is_variant_assignment_external** | **Boolean** | The source of the assignment. - false - The assignment to the variant is handled internally by the Talon.Oneandled internally by the Talon.One. - true - The assignment to the variant handled externally.  |  |
| **activated** | **Time** | The date and time the experiment was activated.  | [optional] |
| **state** | **String** | A disabled experiment is not evaluated for rules or coupons.  | [optional][default to &#39;disabled&#39;] |
| **campaign** | [**NewCampaign**](NewCampaign.md) |  |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::NewExperiment.new(
  is_variant_assignment_external: null,
  activated: null,
  state: enabled,
  campaign: null
)
```

