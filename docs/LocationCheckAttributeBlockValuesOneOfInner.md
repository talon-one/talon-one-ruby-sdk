# TalonOne::LocationCheckAttributeBlockValuesOneOfInner

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **name** | **String** | A human-readable label for this location. | [optional] |
| **geometry** | [**GeoJSONGeometry**](GeoJSONGeometry.md) |  |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::LocationCheckAttributeBlockValuesOneOfInner.new(
  name: Berlin district,
  geometry: null
)
```

