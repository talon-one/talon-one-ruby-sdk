# TalonOne::LocationCheckAttributeBlock1ValuesOneOfInner

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **name** | **String** | A human-readable label for this location. | [optional] |
| **geometry** | [**GeoJSONGeometry**](GeoJSONGeometry.md) |  |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::LocationCheckAttributeBlock1ValuesOneOfInner.new(
  name: Berlin district,
  geometry: null
)
```

