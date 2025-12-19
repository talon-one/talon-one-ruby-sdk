# TalonOne::GetLoyaltyPrograms200Response

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **total_result_size** | **Integer** |  |  |
| **data** | [**Array&lt;LoyaltyProgram&gt;**](LoyaltyProgram.md) |  |  |

## Example

```ruby
require 'talon_one'

instance = TalonOne::GetLoyaltyPrograms200Response.new(
  total_result_size: 1,
  data: null
)
```

