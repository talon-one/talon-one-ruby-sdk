# TalonOne::GetAdditionalCosts200Response

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **total_result_size** | **Integer** |  |  |
| **data** | [**Array&lt;AccountAdditionalCost&gt;**](AccountAdditionalCost.md) |  |  |

## Example

```ruby
require 'talon_one'

instance = TalonOne::GetAdditionalCosts200Response.new(
  total_result_size: 1,
  data: null
)
```

