# TalonOne::PriceHistoryRequest

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **sku** | **String** | The SKU of the item for which the historical prices are being retrieved. |  |
| **start_date** | **Time** | The start date of the period for which historical prices should be retrieved. |  |
| **end_date** | **Time** | The end date of the period for which historical prices should be retrieved. |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::PriceHistoryRequest.new(
  sku: [sku-124],
  start_date: 2020-11-10T23:00:00Z,
  end_date: 2020-12-10T23:00:00Z
)
```

