# TalonOne::OutgoingIntegrationBrazePolicy

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **base_url** | **String** | The base URL of your Braze deployment. |  |
| **api_key** | **String** | The API key of your Braze deployment. |  |

## Example

```ruby
require 'talon_one'

instance = TalonOne::OutgoingIntegrationBrazePolicy.new(
  base_url: your-braze-url.com,
  api_key: Your-REST-API-Key
)
```

