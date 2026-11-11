# TalonOne::NewMCPOAuthStaticClient

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **client_name** | **String** | Human-readable name for the OAuth2 client. |  |
| **redirect_uris** | **Array&lt;String&gt;** | List of allowed redirect URIs for the authorization code flow. At least one URI is required. |  |
| **expiry_date** | **Time** | The date the client credentials expire. | [optional] |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::NewMCPOAuthStaticClient.new(
  client_name: My MCP Integration,
  redirect_uris: [http://localhost:3000/callback],
  expiry_date: 2027-01-01T00:00:00Z
)
```

