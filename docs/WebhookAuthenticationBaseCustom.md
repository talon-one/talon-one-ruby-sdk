# TalonOne::WebhookAuthenticationBaseCustom

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **name** | **String** | The name of the webhook authentication. |  |
| **type** | **String** | A webhook authentication discriminator of type &#x60;custom&#x60;. |  |
| **data** | [**WebhookAuthenticationDataCustom**](WebhookAuthenticationDataCustom.md) | The credentials of the webhook authentication. |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::WebhookAuthenticationBaseCustom.new(
  name: My custom auth,
  type: null,
  data: null
)
```

