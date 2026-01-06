# TalonOne::StrikethroughDebugResponse

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **campaigns_ids** | **Array&lt;Integer&gt;** | The campaign IDs that got fetched for the evaluation process. | [optional] |
| **effects** | [**Array&lt;StrikethroughEffect&gt;**](StrikethroughEffect.md) | The strikethrough effects that are returned from the evaluation process. | [optional] |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::StrikethroughDebugResponse.new(
  campaigns_ids: null,
  effects: null
)
```

