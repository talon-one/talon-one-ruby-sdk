# TalonOne::GeoJSONGeometryCollection

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **type** | **String** | The geometry type discriminator. |  |
| **geometries** | [**Array&lt;GeoJSONGeometry&gt;**](GeoJSONGeometry.md) | The shapes contained in this group. |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::GeoJSONGeometryCollection.new(
  type: null,
  geometries: null
)
```

