# TalonOne::OutboundLog

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **uuid** | **String** | UUID of the outbound message. |  |
| **notification_id** | **Integer** | ID of the notification that triggered the outbound message. | [optional] |
| **notification_name** | **String** | Name of the notification that triggered the outbound message. | [optional] |
| **webhook_id** | **Integer** | ID of the webhook that triggered the outbound message. | [optional] |
| **webhook_name** | **String** | Name of the webhook that triggered the outbound message. | [optional] |
| **notification_type** | **String** | Type of notification that triggered the outbound message. |  |
| **application_id** | **Integer** | ID of the Application associated with the outbound message. | [optional] |
| **loyalty_program_id** | **Integer** | ID of the loyalty program associated with the outbound message. | [optional] |
| **request** | [**OutboundLogRequest**](OutboundLogRequest.md) |  | [optional] |
| **created_at** | **Time** | Timestamp when the log was created. |  |
| **processing_time_ms** | **Integer** | Time in milliseconds between sending the outbound request and receiving the response. |  |
| **response** | [**OutboundLogResponse**](OutboundLogResponse.md) |  | [optional] |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::OutboundLog.new(
  uuid: 67e55044-10b1-426f-9247-bb680e5fe0c8,
  notification_id: 1,
  notification_name: Notification name,
  webhook_id: 101,
  webhook_name: My webhook,
  notification_type: CampaignNotification,
  application_id: 1,
  loyalty_program_id: 2,
  request: null,
  created_at: 2026-08-17T14:32:05Z,
  processing_time_ms: 180,
  response: null
)
```

