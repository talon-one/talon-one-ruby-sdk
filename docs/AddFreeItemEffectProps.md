# TalonOne::AddFreeItemEffectProps

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **sku** | **String** | SKU of the item that needs to be added. |  |
| **name** | **String** | The name / description of the effect |  |
| **desired_quantity** | **Integer** | The original quantity in case a partial reward was applied. | [optional] |

## Example

```ruby
require 'talon_one'

instance = TalonOne::AddFreeItemEffectProps.new(
  sku: SKU1241028,
  name: null,
  desired_quantity: null
)
```

