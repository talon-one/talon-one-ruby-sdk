# TalonOne::GetCustomersByAttributes200Response

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **has_more** | **Boolean** |  | [optional] |
| **total_result_size** | **Integer** |  | [optional] |
| **data** | [**Array&lt;CustomerProfile&gt;**](CustomerProfile.md) |  |  |

## Example

```ruby
require 'talon_one'

instance = TalonOne::GetCustomersByAttributes200Response.new(
  has_more: null,
  total_result_size: null,
  data: null
)
```

