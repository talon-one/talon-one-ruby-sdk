# TalonOne::LoyaltyMembership

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **joined** | **Time** | The moment in which the loyalty program was joined. | [optional] |
| **loyalty_program_id** | **Integer** | The ID of the loyalty program belonging to this entity. |  |

## Example

```ruby
require 'talon_one'

instance = TalonOne::LoyaltyMembership.new(
  joined: 2012-03-20T14:15:22Z,
  loyalty_program_id: 323414846
)
```

