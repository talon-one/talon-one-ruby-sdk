# TalonOne::Effect

## Class instance methods

### `openapi_one_of`

Returns the list of classes defined in oneOf.

#### Example

```ruby
require 'talon_one_sdk'

TalonOne::Effect.openapi_one_of
# =>
# [
#   :'EffectAcceptCoupon',
#   :'EffectAcceptReferral',
#   :'EffectAddFreeItem',
#   :'EffectAddLoyaltyPoints',
#   :'EffectAddNegativeLoyaltyPoints',
#   :'EffectAddToAudience',
#   :'EffectAwardGiveaway',
#   :'EffectCallApi',
#   :'EffectChangeLoyaltyTierLevel',
#   :'EffectCouponCreated',
#   :'EffectCustomEffect',
#   :'EffectDeductLoyaltyPoints',
#   :'EffectError',
#   :'EffectExtendLoyaltyPointsExpiryDate',
#   :'EffectIncreaseAchievementProgress',
#   :'EffectJoinLoyaltyProgram',
#   :'EffectOffsetNegativeLoyaltyPoints',
#   :'EffectRedeemReferral',
#   :'EffectReferralCreated',
#   :'EffectRejectCoupon',
#   :'EffectRejectReferral',
#   :'EffectRemoveFromAudience',
#   :'EffectReserveCoupon',
#   :'EffectRollbackAddedLoyaltyPoints',
#   :'EffectRollbackCoupon',
#   :'EffectRollbackDeductedLoyaltyPoints',
#   :'EffectRollbackDiscount',
#   :'EffectRollbackIncreasedAchievementProgress',
#   :'EffectRollbackReferral',
#   :'EffectRollbackUseReward',
#   :'EffectSet',
#   :'EffectSetDiscount',
#   :'EffectSetDiscountPerAdditionalCost',
#   :'EffectSetDiscountPerAdditionalCostPerItem',
#   :'EffectSetDiscountPerItem',
#   :'EffectSetLoyaltyPointsExpiryDate',
#   :'EffectShowBundleMetadata',
#   :'EffectShowNotification',
#   :'EffectStartAchievementProgress',
#   :'EffectUnlockReward',
#   :'EffectUseReward',
#   :'EffectWillAwardGiveaway'
# ]
```

### `openapi_discriminator_name`

Returns the discriminator's property name.

#### Example

```ruby
require 'talon_one_sdk'

TalonOne::Effect.openapi_discriminator_name
# => :'effect_type'
```

### `openapi_discriminator_name`

Returns the discriminator's mapping.

#### Example

```ruby
require 'talon_one_sdk'

TalonOne::Effect.openapi_discriminator_mapping
# =>
# {
#   :'acceptCoupon' => :'EffectAcceptCoupon',
#   :'acceptReferral' => :'EffectAcceptReferral',
#   :'addFreeItem' => :'EffectAddFreeItem',
#   :'addLoyaltyPoints' => :'EffectAddLoyaltyPoints',
#   :'addNegativeLoyaltyPoints' => :'EffectAddNegativeLoyaltyPoints',
#   :'addToAudience' => :'EffectAddToAudience',
#   :'awardGiveaway' => :'EffectAwardGiveaway',
#   :'callApi' => :'EffectCallApi',
#   :'changeLoyaltyTierLevel' => :'EffectChangeLoyaltyTierLevel',
#   :'couponCreated' => :'EffectCouponCreated',
#   :'customEffect' => :'EffectCustomEffect',
#   :'deductLoyaltyPoints' => :'EffectDeductLoyaltyPoints',
#   :'error' => :'EffectError',
#   :'extendLoyaltyPointsExpiryDate' => :'EffectExtendLoyaltyPointsExpiryDate',
#   :'increaseAchievementProgress' => :'EffectIncreaseAchievementProgress',
#   :'joinLoyaltyProgram' => :'EffectJoinLoyaltyProgram',
#   :'offsetNegativeLoyaltyPoints' => :'EffectOffsetNegativeLoyaltyPoints',
#   :'redeemReferral' => :'EffectRedeemReferral',
#   :'referralCreated' => :'EffectReferralCreated',
#   :'rejectCoupon' => :'EffectRejectCoupon',
#   :'rejectReferral' => :'EffectRejectReferral',
#   :'removeFromAudience' => :'EffectRemoveFromAudience',
#   :'reserveCoupon' => :'EffectReserveCoupon',
#   :'rollbackAddedLoyaltyPoints' => :'EffectRollbackAddedLoyaltyPoints',
#   :'rollbackCoupon' => :'EffectRollbackCoupon',
#   :'rollbackDeductedLoyaltyPoints' => :'EffectRollbackDeductedLoyaltyPoints',
#   :'rollbackDiscount' => :'EffectRollbackDiscount',
#   :'rollbackIncreasedAchievementProgress' => :'EffectRollbackIncreasedAchievementProgress',
#   :'rollbackReferral' => :'EffectRollbackReferral',
#   :'rollbackUseReward' => :'EffectRollbackUseReward',
#   :'set' => :'EffectSet',
#   :'setDiscount' => :'EffectSetDiscount',
#   :'setDiscountPerAdditionalCost' => :'EffectSetDiscountPerAdditionalCost',
#   :'setDiscountPerAdditionalCostPerItem' => :'EffectSetDiscountPerAdditionalCostPerItem',
#   :'setDiscountPerItem' => :'EffectSetDiscountPerItem',
#   :'setLoyaltyPointsExpiryDate' => :'EffectSetLoyaltyPointsExpiryDate',
#   :'showBundleMetadata' => :'EffectShowBundleMetadata',
#   :'showNotification' => :'EffectShowNotification',
#   :'startAchievementProgress' => :'EffectStartAchievementProgress',
#   :'unlockReward' => :'EffectUnlockReward',
#   :'useReward' => :'EffectUseReward',
#   :'willAwardGiveaway' => :'EffectWillAwardGiveaway'
# }
```

### build

Find the appropriate object from the `openapi_one_of` list and casts the data into it.

#### Example

```ruby
require 'talon_one_sdk'

TalonOne::Effect.build(data)
# => #<EffectAcceptCoupon:0x00007fdd4aab02a0>

TalonOne::Effect.build(data_that_doesnt_match)
# => nil
```

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **data** | **Mixed** | data to be matched against the list of oneOf items |

#### Return type

- `EffectAcceptCoupon`
- `EffectAcceptReferral`
- `EffectAddFreeItem`
- `EffectAddLoyaltyPoints`
- `EffectAddNegativeLoyaltyPoints`
- `EffectAddToAudience`
- `EffectAwardGiveaway`
- `EffectCallApi`
- `EffectChangeLoyaltyTierLevel`
- `EffectCouponCreated`
- `EffectCustomEffect`
- `EffectDeductLoyaltyPoints`
- `EffectError`
- `EffectExtendLoyaltyPointsExpiryDate`
- `EffectIncreaseAchievementProgress`
- `EffectJoinLoyaltyProgram`
- `EffectOffsetNegativeLoyaltyPoints`
- `EffectRedeemReferral`
- `EffectReferralCreated`
- `EffectRejectCoupon`
- `EffectRejectReferral`
- `EffectRemoveFromAudience`
- `EffectReserveCoupon`
- `EffectRollbackAddedLoyaltyPoints`
- `EffectRollbackCoupon`
- `EffectRollbackDeductedLoyaltyPoints`
- `EffectRollbackDiscount`
- `EffectRollbackIncreasedAchievementProgress`
- `EffectRollbackReferral`
- `EffectRollbackUseReward`
- `EffectSet`
- `EffectSetDiscount`
- `EffectSetDiscountPerAdditionalCost`
- `EffectSetDiscountPerAdditionalCostPerItem`
- `EffectSetDiscountPerItem`
- `EffectSetLoyaltyPointsExpiryDate`
- `EffectShowBundleMetadata`
- `EffectShowNotification`
- `EffectStartAchievementProgress`
- `EffectUnlockReward`
- `EffectUseReward`
- `EffectWillAwardGiveaway`
- `nil` (if no type matches)

