# TalonOne::ListAllRolesV2200Response

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **total_result_size** | **Integer** | The total number of roles returned. |  |
| **data** | [**Array&lt;RoleV2&gt;**](RoleV2.md) | The list of roles. |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::ListAllRolesV2200Response.new(
  total_result_size: 1,
  data: null
)
```

