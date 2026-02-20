# TalonOne::NewExperimentVariant

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **name** | **String** | The name of this variant. |  |
| **weight** | **Integer** | The percentage split of this variant. The sum of all variant percentages must be 100. |  |
| **ruleset** | [**NewRuleset**](NewRuleset.md) |  |  |
| **is_primary** | **Boolean** |  |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::NewExperimentVariant.new(
  name: null,
  weight: 13,
  ruleset: null,
  is_primary: true
)
```

