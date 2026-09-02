# TalonOne::GeoJSONPoint

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **type** | **String** | The geometry type discriminator. |  |
| **coordinates** | **Array&lt;Float&gt;** | The longitude and latitude coordinates of the point, optionally followed by altitude. |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::GeoJSONPoint.new(
  type: null,
  coordinates: [13.405, 52.52]
)
```

