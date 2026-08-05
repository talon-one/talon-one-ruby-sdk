# TalonOne::CheckAchievementBlock1Achievement

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** | The ID of the achievement. |  |
| **title** | **String** | The display name for the achievement in the Campaign Manager. |  |
| **name** | **String** | The internal name of the achievement used in API requests. |  |
| **target** | **Float** | The required number of actions or the transactional milestone to complete the achievement. |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::CheckAchievementBlock1Achievement.new(
  id: 42,
  title: 50% off on 50th purchase.,
  name: Order50Discount,
  target: 50
)
```

