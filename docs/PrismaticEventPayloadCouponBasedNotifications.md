# TalonOne::PrismaticEventPayloadCouponBasedNotifications

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** |  |  |
| **created** | **Time** |  |  |
| **campaign_id** | **Integer** |  |  |
| **value** | **String** |  |  |
| **usage_limit** | **Integer** |  |  |
| **discount_limit** | **Float** |  | [optional] |
| **reservation_limit** | **Integer** |  | [optional] |
| **start_date** | **Time** |  | [optional] |
| **expiry_date** | **Time** |  | [optional] |
| **usage_counter** | **Integer** |  |  |
| **discount_counter** | **Float** |  | [optional] |
| **discount_remainder** | **Float** |  | [optional] |
| **referral_id** | **Integer** |  | [optional] |
| **recipient_integration_id** | **String** |  | [optional] |
| **import_id** | **Integer** |  | [optional] |
| **batch_id** | **String** |  | [optional] |
| **attributes** | **Object** |  | [optional] |
| **limits** | [**Array&lt;PrismaticEventPayloadCouponBasedNotificationsLimits&gt;**](PrismaticEventPayloadCouponBasedNotificationsLimits.md) |  | [optional] |
| **published_at** | **Time** | Timestamp when the event was published. |  |
| **source_of_event** | **String** |  |  |
| **employee_name** | **String** |  |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::PrismaticEventPayloadCouponBasedNotifications.new(
  id: null,
  created: null,
  campaign_id: null,
  value: null,
  usage_limit: null,
  discount_limit: null,
  reservation_limit: null,
  start_date: null,
  expiry_date: null,
  usage_counter: null,
  discount_counter: null,
  discount_remainder: null,
  referral_id: null,
  recipient_integration_id: null,
  import_id: null,
  batch_id: null,
  attributes: null,
  limits: null,
  published_at: null,
  source_of_event: null,
  employee_name: null
)
```

