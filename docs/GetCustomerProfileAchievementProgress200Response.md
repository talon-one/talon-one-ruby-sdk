# TalonOne::GetCustomerProfileAchievementProgress200Response

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **has_more** | **Boolean** |  |  |
| **data** | [**Array&lt;AchievementProgressWithDefinition&gt;**](AchievementProgressWithDefinition.md) |  |  |

## Example

```ruby
require 'talon_one'

instance = TalonOne::GetCustomerProfileAchievementProgress200Response.new(
  has_more: true,
  data: null
)
```

