# TalonOne::MCPOAuthCompleteResult

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **redirect_url** | **String** | The full redirect URL the browser should be sent to, containing the authorization code and state as query parameters. |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::MCPOAuthCompleteResult.new(
  redirect_url: http://localhost:3000/callback?code&#x3D;abc123&amp;state&#x3D;xyz
)
```

