# TalonOne::CreateManagementKey

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **name** | **String** | Name for management key. |  |
| **expiry_date** | **Time** | The date the management key expires. |  |
| **endpoints** | [**Array&lt;Endpoint&gt;**](Endpoint.md) | The list of endpoints that can be accessed with the key |  |
| **allowed_application_ids** | **Array&lt;Integer&gt;** | A list of Application IDs that you can access with the management key. An empty or missing list means the management key can be used for all Applications in the account.  | [optional] |

## Example

```ruby
require 'talon_one'

instance = TalonOne::CreateManagementKey.new(
  name: My generated key,
  expiry_date: 2023-08-24T14:00:00Z,
  endpoints: null,
  allowed_application_ids: [1, 2, 3]
)
```

