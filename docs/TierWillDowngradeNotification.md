# TalonOne::TierWillDowngradeNotification

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **total_result_size** | **Integer** |  |  |
| **data** | [**Array&lt;TierWillDowngradeData&gt;**](TierWillDowngradeData.md) | The array of upcoming tier downgrade notifications. |  |
| **notification_type** | **String** | The type of notification. |  |

## Example

```ruby
require 'talon_one'

instance = TalonOne::TierWillDowngradeNotification.new(
  total_result_size: 1,
  data: null,
  notification_type: null
)
```

