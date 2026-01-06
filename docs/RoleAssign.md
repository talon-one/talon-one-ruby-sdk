# TalonOne::RoleAssign

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **users** | **Array&lt;Integer&gt;** | An array of user IDs. |  |
| **roles** | **Array&lt;Integer&gt;** | An array of role IDs. |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::RoleAssign.new(
  users: [48, 562, 475, 18],
  roles: [128, 147]
)
```

