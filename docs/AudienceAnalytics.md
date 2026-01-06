# TalonOne::AudienceAnalytics

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **audience_id** | **Integer** | The ID of the audience. | [optional] |
| **members_count** | **Integer** | The member count of the audience. | [optional] |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::AudienceAnalytics.new(
  audience_id: 1,
  members_count: 1234
)
```

