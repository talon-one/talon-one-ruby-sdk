# TalonOne::NewApplicationCIF

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **name** | **String** | The name of the Application cart item filter used in API requests. |  |
| **description** | **String** | A short description of the Application cart item filter. | [optional] |
| **active_expression_id** | **Integer** | The ID of the expression that the Application cart item filter uses. | [optional] |
| **modified_by** | **Integer** | The ID of the user who last updated the Application cart item filter. | [optional] |
| **created_by** | **Integer** | The ID of the user who created the Application cart item filter. | [optional] |
| **modified** | **Time** | Timestamp of the most recent update to the Application cart item filter. | [optional] |

## Example

```ruby
require 'talon_one'

instance = TalonOne::NewApplicationCIF.new(
  name: Filter items by product,
  description: This filter allows filtering by shoes,
  active_expression_id: 1,
  modified_by: 334,
  created_by: 216,
  modified: null
)
```

