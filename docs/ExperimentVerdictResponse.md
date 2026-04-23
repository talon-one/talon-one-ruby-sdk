# TalonOne::ExperimentVerdictResponse

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **verdict** | [**ExperimentVerdict**](ExperimentVerdict.md) |  |  |
| **generated** | **Time** | Timestamp of the moment when the verdict was generated. |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::ExperimentVerdictResponse.new(
  verdict: null,
  generated: null
)
```

