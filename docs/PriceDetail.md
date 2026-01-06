# TalonOne::PriceDetail

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **price** | **Float** | The value of this price type. | [optional] |
| **adjustment_context_id** | **String** | The context identifier of the selected price adjustment. | [optional] |
| **adjustment_reference_id** | **String** | The reference identifier of the selected price adjustment for this SKU. | [optional] |
| **adjustment_effective_from** | **Time** | The date and time from which the price adjustment is effective. | [optional] |
| **adjustment_effective_until** | **Time** | The date and time until which the price adjustment is effective. | [optional] |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::PriceDetail.new(
  price: 90,
  adjustment_context_id: summer25,
  adjustment_reference_id: 68851723-e6fa-488f-ace9-112581e6c19b,
  adjustment_effective_from: 2025-05-25T00:00:00Z,
  adjustment_effective_until: 2025-05-30T00:00:00Z
)
```

