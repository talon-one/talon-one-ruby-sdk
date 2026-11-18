# TalonOne::OutboundLogsDataInner

## Class instance methods

### `openapi_one_of`

Returns the list of classes defined in oneOf.

#### Example

```ruby
require 'talon_one_sdk'

TalonOne::OutboundLogsDataInner.openapi_one_of
# =>
# [
#   :'OutboundLogStreamErrorEntry',
#   :'OutboundLogStreamLogEntry'
# ]
```

### `openapi_discriminator_name`

Returns the discriminator's property name.

#### Example

```ruby
require 'talon_one_sdk'

TalonOne::OutboundLogsDataInner.openapi_discriminator_name
# => :'type'
```

### `openapi_discriminator_name`

Returns the discriminator's mapping.

#### Example

```ruby
require 'talon_one_sdk'

TalonOne::OutboundLogsDataInner.openapi_discriminator_mapping
# =>
# {
#   :'error' => :'OutboundLogStreamErrorEntry',
#   :'log' => :'OutboundLogStreamLogEntry'
# }
```

### build

Find the appropriate object from the `openapi_one_of` list and casts the data into it.

#### Example

```ruby
require 'talon_one_sdk'

TalonOne::OutboundLogsDataInner.build(data)
# => #<OutboundLogStreamErrorEntry:0x00007fdd4aab02a0>

TalonOne::OutboundLogsDataInner.build(data_that_doesnt_match)
# => nil
```

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **data** | **Mixed** | data to be matched against the list of oneOf items |

#### Return type

- `OutboundLogStreamErrorEntry`
- `OutboundLogStreamLogEntry`
- `nil` (if no type matches)

