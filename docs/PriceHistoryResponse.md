# TalonOne::PriceHistoryResponse

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **sku** | **String** | The SKU of the item for which historical prices should be retrieved. |  |
| **history** | [**Array&lt;History&gt;**](History.md) |  |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::PriceHistoryResponse.new(
  sku: [SKU1241028],
  history: null
)
```

