# TalonOne::AwardDiscountBundleTarget

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **type** | **String** | A target discriminator of type &#x60;bundle&#x60;. |  |
| **name** | **String** | Name of the bundle binding the discount targets. |  |
| **item** | [**AwardDiscountBundleItem**](AwardDiscountBundleItem.md) |  | [optional] |
| **prorated** | **Boolean** | Whether to distribute the discount proportionally across the bundle&#39;s items. | [optional] |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::AwardDiscountBundleTarget.new(
  type: null,
  name: BogoBundle,
  item: null,
  prorated: false
)
```

