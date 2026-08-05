# TalonOne::AwardDiscountBundleItem

## Class instance methods

### `openapi_one_of`

Returns the list of classes defined in oneOf.

#### Example

```ruby
require 'talon_one_sdk'

TalonOne::AwardDiscountBundleItem.openapi_one_of
# =>
# [
#   :'AwardDiscountBundleItemByAttribute',
#   :'AwardDiscountBundleItemByIndex'
# ]
```

### `openapi_discriminator_name`

Returns the discriminator's property name.

#### Example

```ruby
require 'talon_one_sdk'

TalonOne::AwardDiscountBundleItem.openapi_discriminator_name
# => :'type'
```

### `openapi_discriminator_name`

Returns the discriminator's mapping.

#### Example

```ruby
require 'talon_one_sdk'

TalonOne::AwardDiscountBundleItem.openapi_discriminator_mapping
# =>
# {
#   :'byAttribute' => :'AwardDiscountBundleItemByAttribute',
#   :'byIndex' => :'AwardDiscountBundleItemByIndex'
# }
```

### build

Find the appropriate object from the `openapi_one_of` list and casts the data into it.

#### Example

```ruby
require 'talon_one_sdk'

TalonOne::AwardDiscountBundleItem.build(data)
# => #<AwardDiscountBundleItemByAttribute:0x00007fdd4aab02a0>

TalonOne::AwardDiscountBundleItem.build(data_that_doesnt_match)
# => nil
```

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **data** | **Mixed** | data to be matched against the list of oneOf items |

#### Return type

- `AwardDiscountBundleItemByAttribute`
- `AwardDiscountBundleItemByIndex`
- `nil` (if no type matches)

