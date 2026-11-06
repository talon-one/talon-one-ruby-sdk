# TalonOne::CouponCodeExpiringNotification

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **total_result_size** | **Integer** |  |  |
| **data** | [**Array&lt;CouponCodeExpiringNotificationData&gt;**](CouponCodeExpiringNotificationData.md) | The array of expiring coupon notifications. |  |
| **notification_type** | **String** | The type of notification. |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::CouponCodeExpiringNotification.new(
  total_result_size: 1,
  data: null,
  notification_type: null
)
```

