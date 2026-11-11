# TalonOne::MCPOAuthStaticClient

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

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::MCPOAuthStaticClient.new(
  client_id: a3f8c1e2b4d56789,
  client_name: My MCP Integration,
  redirect_uris: [https://example.com/callback, http://localhost:3000/callback],
  created_at: 2026-06-12T10:00:00Z,
  id: 34,
  created_by: 280,
  expiry_date: 2027-01-01T00:00:00Z
)
```

