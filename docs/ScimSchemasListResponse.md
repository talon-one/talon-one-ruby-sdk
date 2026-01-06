# TalonOne::ScimSchemasListResponse

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **resources** | [**Array&lt;ScimSchemaResource&gt;**](ScimSchemaResource.md) |  |  |
| **schemas** | **Array&lt;String&gt;** | SCIM schema for the given resource. | [optional] |
| **total_results** | **Integer** | Number of total results in the response. | [optional] |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::ScimSchemasListResponse.new(
  resources: null,
  schemas: null,
  total_results: null
)
```

