# TalonOne::SelectorStep

## Class instance methods

### `openapi_one_of`

Returns the list of classes defined in oneOf.

#### Example

```ruby
require 'talon_one_sdk'

TalonOne::SelectorStep.openapi_one_of
# =>
# [
#   :'FilterAndMapValuesSelectorStep',
#   :'FilterSelectorStep',
#   :'MapSelectorStep',
#   :'ReduceSelectorStep',
#   :'ReverseSelectorStep',
#   :'SelectSelectorStep',
#   :'SortSelectorStep'
# ]
```

### `openapi_discriminator_name`

Returns the discriminator's property name.

#### Example

```ruby
require 'talon_one_sdk'

TalonOne::SelectorStep.openapi_discriminator_name
# => :'type'
```

### `openapi_discriminator_name`

Returns the discriminator's mapping.

#### Example

```ruby
require 'talon_one_sdk'

TalonOne::SelectorStep.openapi_discriminator_mapping
# =>
# {
#   :'filter' => :'FilterSelectorStep',
#   :'filterAndMapValues' => :'FilterAndMapValuesSelectorStep',
#   :'map' => :'MapSelectorStep',
#   :'reduce' => :'ReduceSelectorStep',
#   :'reverse' => :'ReverseSelectorStep',
#   :'select' => :'SelectSelectorStep',
#   :'sort' => :'SortSelectorStep'
# }
```

### build

Find the appropriate object from the `openapi_one_of` list and casts the data into it.

#### Example

```ruby
require 'talon_one_sdk'

TalonOne::SelectorStep.build(data)
# => #<FilterAndMapValuesSelectorStep:0x00007fdd4aab02a0>

TalonOne::SelectorStep.build(data_that_doesnt_match)
# => nil
```

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **data** | **Mixed** | data to be matched against the list of oneOf items |

#### Return type

- `FilterAndMapValuesSelectorStep`
- `FilterSelectorStep`
- `MapSelectorStep`
- `ReduceSelectorStep`
- `ReverseSelectorStep`
- `SelectSelectorStep`
- `SortSelectorStep`
- `nil` (if no type matches)

