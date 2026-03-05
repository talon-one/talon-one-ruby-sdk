# TalonOne::IntegrationHubConfig

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **integration_hub_url** | **String** | The url used to integrate the IntegrationHub Marketplace. |  |
| **access_token** | **String** | Access token used to authenticate a user in Talon.One. |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::IntegrationHubConfig.new(
  integration_hub_url: https://hub.talon.farm/,
  access_token: eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9
)
```

