# TalonOne::CheckReferralBlock

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** | Unique identifier for this block. | [optional][readonly] |
| **type** | **String** | A block discriminator of type &#x60;checkReferral&#x60;. |  |
| **tags** | **Array&lt;String&gt;** | Semantic labels attached to this block. | [optional][readonly] |
| **redeem** | **Boolean** | When &#x60;true&#x60;, the referral code is redeemed. |  |
| **on_failure** | [**Array&lt;Block&gt;**](Block.md) | Promotion blocks evaluated when this block fails or returns false. | [optional] |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::CheckReferralBlock.new(
  id: a1b2c3d4-e5f6-7890-abcd-ef1234567890,
  type: checkReferral,
  tags: null,
  redeem: true,
  on_failure: null
)
```

