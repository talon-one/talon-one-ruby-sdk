# TalonOne::ScimPatchRequest

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **schemas** | **Array&lt;String&gt;** | SCIM schema for the given resource. | [optional] |
| **operations** | [**Array&lt;ScimPatchOperation&gt;**](ScimPatchOperation.md) |  |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::ScimPatchRequest.new(
  schemas: null,
  operations: null
)
```

