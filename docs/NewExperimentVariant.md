# TalonOne::NewExperimentVariant

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **name** | **String** | The name of this variant. |  |
| **weight** | **Integer** | The percentage split of this variant. For &#x60;random&#x60; assignment, the split must be between 1 and 99 and the sum across all variants must equal 100. Ignored for &#x60;audience&#x60; and &#x60;external&#x60; assignment.  |  |
| **ruleset** | [**NewRuleset**](NewRuleset.md) |  |  |
| **is_primary** | **Boolean** | **Deprecated.** Use &#x60;order&#x60; instead. Indicates whether this is the primary variant. This is computed as &#x60;order &#x3D;&#x3D; 0&#x60;.  | [optional] |
| **order** | **Integer** | The position of this variant in the experiment. The variant with &#x60;order: 0&#x60; is the primary variant. When omitted, the backend assigns order based on the array position.  | [optional] |
| **audience_id** | **Integer** | The ID of the audience this variant targets. Only used when the experiment &#x60;assignmentType&#x60; is &#x60;audience&#x60;.  | [optional] |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::NewExperimentVariant.new(
  name: Variant A,
  weight: 13,
  ruleset: null,
  is_primary: true,
  order: 0,
  audience_id: 55
)
```

