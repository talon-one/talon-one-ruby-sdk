# TalonOne::NewMultipleAudiencesItem

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **name** | **String** | The human-friendly display name for this audience. |  |
| **integration_id** | **String** | The ID of this audience in the third-party integration. | [optional] |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::NewMultipleAudiencesItem.new(
  name: Travel audience,
  integration_id: 382370BKDB946
)
```

