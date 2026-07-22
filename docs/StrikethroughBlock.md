# TalonOne::StrikethroughBlock

## Class instance methods

### `openapi_one_of`

Returns the list of classes defined in oneOf.

#### Example

```ruby
require 'talon_one_sdk'

TalonOne::StrikethroughBlock.openapi_one_of
# =>
# [
#   :'PassthroughBlock',
#   :'StrikethroughCheckAttributeBlock',
#   :'StrikethroughGroupBlock'
# ]
```

### `openapi_discriminator_name`

Returns the discriminator's property name.

#### Example

```ruby
require 'talon_one_sdk'

TalonOne::StrikethroughBlock.openapi_discriminator_name
# => :'type'
```

### `openapi_discriminator_name`

Returns the discriminator's mapping.

#### Example

```ruby
require 'talon_one_sdk'

TalonOne::StrikethroughBlock.openapi_discriminator_mapping
# =>
# {
#   :'checkAttribute' => :'StrikethroughCheckAttributeBlock',
#   :'group' => :'StrikethroughGroupBlock',
#   :'passthrough' => :'PassthroughBlock'
# }
```

### build

Find the appropriate object from the `openapi_one_of` list and casts the data into it.

#### Example

```ruby
require 'talon_one_sdk'

TalonOne::StrikethroughBlock.build(data)
# => #<PassthroughBlock:0x00007fdd4aab02a0>

TalonOne::StrikethroughBlock.build(data_that_doesnt_match)
# => nil
```

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **data** | **Mixed** | data to be matched against the list of oneOf items |

#### Return type

- `PassthroughBlock`
- `StrikethroughCheckAttributeBlock`
- `StrikethroughGroupBlock`
- `nil` (if no type matches)

