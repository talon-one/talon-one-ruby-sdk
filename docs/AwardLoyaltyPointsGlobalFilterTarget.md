# TalonOne::AwardLoyaltyPointsGlobalFilterTarget

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **type** | **String** | A target discriminator of type &#x60;globalFilter&#x60;. |  |
| **name** | **String** | The name of the Application-level cart item filter the points target. |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::AwardLoyaltyPointsGlobalFilterTarget.new(
  type: null,
  name: PremiumItems
)
```

