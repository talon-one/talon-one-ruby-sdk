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
#   :'AwardGiveawayBlock',
#   :'AwardItemBlock',
#   :'CheckAudienceBlock',
#   :'CheckCouponBlock',
#   :'CheckReferralBlock',
#   :'PassthroughBlock',
#   :'PromotionCheckAttributeBlock',
#   :'PromotionGroupBlock',
#   :'ShowNotificationBlock',
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
#   :'awardGiveaway' => :'AwardGiveawayBlock',
#   :'awardItem' => :'AwardItemBlock',
#   :'checkAttribute' => :'PromotionCheckAttributeBlock',
#   :'checkAudience' => :'CheckAudienceBlock',
#   :'checkCoupon' => :'CheckCouponBlock',
#   :'checkReferral' => :'CheckReferralBlock',
#   :'group' => :'PromotionGroupBlock',
#   :'passthrough' => :'PassthroughBlock',
#   :'showNotification' => :'ShowNotificationBlock',
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
# => #<AwardGiveawayBlock:0x00007fdd4aab02a0>

TalonOne::PromotionBlock.build(data_that_doesnt_match)
# => nil
```

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **data** | **Mixed** | data to be matched against the list of oneOf items |

#### Return type

- `AwardGiveawayBlock`
- `AwardItemBlock`
- `CheckAudienceBlock`
- `CheckCouponBlock`
- `CheckReferralBlock`
- `PassthroughBlock`
- `PromotionCheckAttributeBlock`
- `PromotionGroupBlock`
- `ShowNotificationBlock`
- `UpdateAchievementProgressBlock`
- `UpdateAttributeValueBlock`
- `UpdateAudienceMembershipBlock`
- `nil` (if no type matches)

