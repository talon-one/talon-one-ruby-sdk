# TalonOne::TalangAttributeVisibility

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **invisible** | **Array&lt;String&gt;** | List of attribute names to hide in the UI. | [optional] |
| **visible** | **Array&lt;String&gt;** | List of attribute names to show in the UI. | [optional] |

## Example

```ruby
require 'talon_one'

instance = TalonOne::TalangAttributeVisibility.new(
  invisible: null,
  visible: null
)
```

