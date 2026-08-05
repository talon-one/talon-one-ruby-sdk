# TalonOne::CreateReferralBlock

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** | Unique identifier for this block. |  |
| **type** | **String** | Identifies the block variant and determines which additional properties are present in it. |  |
| **tags** | **Array&lt;String&gt;** | Semantic labels attached to this block. | [optional] |
| **campaign_id** | [**CreateReferralBlock1CampaignId**](CreateReferralBlock1CampaignId.md) |  |  |
| **friend_id** | **String** | An optional integration ID of the friend&#39;s profile. |  |
| **store_in_session** | **Boolean** | When &#x60;true&#x60;, the referral code is stored in the session. |  |
| **usage_limit** | [**CreateReferralBlock1UsageLimit**](CreateReferralBlock1UsageLimit.md) |  | [optional] |
| **start_date** | **Object** |  | [optional] |
| **expiry_date** | **Object** |  | [optional] |
| **attributes** | **Object** |  | [optional] |
| **valid_characters** | **String** | Characters used to generate the random parts of a code. | [optional] |
| **pattern** | **String** | The pattern used to generate codes, such as coupon codes, referral codes, and loyalty cards. The character &#x60;#&#x60; is a placeholder and is replaced by a random character from the &#x60;validCharacters&#x60; set.  | [optional] |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::CreateReferralBlock.new(
  id: a1b2c3d4-e5f6-7890-abcd-ef1234567890,
  type: null,
  tags: null,
  campaign_id: null,
  friend_id: {{$Profile.IntegrationId}},
  store_in_session: true,
  usage_limit: null,
  start_date: null,
  expiry_date: null,
  attributes: null,
  valid_characters: ABC,
  pattern: SUMMER-####-####
)
```

