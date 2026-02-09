# TalonOne::NewExperimentVariant

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **name** | **String** | The name of this variant. |  |
| **weight** | **Integer** |  | [optional] |
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

