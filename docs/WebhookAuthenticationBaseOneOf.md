# TalonOne::WebhookAuthenticationBaseOneOf

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **name** | **String** | The name of the webhook authentication. | [optional] |
| **type** | **Object** |  | [optional] |
| **data** | [**WebhookAuthenticationDataBasic**](WebhookAuthenticationDataBasic.md) |  | [optional] |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::WebhookAuthenticationBaseOneOf.new(
  name: My basic auth,
  type: null,
  data: null
)
```

