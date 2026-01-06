# TalonOne::AudienceReference

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **integration_id** | **String** | The ID of this audience in the third-party integration. | [optional] |
| **id** | **Integer** | The ID of the audience. |  |
| **integration** | **String** | The third-party integration of the audience. | [optional] |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::AudienceReference.new(
  integration_id: 382370BKDB946,
  id: null,
  integration: null
)
```

