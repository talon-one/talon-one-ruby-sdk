# TalonOne::AchievementProgress

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **status** | **String** | The status of the achievement. |  |
| **progress** | **Float** | The current progress of the customer in the achievement. |  |
| **start_date** | **Time** | Timestamp at which the customer started the achievement. | [optional] |
| **completion_date** | **Time** | Timestamp at which point the customer completed the achievement. | [optional] |
| **end_date** | **Time** | Timestamp at which point the achievement ends and resets for the customer. | [optional] |

## Example

```ruby
require 'talon_one'

instance = TalonOne::AchievementProgress.new(
  status: completed,
  progress: 10,
  start_date: 2024-01-01T15:04:05Z07:00,
  completion_date: 2024-01-15T15:04:05Z07:00,
  end_date: 2024-02-01T15:04:05Z07:00
)
```

