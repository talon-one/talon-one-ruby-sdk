# TalonOne::ReferralRejectionReason

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **campaign_id** | **Integer** |  |  |
| **referral_id** | **Integer** |  |  |
| **reason** | **String** |  |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::ReferralRejectionReason.new(
  campaign_id: null,
  referral_id: null,
  reason: ReferralNotFound
)
```

