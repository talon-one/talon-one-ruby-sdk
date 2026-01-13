# TalonOne::ReturnedCartItem

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **position** | **Integer** | The index of the cart item in the provided customer session&#39;s &#x60;cartItems&#x60; property. | [optional] |
| **quantity** | **Integer** | Number of cart items to return.  | [optional] |
| **sku** | **String** | The SKU of the cart item in the provided customer session&#39;s &#x60;cartItems&#x60; property. | [optional] |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::ReturnedCartItem.new(
  position: 2,
  quantity: 1,
  sku: SKU1241028
)
```

