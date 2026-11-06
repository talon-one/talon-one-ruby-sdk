# TalonOne::ExperimentVariant

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** | The internal ID of this entity. |  |
| **created** | **Time** | The time this entity was created. |  |
| **name** | **String** |  |  |
| **experiment_id** | **Integer** |  | [optional] |
| **ruleset** | [**Ruleset**](Ruleset.md) |  | [optional] |
| **weight** | **Integer** |  | [optional] |
| **is_primary** | **Boolean** | **Deprecated.** Use &#x60;order&#x60; instead. Indicates whether this is the primary variant. This is computed as &#x60;order &#x3D;&#x3D; 0&#x60;.  | [optional] |
| **order** | **Integer** | The position of this variant in the experiment. The variant with &#x60;order: 0&#x60; is the primary variant.  | [optional] |
| **audience_id** | **Integer** | The ID of the audience this variant targets. Only used when the experiment &#x60;assignmentType&#x60; is &#x60;audience&#x60;.  | [optional] |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::ExperimentVariant.new(
  id: 6,
  created: 2020-06-10T09:05:27.993483Z,
  name: Variant A,
  experiment_id: 10,
  ruleset: null,
  weight: 12,
  is_primary: true,
  order: 0,
  audience_id: 55
)
```

