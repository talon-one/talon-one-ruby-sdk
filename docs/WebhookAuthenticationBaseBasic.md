# TalonOne::WebhookAuthenticationBaseBasic

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **name** | **String** | The name of the webhook authentication. |  |
| **type** | **String** | A webhook authentication discriminator of type &#x60;basic&#x60;. |  |
| **data** | [**WebhookAuthenticationDataBasic**](WebhookAuthenticationDataBasic.md) | The credentials of the webhook authentication. |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::WebhookAuthenticationBaseBasic.new(
  name: My basic auth,
  type: null,
  data: null
)
```

