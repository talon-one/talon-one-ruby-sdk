# TalonOne::UpdateCustomerSessionV2409Response

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **message** | **String** |  | [optional] |
| **errors** | **Array&lt;Object&gt;** |  | [optional] |
| **status_code** | **Integer** |  | [optional] |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::UpdateCustomerSessionV2409Response.new(
  message: Too many requests are updating this session at the same time,
  errors: null,
  status_code: 409
)
```

