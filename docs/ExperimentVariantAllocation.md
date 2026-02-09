# TalonOne::ExperimentVariantAllocation

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **experiment_id** | **Integer** | The ID of the experiment. |  |
| **variant_id** | **Integer** | The ID of the variant to be allocated. |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::ExperimentVariantAllocation.new(
  experiment_id: 1,
  variant_id: 2
)
```

