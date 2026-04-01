# TalonOne::ExperimentResult

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **variants** | [**Array&lt;ExperimentVariantResult&gt;**](ExperimentVariantResult.md) |  |  |
| **confidence** | [**ExperimentVariantResultConfidence**](ExperimentVariantResultConfidence.md) |  |  |
| **experiment_id** | **Integer** |  |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::ExperimentResult.new(
  variants: null,
  confidence: null,
  experiment_id: 1
)
```

