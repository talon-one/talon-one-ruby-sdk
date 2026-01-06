# TalonOne::GetApplicationCustomerFriends200Response

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **has_more** | **Boolean** |  | [optional] |
| **total_result_size** | **Integer** |  | [optional] |
| **data** | [**Array&lt;ApplicationReferee&gt;**](ApplicationReferee.md) |  |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::GetApplicationCustomerFriends200Response.new(
  has_more: null,
  total_result_size: 1,
  data: null
)
```

