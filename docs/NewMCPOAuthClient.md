# TalonOne::NewMCPOAuthClient

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **client_name** | **String** | Human-readable name for the OAuth2 client. |  |
| **redirect_uris** | **Array&lt;String&gt;** | List of allowed redirect URIs for the authorization code flow. At least one URI is required. |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::NewMCPOAuthClient.new(
  client_name: My MCP Integration,
  redirect_uris: [&quot;http://localhost:3000/callback&quot;]
)
```

