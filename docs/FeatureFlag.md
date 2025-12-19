# TalonOne::FeatureFlag

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **name** | **String** | The name of the feature flag. |  |
| **value** | **String** | The value of the feature flag. |  |
| **created** | **Time** | The time this entity was last created. | [optional] |
| **modified** | **Time** | The time this entity was last modified. | [optional] |

## Example

```ruby
require 'talon_one'

instance = TalonOne::FeatureFlag.new(
  name: canCreateCampaignFromTemplate,
  value: true,
  created: 2021-09-22T12:24:14.956203Z,
  modified: 2021-09-25T10:34:12.956203Z
)
```

