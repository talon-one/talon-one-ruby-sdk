# TalonOne::WebhookAuthentication

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **name** | **String** | The name of the webhook authentication. |  |
| **type** | **String** |  |  |
| **data** | **Object** |  |  |
| **id** | **Integer** | The internal ID of this entity. |  |
| **created** | **Time** | The time this entity was created. |  |
| **modified** | **Time** | The time this entity was last modified. |  |
| **created_by** | **String** | The name of the user who created the webhook authentication. |  |
| **modified_by** | **String** | The name of the user who last modified the webhook authentication. |  |
| **webhooks** | [**Array&lt;WebhookAuthenticationWebhookRef&gt;**](WebhookAuthenticationWebhookRef.md) |  |  |

## Example

```ruby
require 'talon_one'

instance = TalonOne::WebhookAuthentication.new(
  name: My basic auth,
  type: null,
  data: null,
  id: 6,
  created: 2020-06-10T09:05:27.993483Z,
  modified: 2021-09-12T10:12:42Z,
  created_by: null,
  modified_by: null,
  webhooks: null
)
```

