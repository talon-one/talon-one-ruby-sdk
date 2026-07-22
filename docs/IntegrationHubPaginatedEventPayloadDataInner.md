# TalonOne::IntegrationHubPaginatedEventPayloadDataInner

## Class instance methods

### `openapi_one_of`

Returns the list of classes defined in oneOf.

#### Example

```ruby
require 'talon_one_sdk'

TalonOne::IntegrationHubPaginatedEventPayloadDataInner.openapi_one_of
# =>
# [
#   :'IntegrationHubEventPayloadCouponBasedNotifications',
#   :'IntegrationHubEventPayloadLoyaltyProfileBasedPointsChangedNotification',
#   :'IntegrationHubEventPayloadLoyaltyProfileBasedTierDowngradeNotification',
#   :'IntegrationHubEventPayloadLoyaltyProfileBasedTierUpgradeNotification'
# ]
```

### `openapi_discriminator_name`

Returns the discriminator's property name.

#### Example

```ruby
require 'talon_one_sdk'

TalonOne::IntegrationHubPaginatedEventPayloadDataInner.openapi_discriminator_name
# => :'event_type'
```

### `openapi_discriminator_name`

Returns the discriminator's mapping.

#### Example

```ruby
require 'talon_one_sdk'

TalonOne::IntegrationHubPaginatedEventPayloadDataInner.openapi_discriminator_mapping
# =>
# {
#   :'CouponCreated' => :'IntegrationHubEventPayloadCouponBasedNotifications',
#   :'CouponDeleted' => :'IntegrationHubEventPayloadCouponBasedNotifications',
#   :'CouponUpdated' => :'IntegrationHubEventPayloadCouponBasedNotifications',
#   :'LoyaltyPointsChanged' => :'IntegrationHubEventPayloadLoyaltyProfileBasedPointsChangedNotification',
#   :'LoyaltyTierDowngrade' => :'IntegrationHubEventPayloadLoyaltyProfileBasedTierDowngradeNotification',
#   :'LoyaltyTierUpgrade' => :'IntegrationHubEventPayloadLoyaltyProfileBasedTierUpgradeNotification'
# }
```

### build

Find the appropriate object from the `openapi_one_of` list and casts the data into it.

#### Example

```ruby
require 'talon_one_sdk'

TalonOne::IntegrationHubPaginatedEventPayloadDataInner.build(data)
# => #<IntegrationHubEventPayloadCouponBasedNotifications:0x00007fdd4aab02a0>

TalonOne::IntegrationHubPaginatedEventPayloadDataInner.build(data_that_doesnt_match)
# => nil
```

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **data** | **Mixed** | data to be matched against the list of oneOf items |

#### Return type

- `IntegrationHubEventPayloadCouponBasedNotifications`
- `IntegrationHubEventPayloadLoyaltyProfileBasedPointsChangedNotification`
- `IntegrationHubEventPayloadLoyaltyProfileBasedTierDowngradeNotification`
- `IntegrationHubEventPayloadLoyaltyProfileBasedTierUpgradeNotification`
- `nil` (if no type matches)

