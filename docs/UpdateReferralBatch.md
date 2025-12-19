# TalonOne::UpdateReferralBatch

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **attributes** | **Object** | Arbitrary properties associated with this item. | [optional] |
| **batch_id** | **String** | The id of the batch the referral belongs to. |  |
| **start_date** | **Time** | Timestamp at which point the referral code becomes valid. | [optional] |
| **expiry_date** | **Time** | Expiration date of the referral code. Referral never expires if this is omitted. | [optional] |
| **usage_limit** | **Integer** | The number of times a referral code can be used. This can be set to 0 for no limit, but any campaign usage limits will still apply.  | [optional] |

## Example

```ruby
require 'talon_one'

instance = TalonOne::UpdateReferralBatch.new(
  attributes: null,
  batch_id: 32535-43255,
  start_date: 2020-11-10T23:00:00Z,
  expiry_date: 2021-11-10T23:00:00Z,
  usage_limit: 1
)
```

