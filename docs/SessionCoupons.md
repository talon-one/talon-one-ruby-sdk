# TalonOne::SessionCoupons

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **session_integration_id** | **String** | The integration ID of the session in which the coupons were applied. |  |
| **coupon_code** | **String** | The coupon codes for which rejection reason is needed. | [optional] |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::SessionCoupons.new(
  session_integration_id: cc53e4fa-547f-4f5e-8333-76e05c381f67,
  coupon_code: SUMMER2025
)
```

