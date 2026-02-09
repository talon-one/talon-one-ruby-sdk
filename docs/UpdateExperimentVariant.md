# TalonOne::UpdateExperimentVariant

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** |  |  |
| **name** | **String** |  |  |
| **ruleset** | [**NewRuleset**](NewRuleset.md) |  |  |
| **weight** | **Integer** |  |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::UpdateExperimentVariant.new(
  id: 10,
  name: Variant A,
  ruleset: null,
  weight: 12
)
```

