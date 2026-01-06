# TalonOne::UpdateCollection

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **description** | **String** | A short description of the purpose of this collection. | [optional] |
| **subscribed_applications_ids** | **Array&lt;Integer&gt;** | A list of the IDs of the Applications where this collection is enabled. | [optional] |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::UpdateCollection.new(
  description: My collection of SKUs,
  subscribed_applications_ids: [1, 2, 3]
)
```

