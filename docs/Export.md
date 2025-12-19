# TalonOne::Export

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** | The internal ID of this entity. |  |
| **created** | **Time** | The time this entity was created. |  |
| **account_id** | **Integer** | The ID of the account that owns this entity. |  |
| **user_id** | **Integer** | The ID of the user associated with this entity. |  |
| **entity** | **String** | The name of the entity that was exported. |  |
| **filter** | **Object** | Map of keys and values that were used to filter the exported rows. |  |

## Example

```ruby
require 'talon_one'

instance = TalonOne::Export.new(
  id: 6,
  created: 2020-06-10T09:05:27.993483Z,
  account_id: 3886,
  user_id: 388,
  entity: null,
  filter: null
)
```

