# TalonOne::CustomerInventory

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **profile** | [**CustomerProfile**](CustomerProfile.md) |  | [optional] |
| **loyalty** | [**Loyalty**](Loyalty.md) |  | [optional] |
| **referrals** | [**Array&lt;InventoryReferral&gt;**](InventoryReferral.md) |  | [optional] |
| **coupons** | [**Array&lt;InventoryCoupon&gt;**](InventoryCoupon.md) | The coupons reserved by this profile. This array includes hard and soft reservations.  | [optional] |
| **giveaways** | [**Array&lt;Giveaway&gt;**](Giveaway.md) |  | [optional] |
| **achievements** | [**Array&lt;AchievementProgressWithDefinition&gt;**](AchievementProgressWithDefinition.md) | The customer&#39;s progress in each achievement they have participated in.  Only achievements the customer has started are included, whether they  are in progress, completed, or expired. Recurring achievements can appear  more than once, once per iteration.  | [optional] |
| **rewards** | [**Array&lt;RewardWithUnlocks&gt;**](RewardWithUnlocks.md) | The rewards that the customer has unlocked but not used. Expired customer rewards are not returned. | [optional] |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::CustomerInventory.new(
  profile: null,
  loyalty: null,
  referrals: null,
  coupons: null,
  giveaways: null,
  achievements: null,
  rewards: null
)
```

