# TalonOne::WebhookAuthentication

## Class instance methods

### `openapi_one_of`

Returns the list of classes defined in oneOf.

#### Example

```ruby
require 'talon_one_sdk'

TalonOne::WebhookAuthentication.openapi_one_of
# =>
# [
#   :'WebhookAuthenticationBasic',
#   :'WebhookAuthenticationCustom'
# ]
```

### `openapi_discriminator_name`

Returns the discriminator's property name.

#### Example

```ruby
require 'talon_one_sdk'

TalonOne::WebhookAuthentication.openapi_discriminator_name
# => :'type'
```

### `openapi_discriminator_name`

Returns the discriminator's mapping.

#### Example

```ruby
require 'talon_one_sdk'

TalonOne::WebhookAuthentication.openapi_discriminator_mapping
# =>
# {
#   :'basic' => :'WebhookAuthenticationBasic',
#   :'custom' => :'WebhookAuthenticationCustom'
# }
```

### build

Find the appropriate object from the `openapi_one_of` list and casts the data into it.

#### Example

```ruby
require 'talon_one_sdk'

TalonOne::WebhookAuthentication.build(data)
# => #<WebhookAuthenticationBasic:0x00007fdd4aab02a0>

TalonOne::WebhookAuthentication.build(data_that_doesnt_match)
# => nil
```

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **data** | **Mixed** | data to be matched against the list of oneOf items |

#### Return type

- `WebhookAuthenticationBasic`
- `WebhookAuthenticationCustom`
- `nil` (if no type matches)

