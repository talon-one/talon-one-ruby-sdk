# TalonOne::OutboundLogRequest

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **method** | **String** | HTTP method of the outbound request. |  |
| **url** | **String** | Target URL of the outbound request. |  |
| **headers** | **Array&lt;String&gt;** | HTTP headers sent with the outbound request. |  |
| **body** | **Hash&lt;String, Object&gt;** | JSON request payload. |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::OutboundLogRequest.new(
  method: POST,
  url: https://example.com/webhook,
  headers: [content-type: application/json],
  body: {ProfileIntegrationID&#x3D;URNGV8294NV, LoyaltyProgramID&#x3D;5, SubledgerID&#x3D;sub-123, Amount&#x3D;10.99, Reason&#x3D;Compensation, TypeOfChange&#x3D;campaign_manager, EmployeeName&#x3D;Franziska Schneider, UserID&#x3D;25, Operation&#x3D;addition, StartDate&#x3D;2023-01-24T14:15:22Z, ExpiryDate&#x3D;2024-01-24T14:15:22Z, SessionIntegrationID&#x3D;cc53e4fa-547f-4f5e-8333-76e05c381f67, NotificationType&#x3D;LoyaltyPointsDeducted, TransactionUUID&#x3D;1a6a7599-2622-4489-9034-5a62da3944e0}
)
```

