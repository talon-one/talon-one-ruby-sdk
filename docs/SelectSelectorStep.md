# TalonOne::SelectSelectorStep

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **type** | **String** | A step discriminator of type &#x60;select&#x60;. |  |
| **operator** | **String** | The selection operator applied to the items. |  |
| **from** | [**SelectSelectorStepFrom**](SelectSelectorStepFrom.md) |  | [optional] |
| **to** | **Integer** | The end index for the &#x60;between&#x60; operator. The item at this index is not included. | [optional] |
| **count** | **Integer** | The maximum number of items to select for the &#x60;many&#x60; operator. | [optional] |
| **index** | **Integer** | The exact position of the item to select for the &#x60;one&#x60; operator. | [optional] |
| **partial** | **Boolean** | Indicates if the step returns fewer items than requested when the source list is shorter than the range needs. Always &#x60;true&#x60; for the &#x60;many&#x60; and &#x60;between&#x60; operators; not present for &#x60;one&#x60;, which fails instead of returning a partial result. | [optional] |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::SelectSelectorStep.new(
  type: select,
  operator: many,
  from: null,
  to: 7,
  count: 5,
  index: 0,
  partial: true
)
```

