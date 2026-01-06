# TalonOne::GetCustomerAchievements200Response

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **total_result_size** | **Integer** |  |  |
| **data** | [**Array&lt;AchievementStatusEntry&gt;**](AchievementStatusEntry.md) |  |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::GetCustomerAchievements200Response.new(
  total_result_size: 1,
  data: null
)
```

