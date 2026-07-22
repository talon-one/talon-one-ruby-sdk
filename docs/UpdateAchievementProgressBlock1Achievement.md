# TalonOne::UpdateAchievementProgressBlock1Achievement

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** | The ID of the achievement. |  |
| **name** | **String** | The internal name of the achievement used in API requests. |  |
| **title** | **String** | The display name of the achievement in the Campaign Manager. |  |
| **target** | **Float** | The required number of actions or the transactional milestone to complete the achievement. |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::UpdateAchievementProgressBlock1Achievement.new(
  id: 42,
  name: Order50Discount,
  title: 50% off on 50th purchase.,
  target: 50
)
```

