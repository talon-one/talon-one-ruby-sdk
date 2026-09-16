# TalonOne::AwardLoyaltyPointsSelectorTarget

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **type** | **String** | A target discriminator of type &#x60;selector&#x60;. |  |
| **name** | **String** | The name of the selector binding the points target. |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::AwardLoyaltyPointsSelectorTarget.new(
  type: null,
  name: ElectronicsItems
)
```

