# TalonOne::ListCatalogItems200Response

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **has_more** | **Boolean** |  | [optional] |
| **total_result_size** | **Integer** |  | [optional] |
| **data** | [**Array&lt;CatalogItem&gt;**](CatalogItem.md) |  |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::ListCatalogItems200Response.new(
  has_more: null,
  total_result_size: 1,
  data: null
)
```

