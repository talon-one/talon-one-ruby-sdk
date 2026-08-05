# TalonOne::CheckBudgetBlock

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** | Unique identifier for this block. |  |
| **type** | **String** | Identifies the block variant and determines which additional properties are present in it. |  |
| **tags** | **Array&lt;String&gt;** | Semantic labels attached to this block. | [optional] |
| **operator** | **String** | The comparison operator applied to the limit. &#x60;available&#x60; checks if there is budget available for a given limitable action; &#x60;enoughFor&#x60; checks if the available budget meets or exceeds a specific value limit. |  |
| **action** | **String** | The limitable action to check. |  |
| **value** | **Float** | The value to check against when using the &#x60;enoughFor&#x60; operator. | [optional] |
| **on_failure** | [**Array&lt;PromotionBlock&gt;**](PromotionBlock.md) | Promotion blocks evaluated when this block fails or returns false. | [optional] |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::CheckBudgetBlock.new(
  id: a1b2c3d4-e5f6-7890-abcd-ef1234567890,
  type: null,
  tags: null,
  operator: available,
  action: setDiscount,
  value: 5,
  on_failure: null
)
```

