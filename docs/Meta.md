# TalonOne::Meta

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **campaigns** | **Object** | Maps each evaluated campaign ID to a key-value list of that campaigns attributes. Campaigns without attributes will be omitted. | [optional] |
| **coupons** | **Object** | Maps the coupon value to a key-value list of that coupons attributes. | [optional] |
| **coupon_rejection_reason** | [**CouponRejectionReason**](CouponRejectionReason.md) |  | [optional] |
| **referral_rejection_reason** | [**ReferralRejectionReason**](ReferralRejectionReason.md) |  | [optional] |
| **warnings** | **Object** | Contains warnings about possible misuse. | [optional] |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::Meta.new(
  campaigns: null,
  coupons: null,
  coupon_rejection_reason: null,
  referral_rejection_reason: null,
  warnings: null
)
```

