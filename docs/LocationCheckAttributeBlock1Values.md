# TalonOne::LocationCheckAttributeBlock1Values

## Class instance methods

### `openapi_one_of`

Returns the list of classes defined in oneOf.

#### Example

```ruby
require 'talon_one_sdk'

TalonOne::LocationCheckAttributeBlock1Values.openapi_one_of
# =>
# [
#   :'Array<LocationCheckAttributeBlock1ValuesOneOfInner>',
#   :'String'
# ]
```

### build

Find the appropriate object from the `openapi_one_of` list and casts the data into it.

#### Example

```ruby
require 'talon_one_sdk'

TalonOne::LocationCheckAttributeBlock1Values.build(data)
# => #<Array<LocationCheckAttributeBlock1ValuesOneOfInner>:0x00007fdd4aab02a0>

TalonOne::LocationCheckAttributeBlock1Values.build(data_that_doesnt_match)
# => nil
```

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **data** | **Mixed** | data to be matched against the list of oneOf items |

#### Return type

- `Array<LocationCheckAttributeBlock1ValuesOneOfInner>`
- `String`
- `nil` (if no type matches)

