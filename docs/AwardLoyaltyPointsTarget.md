# TalonOne::AwardLoyaltyPointsTarget

## Class instance methods

### `openapi_one_of`

Returns the list of classes defined in oneOf.

#### Example

```ruby
require 'talon_one_sdk'

TalonOne::AwardLoyaltyPointsTarget.openapi_one_of
# =>
# [
#   :'AwardLoyaltyPointsAllItemsTarget',
#   :'AwardLoyaltyPointsBundleTarget',
#   :'AwardLoyaltyPointsCartTarget',
#   :'AwardLoyaltyPointsGlobalFilterTarget',
#   :'AwardLoyaltyPointsSelectorTarget'
# ]
```

### `openapi_discriminator_name`

Returns the discriminator's property name.

#### Example

```ruby
require 'talon_one_sdk'

TalonOne::AwardLoyaltyPointsTarget.openapi_discriminator_name
# => :'type'
```

### `openapi_discriminator_name`

Returns the discriminator's mapping.

#### Example

```ruby
require 'talon_one_sdk'

TalonOne::AwardLoyaltyPointsTarget.openapi_discriminator_mapping
# =>
# {
#   :'allItems' => :'AwardLoyaltyPointsAllItemsTarget',
#   :'bundle' => :'AwardLoyaltyPointsBundleTarget',
#   :'cart' => :'AwardLoyaltyPointsCartTarget',
#   :'globalFilter' => :'AwardLoyaltyPointsGlobalFilterTarget',
#   :'selector' => :'AwardLoyaltyPointsSelectorTarget'
# }
```

### build

Find the appropriate object from the `openapi_one_of` list and casts the data into it.

#### Example

```ruby
require 'talon_one_sdk'

TalonOne::AwardLoyaltyPointsTarget.build(data)
# => #<AwardLoyaltyPointsAllItemsTarget:0x00007fdd4aab02a0>

TalonOne::AwardLoyaltyPointsTarget.build(data_that_doesnt_match)
# => nil
```

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **data** | **Mixed** | data to be matched against the list of oneOf items |

#### Return type

- `AwardLoyaltyPointsAllItemsTarget`
- `AwardLoyaltyPointsBundleTarget`
- `AwardLoyaltyPointsCartTarget`
- `AwardLoyaltyPointsGlobalFilterTarget`
- `AwardLoyaltyPointsSelectorTarget`
- `nil` (if no type matches)

