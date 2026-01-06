# TalonOne::TierDowngradeNotification

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **total_result_size** | **Integer** |  |  |
| **data** | [**Array&lt;TierDowngradeData&gt;**](TierDowngradeData.md) | The array of tier downgrade notifications. |  |
| **notification_type** | **String** | The type of notification. |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::TierDowngradeNotification.new(
  total_result_size: 1,
  data: null,
  notification_type: null
)
```

