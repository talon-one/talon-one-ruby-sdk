# TalonOne::NewRole

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **name** | **String** | Name of the role. |  |
| **description** | **String** | Description of the role. | [optional] |
| **acl** | **String** | The &#x60;Access Control List&#x60; json defining the role of the user. This represents the access control on the user level. |  |
| **members** | **Array&lt;Integer&gt;** | An array of user identifiers. |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::NewRole.new(
  name: Campaign Manager,
  description: Manages the campaigns,
  acl: {Role&#x3D;128, Applications&#x3D;null},
  members: [48, 562, 475, 18]
)
```

