# TalonOne::BaseNotificationPolicy

## Class instance methods

### `openapi_one_of`

Returns the list of classes defined in oneOf.

#### Example

```ruby
require 'talon_one_sdk'

TalonOne::BaseNotificationPolicy.openapi_one_of
# =>
# [
#   :'AddedDeductedPointsBalancesNotificationPolicy',
#   :'AddedDeductedPointsNotificationPolicy',
#   :'CampaignNotificationPolicy',
#   :'CardAddedDeductedPointsBalancesNotificationPolicy',
#   :'CardAddedDeductedPointsNotificationPolicy',
#   :'CardExpiringPointsNotificationPolicy',
#   :'CatalogsStrikethroughNotificationPolicy',
#   :'CouponsNotificationPolicy',
#   :'ExpiringCouponsNotificationPolicy',
#   :'ExpiringPointsNotificationPolicy',
#   :'PendingPointsNotificationPolicy',
#   :'TierDowngradeNotificationPolicy',
#   :'TierUpgradeNotificationPolicy',
#   :'TierWillDowngradeNotificationPolicy'
# ]
```

### build

Find the appropriate object from the `openapi_one_of` list and casts the data into it.

#### Example

```ruby
require 'talon_one_sdk'

TalonOne::BaseNotificationPolicy.build(data)
# => #<AddedDeductedPointsBalancesNotificationPolicy:0x00007fdd4aab02a0>

TalonOne::BaseNotificationPolicy.build(data_that_doesnt_match)
# => nil
```

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **data** | **Mixed** | data to be matched against the list of oneOf items |

#### Return type

- `AddedDeductedPointsBalancesNotificationPolicy`
- `AddedDeductedPointsNotificationPolicy`
- `CampaignNotificationPolicy`
- `CardAddedDeductedPointsBalancesNotificationPolicy`
- `CardAddedDeductedPointsNotificationPolicy`
- `CardExpiringPointsNotificationPolicy`
- `CatalogsStrikethroughNotificationPolicy`
- `CouponsNotificationPolicy`
- `ExpiringCouponsNotificationPolicy`
- `ExpiringPointsNotificationPolicy`
- `PendingPointsNotificationPolicy`
- `TierDowngradeNotificationPolicy`
- `TierUpgradeNotificationPolicy`
- `TierWillDowngradeNotificationPolicy`
- `nil` (if no type matches)

