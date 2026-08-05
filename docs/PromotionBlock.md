# TalonOne::PromotionBlock

## Class instance methods

### `openapi_one_of`

Returns the list of classes defined in oneOf.

#### Example

```ruby
require 'talon_one_sdk'

TalonOne::PromotionBlock.openapi_one_of
# =>
# [
#   :'AwardDiscountBlock',
#   :'AwardGiveawayBlock',
#   :'AwardItemBlock',
#   :'CheckAchievementBlock',
#   :'CheckAudienceBlock',
#   :'CheckBudgetBlock',
#   :'CheckCouponBlock',
#   :'CheckEventBlock',
#   :'CheckLoyaltyBalanceBlock',
#   :'CheckReferralBlock',
#   :'CreateCouponBlock',
#   :'CreateReferralBlock',
#   :'PassthroughBlock',
#   :'PromotionCheckAttributeBlock',
#   :'PromotionGroupBlock',
#   :'ReserveCouponBlock',
#   :'ShowNotificationBlock',
#   :'TriggerCustomEffectBlock',
#   :'TriggerWebhookBlock',
#   :'UpdateAchievementProgressBlock',
#   :'UpdateAttributeValueBlock',
#   :'UpdateAudienceMembershipBlock'
# ]
```

### `openapi_discriminator_name`

Returns the discriminator's property name.

#### Example

```ruby
require 'talon_one_sdk'

TalonOne::PromotionBlock.openapi_discriminator_name
# => :'type'
```

### `openapi_discriminator_name`

Returns the discriminator's mapping.

#### Example

```ruby
require 'talon_one_sdk'

TalonOne::PromotionBlock.openapi_discriminator_mapping
# =>
# {
#   :'awardDiscount' => :'AwardDiscountBlock',
#   :'awardGiveaway' => :'AwardGiveawayBlock',
#   :'awardItem' => :'AwardItemBlock',
#   :'checkAchievement' => :'CheckAchievementBlock',
#   :'checkAttribute' => :'PromotionCheckAttributeBlock',
#   :'checkAudience' => :'CheckAudienceBlock',
#   :'checkBudget' => :'CheckBudgetBlock',
#   :'checkCoupon' => :'CheckCouponBlock',
#   :'checkEvent' => :'CheckEventBlock',
#   :'checkLoyaltyBalance' => :'CheckLoyaltyBalanceBlock',
#   :'checkReferral' => :'CheckReferralBlock',
#   :'createCoupon' => :'CreateCouponBlock',
#   :'createReferral' => :'CreateReferralBlock',
#   :'group' => :'PromotionGroupBlock',
#   :'passthrough' => :'PassthroughBlock',
#   :'reserveCoupon' => :'ReserveCouponBlock',
#   :'showNotification' => :'ShowNotificationBlock',
#   :'triggerCustomEffect' => :'TriggerCustomEffectBlock',
#   :'triggerWebhook' => :'TriggerWebhookBlock',
#   :'updateAchievementProgress' => :'UpdateAchievementProgressBlock',
#   :'updateAttributeValue' => :'UpdateAttributeValueBlock',
#   :'updateAudienceMembership' => :'UpdateAudienceMembershipBlock'
# }
```

### build

Find the appropriate object from the `openapi_one_of` list and casts the data into it.

#### Example

```ruby
require 'talon_one_sdk'

TalonOne::PromotionBlock.build(data)
# => #<AwardDiscountBlock:0x00007fdd4aab02a0>

TalonOne::PromotionBlock.build(data_that_doesnt_match)
# => nil
```

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **data** | **Mixed** | data to be matched against the list of oneOf items |

#### Return type

- `AwardDiscountBlock`
- `AwardGiveawayBlock`
- `AwardItemBlock`
- `CheckAchievementBlock`
- `CheckAudienceBlock`
- `CheckBudgetBlock`
- `CheckCouponBlock`
- `CheckEventBlock`
- `CheckLoyaltyBalanceBlock`
- `CheckReferralBlock`
- `CreateCouponBlock`
- `CreateReferralBlock`
- `PassthroughBlock`
- `PromotionCheckAttributeBlock`
- `PromotionGroupBlock`
- `ReserveCouponBlock`
- `ShowNotificationBlock`
- `TriggerCustomEffectBlock`
- `TriggerWebhookBlock`
- `UpdateAchievementProgressBlock`
- `UpdateAttributeValueBlock`
- `UpdateAudienceMembershipBlock`
- `nil` (if no type matches)

