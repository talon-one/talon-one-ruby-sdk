# TalonOne::NewExperiment

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **is_variant_assignment_external** | **Boolean** | The source of the assignment. - false - The variant assignment is handled internally by Talon.One. - true - The variant assignment is handled externally.  |  |
| **campaign** | [**NewCampaign**](NewCampaign.md) |  |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::NewExperiment.new(
  is_variant_assignment_external: null,
  campaign: null
)
```

