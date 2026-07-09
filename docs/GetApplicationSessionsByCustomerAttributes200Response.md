# TalonOne::GetApplicationSessionsByCustomerAttributes200Response

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **has_more** | **Boolean** |  | [optional] |
| **total_result_size** | **Integer** |  | [optional] |
| **data** | [**Array&lt;ApplicationSession&gt;**](ApplicationSession.md) |  |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::GetApplicationSessionsByCustomerAttributes200Response.new(
  has_more: null,
  total_result_size: null,
  data: null
)
```

