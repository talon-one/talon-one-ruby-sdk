# TalonOne::CustomerProfileSearchQuery

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **attributes** | **Object** | Properties to match against a customer profile. All provided attributes will be exactly matched against profile attributes. | [optional] |
| **integration_ids** | **Array&lt;String&gt;** |  | [optional] |
| **profile_ids** | **Array&lt;Integer&gt;** |  | [optional] |

## Example

```ruby
require 'talon_one'

instance = TalonOne::CustomerProfileSearchQuery.new(
  attributes: null,
  integration_ids: null,
  profile_ids: null
)
```

