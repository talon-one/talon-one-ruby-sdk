# TalonOne::NewStore

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **name** | **String** | The name of the store. |  |
| **description** | **String** | The description of the store. |  |
| **attributes** | **Object** | The attributes of the store. | [optional] |
| **integration_id** | **String** | The integration ID of the store. You choose this ID when you create a store.  **Note**: You cannot edit the &#x60;integrationId&#x60; after the store has been created.  |  |

## Example

```ruby
require 'talon_one'

instance = TalonOne::NewStore.new(
  name: South US store,
  description: This is the description of the store in south US.,
  attributes: {country&#x3D;USA, code&#x3D;1234},
  integration_id: STORE-001
)
```

