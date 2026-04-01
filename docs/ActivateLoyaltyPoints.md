# TalonOne::ActivateLoyaltyPoints

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **transaction_uuids** | **Array&lt;String&gt;** | An array of transaction UUIDs used to activate specific pending point transactions.  If provided, do not include the &#x60;sessionId&#x60; parameter.  | [optional] |
| **session_id** | **String** | The ID of the session containing the pending point transactions to activate.  If provided, do not include the &#x60;transactionUUIDs&#x60; parameter.  | [optional] |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::ActivateLoyaltyPoints.new(
  transaction_uuids: [8f1a8d7c-9c3e-4a5e-9f0d-2c5f7a3b1cde],
  session_id: ac08cc3c43470426591ad75b2d685ec04_v2
)
```

