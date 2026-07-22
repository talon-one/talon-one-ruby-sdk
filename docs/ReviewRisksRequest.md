# TalonOne::ReviewRisksRequest

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **risk_ids** | **Array&lt;Integer&gt;** | The IDs of the risks to move to &#x60;In review&#x60; status. |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::ReviewRisksRequest.new(
  risk_ids: [1,2,3]
)
```

