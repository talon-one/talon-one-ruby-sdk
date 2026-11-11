# TalonOne::WebhookAuthenticationBasic

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **name** | **String** | The name of the webhook authentication. |  |
| **type** | **String** | A webhook authentication discriminator of type &#x60;basic&#x60;. |  |
| **data** | [**WebhookAuthenticationDataBasic**](WebhookAuthenticationDataBasic.md) | The credentials of the webhook authentication. |  |
| **created_by** | **String** | The name of the user who created the webhook authentication. |  |
| **modified_by** | **String** | The name of the user who last modified the webhook authentication. |  |
| **webhooks** | [**Array&lt;WebhookAuthenticationWebhookRef&gt;**](WebhookAuthenticationWebhookRef.md) |  |  |
| **id** | **Integer** | The internal ID of this entity. |  |
| **created** | **Time** | The time this entity was created. |  |
| **modified** | **Time** | The time this entity was last modified. |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::WebhookAuthenticationBasic.new(
  name: My basic auth,
  type: null,
  data: null,
  created_by: null,
  modified_by: null,
  webhooks: null,
  id: 6,
  created: 2020-06-10T09:05:27.993483Z,
  modified: 2021-09-12T10:12:42Z
)
```

