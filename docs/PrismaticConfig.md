# TalonOne::PrismaticConfig

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **prismatic_url** | **String** | The url used to integrate the Prismatic Marketplace. |  |
| **access_token** | **String** | Access token used to authenticate a user in Talon.One. |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::PrismaticConfig.new(
  prismatic_url: https://app.eu-west-1.prismatic.io/,
  access_token: eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9
)
```

