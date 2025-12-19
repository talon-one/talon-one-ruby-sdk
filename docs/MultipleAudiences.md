# TalonOne::MultipleAudiences

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **account_id** | **Integer** | The ID of the account that owns this entity. |  |
| **audiences** | [**Array&lt;MultipleAudiencesItem&gt;**](MultipleAudiencesItem.md) |  |  |

## Example

```ruby
require 'talon_one'

instance = TalonOne::MultipleAudiences.new(
  account_id: 3886,
  audiences: null
)
```

