# TalonOne::GetApplicationCustomersByAttributes200Response

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **has_more** | **Boolean** |  | [optional] |
| **total_result_size** | **Integer** |  | [optional] |
| **data** | [**Array&lt;ApplicationCustomer&gt;**](ApplicationCustomer.md) |  |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::GetApplicationCustomersByAttributes200Response.new(
  has_more: null,
  total_result_size: null,
  data: null
)
```

