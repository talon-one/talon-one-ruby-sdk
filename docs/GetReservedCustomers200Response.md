# TalonOne::GetReservedCustomers200Response

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **total_result_size** | **Integer** |  |  |
| **data** | [**Array&lt;CustomerProfile&gt;**](CustomerProfile.md) |  |  |

## Example

```ruby
require 'talon_one'

instance = TalonOne::GetReservedCustomers200Response.new(
  total_result_size: 1,
  data: null
)
```

