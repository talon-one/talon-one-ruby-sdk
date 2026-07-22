# TalonOne::NewCouponCreationJob

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **usage_limit** | **Integer** | The number of times the coupon code can be redeemed. &#x60;0&#x60; means unlimited redemptions but any campaign usage limits will still apply.  | [optional] |
| **discount_limit** | **Float** | The total discount value that the code can give. Typically used to represent a gift card value.  | [optional] |
| **reservation_limit** | **Integer** | The number of reservations that can be made with this coupon code.  | [optional] |
| **start_date** | **Time** | Timestamp at which point the coupon becomes valid. | [optional] |
| **expiry_date** | **Time** | Expiration date of the coupon. Coupon never expires if this is omitted. | [optional] |
| **number_of_coupons** | **Integer** | The number of new coupon codes to generate for the campaign. |  |
| **coupon_settings** | [**CodeGeneratorSettings**](CodeGeneratorSettings.md) |  | [optional] |
| **attributes** | **Object** | Arbitrary properties associated with coupons. |  |
| **is_reservation_mandatory** | **Boolean** | An indication of whether the code can be redeemed only if it has been reserved first. | [optional][default to false] |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::NewCouponCreationJob.new(
  usage_limit: 100,
  discount_limit: 30,
  reservation_limit: 45,
  start_date: 2020-01-24T14:15:22Z,
  expiry_date: 2023-08-24T14:15:22Z,
  number_of_coupons: 200000,
  coupon_settings: null,
  attributes: null,
  is_reservation_mandatory: false
)
```

