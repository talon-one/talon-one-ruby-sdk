# TalonOne::AnalyticsProduct

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** | The ID of the product. |  |
| **name** | **String** | The name of the product. |  |
| **catalog_id** | **Integer** | The ID of the catalog. You can find the ID in the Campaign Manager in **Account** &gt; **Tools** &gt; **Cart item catalogs**.  |  |
| **units_sold** | [**AnalyticsDataPointWithTrend**](AnalyticsDataPointWithTrend.md) | The number of times the product or SKU was purchased. | [optional] |

## Example

```ruby
require 'talon_one'

instance = TalonOne::AnalyticsProduct.new(
  id: 1,
  name: MyProduct,
  catalog_id: 1,
  units_sold: null
)
```

