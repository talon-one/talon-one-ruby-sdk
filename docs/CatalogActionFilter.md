# TalonOne::CatalogActionFilter

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **attr** | **String** | The name of the attribute to filter on. The attribute must exist in the catalog. For the &#x60;LT&#x60;, &#x60;LE&#x60;, &#x60;GT&#x60;, and &#x60;GE&#x60; comparison operators, the attribute must be of type &#x60;number&#x60;. |  |
| **op** | **String** | The filtering operator. |  |
| **value** | **Object** | The value to filter for. For the &#x60;LT&#x60;, &#x60;LE&#x60;, &#x60;GT&#x60;, and &#x60;GE&#x60; comparison operators, the value must be a number or a numeric string. |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::CatalogActionFilter.new(
  attr: color,
  op: EQ,
  value: blue
)
```

