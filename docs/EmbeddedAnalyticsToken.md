# TalonOne::EmbeddedAnalyticsToken

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **token** | **String** | JWT for embedded analytics. |  |
| **hostname** | **String** | Base URL of the embedded analytics instance. |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::EmbeddedAnalyticsToken.new(
  token: eyJhbGciOiJSUzI1NiIsInR5cCI6IkpXVCJ9.eyJzdWIiOiJleGFtcGxlLXVzZXIiLCJpc3MiOiJ0YWxvbi5vbmUiLCJpYXQiOjE3NjcyMjU2MDAsImV4cCI6MTc2NzIyOTIwMH0.ZXhhbXBsZS1zaWduYXR1cmUtbm90LXZhbGlk,
  hostname: https://talon-sg.cloud.analyticsprovider.com
)
```

