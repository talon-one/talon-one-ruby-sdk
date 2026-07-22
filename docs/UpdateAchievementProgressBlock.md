# TalonOne::UpdateAchievementProgressBlock

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** | Unique identifier for this block. |  |
| **type** | **String** | Identifies the block variant and determines which additional properties are present in it. |  |
| **tags** | **Array&lt;String&gt;** | Semantic labels attached to this block. | [optional] |
| **operator** | **String** |  |  |
| **value** | **String** | The value to update the progress by. Supports template placeholders (e.g. \&quot;{{$Session.Total / 2}}\&quot;) for dynamic quantities. |  |
| **achievement** | [**UpdateAchievementProgressBlock1Achievement**](UpdateAchievementProgressBlock1Achievement.md) |  |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::UpdateAchievementProgressBlock.new(
  id: a1b2c3d4-e5f6-7890-abcd-ef1234567890,
  type: null,
  tags: null,
  operator: increaseBy,
  value: 10,
  achievement: null
)
```

