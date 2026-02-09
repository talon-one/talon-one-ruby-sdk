# TalonOne::UpdateExperiment

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **is_variant_assignment_external** | **Boolean** | The source of the assignment. - false - The assignment to the variant is handled internally by the Talon.Oneandled internally by the Talon.One. - true - The assignment to the variant handled externally.        |  |
| **campaign** | [**UpdateCampaign**](UpdateCampaign.md) |  |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::UpdateExperiment.new(
  is_variant_assignment_external: null,
  campaign: null
)
```

