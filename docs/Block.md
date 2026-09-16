# TalonOne::Block

## Class instance methods

### `openapi_one_of`

Returns the list of classes defined in oneOf.

#### Example

```ruby
require 'talon_one_sdk'

TalonOne::Block.openapi_one_of
# =>
# [
#   :'AwardDiscountBlock',
#   :'AwardGiveawayBlock',
#   :'AwardItemBlock',
#   :'AwardLoyaltyPointsBlock',
#   :'CheckAchievementBlock',
#   :'CheckAttributeBlock',
#   :'CheckAudienceBlock',
#   :'CheckBudgetBlock',
#   :'CheckCouponBlock',
#   :'CheckEventBlock',
#   :'CheckLoyaltyBalanceBlock',
#   :'CheckLoyaltyCardBlock',
#   :'CheckReferralBlock',
#   :'CheckTierBlock',
#   :'CreateCouponBlock',
#   :'CreateReferralBlock',
#   :'GroupBlock',
#   :'PassthroughBlock',
#   :'RedeemLoyaltyPointsBlock',
#   :'ReserveCouponBlock',
#   :'ShowNotificationBlock',
#   :'TriggerCustomEffectBlock',
#   :'TriggerWebhookBlock',
#   :'UpdateAchievementProgressBlock',
#   :'UpdateAttributeValueBlock',
#   :'UpdateAudienceMembershipBlock',
#   :'UpdateLoyaltyPointsExpiryBlock'
# ]
```

### `openapi_discriminator_name`

Returns the discriminator's property name.

#### Example

```ruby
require 'talon_one_sdk'

TalonOne::Block.openapi_discriminator_name
# => :'type'
```

### `openapi_discriminator_name`

Returns the discriminator's mapping.

#### Example

```ruby
require 'talon_one_sdk'

TalonOne::Block.openapi_discriminator_mapping
# =>
# {
#   :'awardDiscount' => :'AwardDiscountBlock',
#   :'awardGiveaway' => :'AwardGiveawayBlock',
#   :'awardItem' => :'AwardItemBlock',
#   :'awardLoyaltyPoints' => :'AwardLoyaltyPointsBlock',
#   :'checkAchievement' => :'CheckAchievementBlock',
#   :'checkAttribute' => :'CheckAttributeBlock',
#   :'checkAudience' => :'CheckAudienceBlock',
#   :'checkBudget' => :'CheckBudgetBlock',
#   :'checkCoupon' => :'CheckCouponBlock',
#   :'checkEvent' => :'CheckEventBlock',
#   :'checkLoyaltyBalance' => :'CheckLoyaltyBalanceBlock',
#   :'checkLoyaltyCard' => :'CheckLoyaltyCardBlock',
#   :'checkReferral' => :'CheckReferralBlock',
#   :'checkTier' => :'CheckTierBlock',
#   :'createCoupon' => :'CreateCouponBlock',
#   :'createReferral' => :'CreateReferralBlock',
#   :'group' => :'GroupBlock',
#   :'passthrough' => :'PassthroughBlock',
#   :'redeemLoyaltyPoints' => :'RedeemLoyaltyPointsBlock',
#   :'reserveCoupon' => :'ReserveCouponBlock',
#   :'showNotification' => :'ShowNotificationBlock',
#   :'triggerCustomEffect' => :'TriggerCustomEffectBlock',
#   :'triggerWebhook' => :'TriggerWebhookBlock',
#   :'updateAchievementProgress' => :'UpdateAchievementProgressBlock',
#   :'updateAttributeValue' => :'UpdateAttributeValueBlock',
#   :'updateAudienceMembership' => :'UpdateAudienceMembershipBlock',
#   :'updateLoyaltyPointsExpiry' => :'UpdateLoyaltyPointsExpiryBlock'
# }
```

### build

Find the appropriate object from the `openapi_one_of` list and casts the data into it.

#### Example

```ruby
require 'talon_one_sdk'

TalonOne::Block.build(data)
# => #<AwardDiscountBlock:0x00007fdd4aab02a0>

TalonOne::Block.build(data_that_doesnt_match)
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
- `AwardLoyaltyPointsBlock`
- `CheckAchievementBlock`
- `CheckAttributeBlock`
- `CheckAudienceBlock`
- `CheckBudgetBlock`
- `CheckCouponBlock`
- `CheckEventBlock`
- `CheckLoyaltyBalanceBlock`
- `CheckLoyaltyCardBlock`
- `CheckReferralBlock`
- `CheckTierBlock`
- `CreateCouponBlock`
- `CreateReferralBlock`
- `GroupBlock`
- `PassthroughBlock`
- `RedeemLoyaltyPointsBlock`
- `ReserveCouponBlock`
- `ShowNotificationBlock`
- `TriggerCustomEffectBlock`
- `TriggerWebhookBlock`
- `UpdateAchievementProgressBlock`
- `UpdateAttributeValueBlock`
- `UpdateAudienceMembershipBlock`
- `UpdateLoyaltyPointsExpiryBlock`
- `nil` (if no type matches)

