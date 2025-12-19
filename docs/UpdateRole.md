# TalonOne::UpdateRole

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **name** | **String** | Name of the role. | [optional] |
| **description** | **String** | Description of the role. | [optional] |
| **acl** | **String** | The &#x60;Access Control List&#x60; json defining the role of the user. This represents the access control on the user level. | [optional] |
| **members** | **Array&lt;Integer&gt;** | An array of user identifiers. | [optional] |

## Example

```ruby
require 'talon_one'

instance = TalonOne::UpdateRole.new(
  name: Campaign Manager,
  description: Manages the campaigns,
  acl: {Role&#x3D;128, Applications&#x3D;null},
  members: [48, 562, 475, 18]
)
```

