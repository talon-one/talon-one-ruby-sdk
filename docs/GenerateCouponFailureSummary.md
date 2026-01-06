# TalonOne::GenerateCouponFailureSummary

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **event_id** | **Integer** | The ID of the event. |  |
| **language** | **String** | The language the summary will be generated in. | [optional] |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::GenerateCouponFailureSummary.new(
  event_id: null,
  language: en
)
```

