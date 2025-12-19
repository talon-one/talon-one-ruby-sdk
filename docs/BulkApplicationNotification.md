# TalonOne::BulkApplicationNotification

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **total_result_size** | **Integer** |  |  |
| **data** | [**Array&lt;ApplicationNotification&gt;**](ApplicationNotification.md) |  |  |

## Example

```ruby
require 'talon_one'

instance = TalonOne::BulkApplicationNotification.new(
  total_result_size: 1,
  data: null
)
```

