# TalonOne::GetApplicationCustomers200Response

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **total_result_size** | **Integer** |  | [optional] |
| **has_more** | **Boolean** |  | [optional] |
| **data** | [**Array&lt;ApplicationCustomer&gt;**](ApplicationCustomer.md) |  |  |

## Example

```ruby
require 'talon_one'

instance = TalonOne::GetApplicationCustomers200Response.new(
  total_result_size: 1,
  has_more: null,
  data: null
)
```

