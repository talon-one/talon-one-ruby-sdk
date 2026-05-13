# TalonOne::FeatureFlagUpdate

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **name** | **String** | The name of the feature flag. |  |
| **value** | **String** | The value of the feature flag. |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::FeatureFlagUpdate.new(
  name: canCreateCampaignFromTemplate,
  value: true
)
```

