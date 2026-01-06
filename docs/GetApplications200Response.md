# TalonOne::GetApplications200Response

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **total_result_size** | **Integer** |  |  |
| **data** | [**Array&lt;Application&gt;**](Application.md) |  |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::GetApplications200Response.new(
  total_result_size: 1,
  data: null
)
```

