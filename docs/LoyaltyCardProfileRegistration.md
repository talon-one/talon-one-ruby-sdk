# TalonOne::LoyaltyCardProfileRegistration

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **integration_id** | **String** | Integration ID of the customer profile linked to the card. |  |
| **timestamp** | **Time** | Timestamp the customer profile was linked to the card. |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::LoyaltyCardProfileRegistration.new(
  integration_id: R195412,
  timestamp: 2021-09-12T10:12:42Z
)
```

