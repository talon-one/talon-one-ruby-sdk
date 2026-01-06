# TalonOne::GetChanges200Response

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **total_result_size** | **Integer** |  | [optional] |
| **has_more** | **Boolean** |  | [optional] |
| **data** | [**Array&lt;Change&gt;**](Change.md) |  |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::GetChanges200Response.new(
  total_result_size: 1,
  has_more: null,
  data: null
)
```

