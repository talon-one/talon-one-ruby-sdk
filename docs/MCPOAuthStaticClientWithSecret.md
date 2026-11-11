# TalonOne::MCPOAuthStaticClientWithSecret

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **client_id** | **String** | Unique identifier for the OAuth2 client. |  |
| **client_name** | **String** | Human-readable name for the OAuth2 client. |  |
| **redirect_uris** | **Array&lt;String&gt;** | List of allowed redirect URIs for the authorization code flow. |  |
| **created_at** | **Time** | Timestamp of when the client was registered. |  |
| **id** | **Integer** | Numeric ID of the OAuth client, used to delete it. |  |
| **created_by** | **Integer** | ID of the user who created the client. |  |
| **expiry_date** | **Time** | The date the client credentials expire. | [optional] |
| **client_secret** | **String** | The generated client secret. Only returned once on creation. |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::MCPOAuthStaticClientWithSecret.new(
  client_id: a3f8c1e2b4d56789,
  client_name: My MCP Integration,
  redirect_uris: [https://example.com/callback, http://localhost:3000/callback],
  created_at: 2026-06-12T10:00:00Z,
  id: 34,
  created_by: 280,
  expiry_date: 2027-01-01T00:00:00Z,
  client_secret: 7b1f0c9d8e2a4f6b1c3d5e7f9a0b2c4d6e8f0a1b3c5d7e9f1a2b4c6d8e0f2a4b
)
```

