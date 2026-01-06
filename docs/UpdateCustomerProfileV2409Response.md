# TalonOne::UpdateCustomerProfileV2409Response

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **message** | **String** |  | [optional] |
| **errors** | **Array&lt;Object&gt;** |  | [optional] |
| **status_code** | **Integer** |  | [optional] |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::UpdateCustomerProfileV2409Response.new(
  message: Too many requests are updating this profile at the same time,
  errors: null,
  status_code: 409
)
```

