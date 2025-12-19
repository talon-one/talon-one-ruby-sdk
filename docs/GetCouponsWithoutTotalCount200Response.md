# TalonOne::GetCouponsWithoutTotalCount200Response

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **has_more** | **Boolean** |  |  |
| **data** | [**Array&lt;Coupon&gt;**](Coupon.md) |  |  |

## Example

```ruby
require 'talon_one'

instance = TalonOne::GetCouponsWithoutTotalCount200Response.new(
  has_more: true,
  data: null
)
```

