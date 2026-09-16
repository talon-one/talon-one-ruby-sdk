# TalonOne::RoleV2PermissionSet

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **name** | **String** | Name of the permission set. |  |
| **logical_operations** | **Array&lt;String&gt;** | List of logical operations in the permission set.  |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::RoleV2PermissionSet.new(
  name: Campaign manager permission set,
  logical_operations: [createCampaignOperations, getCampaignOperations, deleteCampaignOperations]
)
```

