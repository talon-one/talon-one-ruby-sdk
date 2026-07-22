# TalonOne::EffectProps

## Class instance methods

### `openapi_one_of`

Returns the list of classes defined in oneOf.

#### Example

```ruby
require 'talon_one_sdk'

TalonOne::EffectProps.openapi_one_of
# =>
# [
#   :'AcceptCouponEffectProps',
#   :'AcceptReferralEffectProps',
#   :'AddFreeItemEffectProps',
#   :'AddLoyaltyPointsEffectProps',
#   :'AddToAudienceEffectProps',
#   :'AwardGiveawayEffectProps',
#   :'ChangeLoyaltyTierLevelEffectProps',
#   :'CouponCreatedEffectProps',
#   :'CustomEffectProps',
#   :'DeductLoyaltyPointsEffectProps',
#   :'ErrorEffectProps',
#   :'ExtendLoyaltyPointsExpiryDateEffectProps',
#   :'IncreaseAchievementProgressEffectProps',
#   :'RedeemReferralEffectProps',
#   :'ReferralCreatedEffectProps',
#   :'RejectCouponEffectProps',
#   :'RejectReferralEffectProps',
#   :'RemoveFromAudienceEffectProps',
#   :'ReserveCouponEffectProps',
#   :'RollbackAddedLoyaltyPointsEffectProps',
#   :'RollbackCouponEffectProps',
#   :'RollbackDeductedLoyaltyPointsEffectProps',
#   :'RollbackDiscountEffectProps',
#   :'RollbackIncreasedAchievementProgressEffectProps',
#   :'RollbackReferralEffectProps',
#   :'SetDiscountEffectProps',
#   :'SetDiscountPerAdditionalCostEffectProps',
#   :'SetDiscountPerAdditionalCostPerItemEffectProps',
#   :'SetDiscountPerItemEffectProps',
#   :'SetLoyaltyPointsExpiryDateEffectProps',
#   :'ShowBundleMetadataEffectProps',
#   :'ShowNotificationEffectProps',
#   :'TriggerWebhookEffectProps',
#   :'UpdateAttributeEffectProps',
#   :'WillAwardGiveawayEffectProps'
# ]
```

### build

Find the appropriate object from the `openapi_one_of` list and casts the data into it.

#### Example

```ruby
require 'talon_one_sdk'

TalonOne::EffectProps.build(data)
# => #<AcceptCouponEffectProps:0x00007fdd4aab02a0>

TalonOne::EffectProps.build(data_that_doesnt_match)
# => nil
```

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **data** | **Mixed** | data to be matched against the list of oneOf items |

#### Return type

- `AcceptCouponEffectProps`
- `AcceptReferralEffectProps`
- `AddFreeItemEffectProps`
- `AddLoyaltyPointsEffectProps`
- `AddToAudienceEffectProps`
- `AwardGiveawayEffectProps`
- `ChangeLoyaltyTierLevelEffectProps`
- `CouponCreatedEffectProps`
- `CustomEffectProps`
- `DeductLoyaltyPointsEffectProps`
- `ErrorEffectProps`
- `ExtendLoyaltyPointsExpiryDateEffectProps`
- `IncreaseAchievementProgressEffectProps`
- `RedeemReferralEffectProps`
- `ReferralCreatedEffectProps`
- `RejectCouponEffectProps`
- `RejectReferralEffectProps`
- `RemoveFromAudienceEffectProps`
- `ReserveCouponEffectProps`
- `RollbackAddedLoyaltyPointsEffectProps`
- `RollbackCouponEffectProps`
- `RollbackDeductedLoyaltyPointsEffectProps`
- `RollbackDiscountEffectProps`
- `RollbackIncreasedAchievementProgressEffectProps`
- `RollbackReferralEffectProps`
- `SetDiscountEffectProps`
- `SetDiscountPerAdditionalCostEffectProps`
- `SetDiscountPerAdditionalCostPerItemEffectProps`
- `SetDiscountPerItemEffectProps`
- `SetLoyaltyPointsExpiryDateEffectProps`
- `ShowBundleMetadataEffectProps`
- `ShowNotificationEffectProps`
- `TriggerWebhookEffectProps`
- `UpdateAttributeEffectProps`
- `WillAwardGiveawayEffectProps`
- `nil` (if no type matches)

