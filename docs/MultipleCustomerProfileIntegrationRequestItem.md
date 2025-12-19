# TalonOne::MultipleCustomerProfileIntegrationRequestItem

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **attributes** | **Object** | Arbitrary properties associated with this item. | [optional] |
| **integration_id** | **String** | The identifier of this profile, set by your integration layer. It must be unique within the account.  To get the &#x60;integrationId&#x60; of the profile from a &#x60;sessionId&#x60;, use the [Update customer session](https://docs.talon.one/integration-api#operation/updateCustomerSessionV2).  |  |

## Example

```ruby
require 'talon_one'

instance = TalonOne::MultipleCustomerProfileIntegrationRequestItem.new(
  attributes: {Language&#x3D;english, ShippingCountry&#x3D;DE},
  integration_id: R195412
)
```

