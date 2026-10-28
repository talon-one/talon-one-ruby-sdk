# TalonOne::UpdateLoyaltyCard

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **status** | **String** | Status of the loyalty card. Can be &#x60;active&#x60; or &#x60;inactive&#x60;.  |  |
| **block_reason** | **String** | Reason for transferring and blocking the loyalty card.  | [optional] |
| **attributes** | **Object** | Set values for the [custom attributes](https://docs.talon.one/docs/dev/concepts/attributes#custom-attributes) of a loyalty card. These attributes must be created in the Campaign Manager before their values can be updated through this endpoint.  | [optional] |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::UpdateLoyaltyCard.new(
  status: active,
  block_reason: Current card lost. Customer needs a new card.,
  attributes: {PIN&#x3D;1234, Language&#x3D;DE}
)
```

