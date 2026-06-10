# TalonOne::Change

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** | The internal ID of this entity. |  |
| **created** | **Time** | The time this entity was created. |  |
| **user_id** | **Integer** | The ID of the user associated with this entity. |  |
| **application_id** | **Integer** | ID of application associated with change. | [optional] |
| **entity** | **String** | API endpoint on which the change was initiated. |  |
| **old** | **Object** | Arbitrary properties associated with this campaign. | [optional] |
| **new** | **Object** | Arbitrary properties associated with this campaign. | [optional] |
| **management_key_id** | **Integer** | ID of management key used to perform changes. | [optional] |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::Change.new(
  id: 6,
  created: 2020-06-10T09:05:27.993483Z,
  user_id: 388,
  application_id: 359,
  entity: /v1/applications/359/campaigns/6727,
  old: null,
  new: null,
  management_key_id: 3
)
```

