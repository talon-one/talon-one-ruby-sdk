# TalonOne::ScimUsersListResponse

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **resources** | [**Array&lt;ScimUser&gt;**](ScimUser.md) |  |  |
| **schemas** | **Array&lt;String&gt;** | SCIM schema for the given resource. | [optional] |
| **total_results** | **Integer** | Number of total results in the response. | [optional] |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::ScimUsersListResponse.new(
  resources: null,
  schemas: null,
  total_results: null
)
```

