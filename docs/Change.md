# TalonOne::Change

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** | The internal ID of this entity. |  |
| **created** | **Time** | The time this entity was created. |  |
| **user_id** | **Integer** | The ID of the user associated with this entity. |  |
| **application_id** | **Integer** | ID of application associated with change. | [optional] |
| **entity** | **String** | API endpoint on which the change was initiated. |  |
| **old** | **Object** | Resource before the change occurred. | [optional] |
| **new** | **Object** | Resource after the change occurred. | [optional] |
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
  old: {},
  new: {applicationId&quot;&#x3D;359, attributes&quot;&#x3D;{}, campaignGroups&quot;&#x3D;[], created&quot;&#x3D;2022-07-08T13:04:02.972762328Z, description&quot;&#x3D;, features&quot;&#x3D;[referrals, loyalty], id&#x3D;6727},
  management_key_id: 3
)
```

