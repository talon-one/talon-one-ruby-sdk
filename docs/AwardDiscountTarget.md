# TalonOne::AwardDiscountTarget

## Class instance methods

### `openapi_one_of`

Returns the list of classes defined in oneOf.

#### Example

```ruby
require 'talon_one_sdk'

TalonOne::AwardDiscountTarget.openapi_one_of
# =>
# [
#   :'AwardDiscountAdditionalCostTarget',
#   :'AwardDiscountAllItemsTarget',
#   :'AwardDiscountBundleTarget',
#   :'AwardDiscountCartTarget',
#   :'AwardDiscountGlobalFilterTarget',
#   :'AwardDiscountSelectorTarget'
# ]
```

### `openapi_discriminator_name`

Returns the discriminator's property name.

#### Example

```ruby
require 'talon_one_sdk'

TalonOne::AwardDiscountTarget.openapi_discriminator_name
# => :'type'
```

### `openapi_discriminator_name`

Returns the discriminator's mapping.

#### Example

```ruby
require 'talon_one_sdk'

TalonOne::AwardDiscountTarget.openapi_discriminator_mapping
# =>
# {
#   :'additionalCost' => :'AwardDiscountAdditionalCostTarget',
#   :'allItems' => :'AwardDiscountAllItemsTarget',
#   :'bundle' => :'AwardDiscountBundleTarget',
#   :'cart' => :'AwardDiscountCartTarget',
#   :'globalFilter' => :'AwardDiscountGlobalFilterTarget',
#   :'selector' => :'AwardDiscountSelectorTarget'
# }
```

### build

Find the appropriate object from the `openapi_one_of` list and casts the data into it.

#### Example

```ruby
require 'talon_one_sdk'

TalonOne::AwardDiscountTarget.build(data)
# => #<AwardDiscountAdditionalCostTarget:0x00007fdd4aab02a0>

TalonOne::AwardDiscountTarget.build(data_that_doesnt_match)
# => nil
```

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **data** | **Mixed** | data to be matched against the list of oneOf items |

#### Return type

- `AwardDiscountAdditionalCostTarget`
- `AwardDiscountAllItemsTarget`
- `AwardDiscountBundleTarget`
- `AwardDiscountCartTarget`
- `AwardDiscountGlobalFilterTarget`
- `AwardDiscountSelectorTarget`
- `nil` (if no type matches)

