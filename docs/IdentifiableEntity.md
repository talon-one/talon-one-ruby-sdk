# TalonOne::IdentifiableEntity

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** | Unique ID for this entity. Not to be confused with the Integration ID, which is set by your integration layer and used in most endpoints. |  |

## Example

```ruby
require 'talon_one'

instance = TalonOne::IdentifiableEntity.new(
  id: 6
)
```

