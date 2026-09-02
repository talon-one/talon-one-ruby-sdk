# TalonOne::LocationCheckAttributeBlockValues

## Class instance methods

### `openapi_one_of`

Returns the list of classes defined in oneOf.

#### Example

```ruby
require 'talon_one_sdk'

TalonOne::LocationCheckAttributeBlockValues.openapi_one_of
# =>
# [
#   :'Array<LocationCheckAttributeBlockValuesOneOfInner>',
#   :'String'
# ]
```

### build

Find the appropriate object from the `openapi_one_of` list and casts the data into it.

#### Example

```ruby
require 'talon_one_sdk'

TalonOne::LocationCheckAttributeBlockValues.build(data)
# => #<Array<LocationCheckAttributeBlockValuesOneOfInner>:0x00007fdd4aab02a0>

TalonOne::LocationCheckAttributeBlockValues.build(data_that_doesnt_match)
# => nil
```

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **data** | **Mixed** | data to be matched against the list of oneOf items |

#### Return type

- `Array<LocationCheckAttributeBlockValuesOneOfInner>`
- `String`
- `nil` (if no type matches)

