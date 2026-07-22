# TalonOne::StrikethroughEffectProps

## Class instance methods

### `openapi_one_of`

Returns the list of classes defined in oneOf.

#### Example

```ruby
require 'talon_one_sdk'

TalonOne::StrikethroughEffectProps.openapi_one_of
# =>
# [
#   :'StrikethroughCustomEffectPerItemProps',
#   :'StrikethroughSetDiscountPerItemEffectProps',
#   :'StrikethroughSetDiscountPerItemMemberEffectProps'
# ]
```

### build

Find the appropriate object from the `openapi_one_of` list and casts the data into it.

#### Example

```ruby
require 'talon_one_sdk'

TalonOne::StrikethroughEffectProps.build(data)
# => #<StrikethroughCustomEffectPerItemProps:0x00007fdd4aab02a0>

TalonOne::StrikethroughEffectProps.build(data_that_doesnt_match)
# => nil
```

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **data** | **Mixed** | data to be matched against the list of oneOf items |

#### Return type

- `StrikethroughCustomEffectPerItemProps`
- `StrikethroughSetDiscountPerItemEffectProps`
- `StrikethroughSetDiscountPerItemMemberEffectProps`
- `nil` (if no type matches)

