# TalonOne::MultipleAudiencesItem

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** | The internal ID of this entity. |  |
| **created** | **Time** | The time this entity was created. |  |
| **name** | **String** | The human-friendly display name for this audience. |  |
| **integration_id** | **String** | The ID of this audience in the third-party integration. | [optional] |
| **status** | **String** | Indicates whether the audience is new, updated or unmodified by the request.  |  |

## Example

```ruby
require 'talon_one'

instance = TalonOne::MultipleAudiencesItem.new(
  id: 6,
  created: 2020-06-10T09:05:27.993483Z,
  name: Travel audience,
  integration_id: 382370BKDB946,
  status: new
)
```

