# TalonOne::CatalogAction

## Class instance methods

### `openapi_one_of`

Returns the list of classes defined in oneOf.

#### Example

```ruby
require 'talon_one_sdk'

TalonOne::CatalogAction.openapi_one_of
# =>
# [
#   :'CatalogActionAdd',
#   :'CatalogActionAddPriceAdjustment',
#   :'CatalogActionPatch',
#   :'CatalogActionPatchMany',
#   :'CatalogActionRemove',
#   :'CatalogActionRemoveMany'
# ]
```

### `openapi_discriminator_name`

Returns the discriminator's property name.

#### Example

```ruby
require 'talon_one_sdk'

TalonOne::CatalogAction.openapi_discriminator_name
# => :'type'
```

### `openapi_discriminator_name`

Returns the discriminator's mapping.

#### Example

```ruby
require 'talon_one_sdk'

TalonOne::CatalogAction.openapi_discriminator_mapping
# =>
# {
#   :'ADD' => :'CatalogActionAdd',
#   :'ADD_PRICE_ADJUSTMENT' => :'CatalogActionAddPriceAdjustment',
#   :'PATCH' => :'CatalogActionPatch',
#   :'PATCH_MANY' => :'CatalogActionPatchMany',
#   :'REMOVE' => :'CatalogActionRemove',
#   :'REMOVE_MANY' => :'CatalogActionRemoveMany'
# }
```

### build

Find the appropriate object from the `openapi_one_of` list and casts the data into it.

#### Example

```ruby
require 'talon_one_sdk'

TalonOne::CatalogAction.build(data)
# => #<CatalogActionAdd:0x00007fdd4aab02a0>

TalonOne::CatalogAction.build(data_that_doesnt_match)
# => nil
```

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **data** | **Mixed** | data to be matched against the list of oneOf items |

#### Return type

- `CatalogActionAdd`
- `CatalogActionAddPriceAdjustment`
- `CatalogActionPatch`
- `CatalogActionPatchMany`
- `CatalogActionRemove`
- `CatalogActionRemoveMany`
- `nil` (if no type matches)

