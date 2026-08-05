# TalonOne::CheckAttributeBlock

## Class instance methods

### `openapi_one_of`

Returns the list of classes defined in oneOf.

#### Example

```ruby
require 'talon_one_sdk'

TalonOne::CheckAttributeBlock.openapi_one_of
# =>
# [
#   :'CheckAttributeBlockBase'
# ]
```

### `openapi_discriminator_name`

Returns the discriminator's property name.

#### Example

```ruby
require 'talon_one_sdk'

TalonOne::CheckAttributeBlock.openapi_discriminator_name
# => :'operator'
```

### `openapi_discriminator_name`

Returns the discriminator's mapping.

#### Example

```ruby
require 'talon_one_sdk'

TalonOne::CheckAttributeBlock.openapi_discriminator_mapping
# =>
# {
#   :'after' => :'ScalarCheckAttributeBlock',
#   :'before' => :'ScalarCheckAttributeBlock',
#   :'between' => :'BetweenCheckAttributeBlock',
#   :'contains' => :'ScalarCheckAttributeBlock',
#   :'containsAllOf' => :'ListCheckAttributeBlock',
#   :'containsAtLeast' => :'ListWithCountCheckAttributeBlock',
#   :'containsExactly' => :'ListWithCountCheckAttributeBlock',
#   :'containsNoneOf' => :'ListCheckAttributeBlock',
#   :'containsOneOf' => :'ListCheckAttributeBlock',
#   :'empty' => :'UnaryCheckAttributeBlock',
#   :'endsWith' => :'ScalarCheckAttributeBlock',
#   :'equals' => :'ScalarCheckAttributeBlock',
#   :'exists' => :'UnaryCheckAttributeBlock',
#   :'greaterThan' => :'ScalarCheckAttributeBlock',
#   :'greaterThanOrEqual' => :'ScalarCheckAttributeBlock',
#   :'inCollection' => :'ScalarCheckAttributeBlock',
#   :'isFalse' => :'UnaryCheckAttributeBlock',
#   :'isTrue' => :'UnaryCheckAttributeBlock',
#   :'lessThan' => :'ScalarCheckAttributeBlock',
#   :'lessThanOrEqual' => :'ScalarCheckAttributeBlock',
#   :'matchesRegexp' => :'ScalarCheckAttributeBlock',
#   :'not(contains)' => :'ScalarCheckAttributeBlock',
#   :'not(empty)' => :'UnaryCheckAttributeBlock',
#   :'not(equals)' => :'ScalarCheckAttributeBlock',
#   :'not(exists)' => :'UnaryCheckAttributeBlock',
#   :'not(inCollection)' => :'ScalarCheckAttributeBlock',
#   :'not(oneOf)' => :'ScalarCheckAttributeBlock',
#   :'not(within)' => :'WithinCheckAttributeBlock',
#   :'oneOf' => :'ScalarCheckAttributeBlock',
#   :'startsWith' => :'ScalarCheckAttributeBlock',
#   :'within' => :'WithinCheckAttributeBlock'
# }
```

### build

Find the appropriate object from the `openapi_one_of` list and casts the data into it.

#### Example

```ruby
require 'talon_one_sdk'

TalonOne::CheckAttributeBlock.build(data)
# => #<CheckAttributeBlockBase:0x00007fdd4aab02a0>

TalonOne::CheckAttributeBlock.build(data_that_doesnt_match)
# => nil
```

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **data** | **Mixed** | data to be matched against the list of oneOf items |

#### Return type

- `CheckAttributeBlockBase`
- `nil` (if no type matches)

