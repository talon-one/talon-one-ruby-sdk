# TalonOne::WebhookAuthenticationBase

## Class instance methods

### `openapi_one_of`

Returns the list of classes defined in oneOf.

#### Example

```ruby
require 'talon_one_sdk'

TalonOne::WebhookAuthenticationBase.openapi_one_of
# =>
# [
#   :'WebhookAuthenticationBaseBasic',
#   :'WebhookAuthenticationBaseCustom'
# ]
```

### `openapi_discriminator_name`

Returns the discriminator's property name.

#### Example

```ruby
require 'talon_one_sdk'

TalonOne::WebhookAuthenticationBase.openapi_discriminator_name
# => :'type'
```

### `openapi_discriminator_name`

Returns the discriminator's mapping.

#### Example

```ruby
require 'talon_one_sdk'

TalonOne::WebhookAuthenticationBase.openapi_discriminator_mapping
# =>
# {
#   :'basic' => :'WebhookAuthenticationBaseBasic',
#   :'custom' => :'WebhookAuthenticationBaseCustom'
# }
```

### build

Find the appropriate object from the `openapi_one_of` list and casts the data into it.

#### Example

```ruby
require 'talon_one_sdk'

TalonOne::WebhookAuthenticationBase.build(data)
# => #<WebhookAuthenticationBaseBasic:0x00007fdd4aab02a0>

TalonOne::WebhookAuthenticationBase.build(data_that_doesnt_match)
# => nil
```

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **data** | **Mixed** | data to be matched against the list of oneOf items |

#### Return type

- `WebhookAuthenticationBaseBasic`
- `WebhookAuthenticationBaseCustom`
- `nil` (if no type matches)

