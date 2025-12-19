# TalonOne::LoyaltyProgramEntity

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **program_id** | **Integer** | The ID of the loyalty program that owns this entity. |  |
| **program_name** | **String** | The integration name of the loyalty program that owns this entity. | [optional] |
| **program_title** | **String** | The Campaign Manager-displayed name of the loyalty program that owns this entity. | [optional] |

## Example

```ruby
require 'talon_one'

instance = TalonOne::LoyaltyProgramEntity.new(
  program_id: 125,
  program_name: Loyalty_program,
  program_title: Loyalty program
)
```

