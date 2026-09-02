# TalonOne::CreateCouponBlock

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** | Unique identifier for this block. | [optional][readonly] |
| **type** | **String** | Identifies the block variant and determines which additional properties are present in it. |  |
| **tags** | **Array&lt;String&gt;** | Semantic labels attached to this block. | [optional][readonly] |
| **campaign_id** | [**CreateCouponBlock1CampaignId**](CreateCouponBlock1CampaignId.md) |  |  |
| **recipient_id** | **String** | The integration ID of the customer that is allowed to redeem this coupon. |  |
| **store_in_session** | **Boolean** | When &#x60;true&#x60;, the coupon is stored in the session. |  |
| **usage_limit** | [**CreateCouponBlock1UsageLimit**](CreateCouponBlock1UsageLimit.md) |  | [optional] |
| **discount_limit** | [**CreateCouponBlock1DiscountLimit**](CreateCouponBlock1DiscountLimit.md) |  | [optional] |
| **start_date** | **Object** | Timestamp at which point the coupon becomes valid. | [optional] |
| **expiry_date** | **Object** | Expiration date of the coupon. Coupon never expires if this is omitted. | [optional] |
| **attributes** | **Object** | Custom attributes associated with this coupon code. | [optional] |
| **valid_characters** | **String** | Characters used to generate the random parts of a code. | [optional] |
| **pattern** | **String** | The pattern used to generate codes, such as coupon codes, referral codes, and loyalty cards. The character &#x60;#&#x60; is a placeholder and is replaced by a random character from the &#x60;validCharacters&#x60; set.  | [optional] |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::CreateCouponBlock.new(
  id: a1b2c3d4-e5f6-7890-abcd-ef1234567890,
  type: null,
  tags: null,
  campaign_id: null,
  recipient_id: {{$Profile.IntegrationId}},
  store_in_session: true,
  usage_limit: null,
  discount_limit: null,
  start_date: 2024-12-24T14:15:22Z,
  expiry_date: 2024-12-24T14:15:22Z,
  attributes: null,
  valid_characters: ABC,
  pattern: SUMMER-####-####
)
```

