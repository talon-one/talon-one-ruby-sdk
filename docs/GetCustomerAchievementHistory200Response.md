# TalonOne::GetCustomerAchievementHistory200Response

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **total_result_size** | **Integer** |  |  |
| **data** | [**Array&lt;AchievementProgress&gt;**](AchievementProgress.md) |  |  |

## Example

```ruby
require 'talon_one'

instance = TalonOne::GetCustomerAchievementHistory200Response.new(
  total_result_size: 1,
  data: null
)
```

