# TalonOne::GetReservedCustomers200Response

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **total_result_size** | **Integer** |  |  |
| **data** | [**Array&lt;CustomerReservation&gt;**](CustomerReservation.md) |  |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::GetReservedCustomers200Response.new(
  total_result_size: 1,
  data: null
)
```

