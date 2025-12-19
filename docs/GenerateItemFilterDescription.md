# TalonOne::GenerateItemFilterDescription

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **item_filter** | **Array&lt;Object&gt;** | An array of item filter Talang expressions. |  |

## Example

```ruby
require 'talon_one'

instance = TalonOne::GenerateItemFilterDescription.new(
  item_filter: [&quot;filter&quot;,[&quot;.&quot;,&quot;Session&quot;,&quot;CartItems&quot;],[[&quot;Item&quot;],[&quot;catch&quot;,false,[&quot;and&quot;,[&quot;!&#x3D;&quot;,[&quot;.&quot;,&quot;Item&quot;,&quot;Attributes&quot;,&quot;c_productType&quot;],&quot;egiftcard&quot;]]]]]
)
```

