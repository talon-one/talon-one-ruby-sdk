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
#   :'CatalogActionOneOf',
#   :'CatalogActionOneOf1',
#   :'CatalogActionOneOf2',
#   :'CatalogActionOneOf3',
#   :'CatalogActionOneOf4',
#   :'CatalogActionOneOf5'
# ]
```

### build

Find the appropriate object from the `openapi_one_of` list and casts the data into it.

#### Example

```ruby
require 'talon_one_sdk'

TalonOne::CatalogAction.build(data)
# => #<CatalogActionOneOf:0x00007fdd4aab02a0>

TalonOne::CatalogAction.build(data_that_doesnt_match)
# => nil
```

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **data** | **Mixed** | data to be matched against the list of oneOf items |

#### Return type

- `CatalogActionOneOf`
- `CatalogActionOneOf1`
- `CatalogActionOneOf2`
- `CatalogActionOneOf3`
- `CatalogActionOneOf4`
- `CatalogActionOneOf5`
- `nil` (if no type matches)

