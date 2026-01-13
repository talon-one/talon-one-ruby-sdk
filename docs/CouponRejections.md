# TalonOne::CouponRejections

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **session_details** | [**Array&lt;SessionCoupons&gt;**](SessionCoupons.md) | Array containing details from session like session id and optional coupon code used in the session. Only the first 15 entries will be processed. |  |
| **application_id** | **Integer** | The application ID for which the coupon was used. |  |
| **language** | **String** | The language the summary will be generated in. | [optional] |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::CouponRejections.new(
  session_details: null,
  application_id: 123,
  language: en
)
```

