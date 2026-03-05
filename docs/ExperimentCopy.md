# TalonOne::ExperimentCopy

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **target_application_id** | **Integer** | The ID of the Application to copy the experiment. It is displayed in your Talon.One deployment URL.  |  |
| **experiment** | [**ExperimentCopyExperiment**](ExperimentCopyExperiment.md) |  |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::ExperimentCopy.new(
  target_application_id: null,
  experiment: null
)
```

