# TalonOne::GiveawayPoolReference

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** | The unique identifier of the giveaway pool. |  |
| **name** | **String** | The display name of the giveaway pool. | [readonly] |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::GiveawayPoolReference.new(
  id: 42,
  name: Summer Campaign Pool
)
```

