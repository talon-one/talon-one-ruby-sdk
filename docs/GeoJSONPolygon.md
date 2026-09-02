# TalonOne::GeoJSONPolygon

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **type** | **String** | The geometry type discriminator. |  |
| **coordinates** | **Array&lt;Array&lt;Array&lt;Float&gt;&gt;&gt;** | The boundaries that make up the shape. Each boundary is a closed loop of longitude and latitude points, where the first and last point are the same. |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::GeoJSONPolygon.new(
  type: null,
  coordinates: [[[13, 52.3], [13.8, 52.3], [13.8, 52.7], [13, 52.7], [13, 52.3]]]
)
```

