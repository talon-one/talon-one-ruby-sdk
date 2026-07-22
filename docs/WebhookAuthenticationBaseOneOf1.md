# TalonOne::WebhookAuthenticationBaseOneOf1

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **name** | **String** | The name of the webhook authentication. | [optional] |
| **type** | **Object** |  | [optional] |
| **data** | [**WebhookAuthenticationDataCustom**](WebhookAuthenticationDataCustom.md) |  | [optional] |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::WebhookAuthenticationBaseOneOf1.new(
  name: My basic auth,
  type: null,
  data: null
)
```

