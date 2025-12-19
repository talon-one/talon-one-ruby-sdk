# TalonOne::UpdateStore

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **name** | **String** | The name of the store. |  |
| **description** | **String** | The description of the store. |  |
| **attributes** | **Object** | The attributes of the store. | [optional] |

## Example

```ruby
require 'talon_one'

instance = TalonOne::UpdateStore.new(
  name: South US store,
  description: This is the description of the store in south US.,
  attributes: {country&#x3D;USA, code&#x3D;1234}
)
```

