# TalonOne::ListAccountCollections200Response

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **has_more** | **Boolean** |  | [optional] |
| **total_result_size** | **Integer** |  | [optional] |
| **data** | [**Array&lt;CollectionWithoutPayload&gt;**](CollectionWithoutPayload.md) |  |  |

## Example

```ruby
require 'talon_one'

instance = TalonOne::ListAccountCollections200Response.new(
  has_more: null,
  total_result_size: 1,
  data: null
)
```

