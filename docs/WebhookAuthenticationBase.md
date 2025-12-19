# TalonOne::WebhookAuthenticationBase

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **name** | **String** | The name of the webhook authentication. |  |
| **type** | **String** |  |  |
| **data** | **Object** |  |  |

## Example

```ruby
require 'talon_one'

instance = TalonOne::WebhookAuthenticationBase.new(
  name: My basic auth,
  type: null,
  data: null
)
```

