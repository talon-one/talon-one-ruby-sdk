# TalonOne::PlaceholderDetails

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **name** | **String** | The name of the placeholder. |  |
| **type** | **String** | The type of the value assigned to the placeholder. |  |
| **value** | **Array&lt;Object&gt;** | The current value of the placeholder. |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::PlaceholderDetails.new(
  name: my property,
  type: list string,
  value: [1, sku_value]
)
```

