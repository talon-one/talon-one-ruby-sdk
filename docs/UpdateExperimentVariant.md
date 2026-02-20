# TalonOne::UpdateExperimentVariant

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** |  |  |
| **name** | **String** |  |  |
| **ruleset** | [**NewRuleset**](NewRuleset.md) |  |  |
| **weight** | **Integer** | The percentage split of this variant. The sum of all variant percentages must be 100. |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::UpdateExperimentVariant.new(
  id: 10,
  name: Variant A,
  ruleset: null,
  weight: 13
)
```

