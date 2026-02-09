# TalonOne::ExperimentResults

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **variants** | [**Array&lt;ExperimentVariantResult&gt;**](ExperimentVariantResult.md) |  | [optional] |
| **confidence** | [**ExperimentVariantResultConfidence**](ExperimentVariantResultConfidence.md) |  |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::ExperimentResults.new(
  variants: null,
  confidence: null
)
```

