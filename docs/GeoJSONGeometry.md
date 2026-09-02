# TalonOne::GeoJSONGeometry

## Class instance methods

### `openapi_one_of`

Returns the list of classes defined in oneOf.

#### Example

```ruby
require 'talon_one_sdk'

TalonOne::GeoJSONGeometry.openapi_one_of
# =>
# [
#   :'GeoJSONGeometryCollection',
#   :'GeoJSONMultiPolygon',
#   :'GeoJSONPoint',
#   :'GeoJSONPolygon'
# ]
```

### `openapi_discriminator_name`

Returns the discriminator's property name.

#### Example

```ruby
require 'talon_one_sdk'

TalonOne::GeoJSONGeometry.openapi_discriminator_name
# => :'type'
```

### `openapi_discriminator_name`

Returns the discriminator's mapping.

#### Example

```ruby
require 'talon_one_sdk'

TalonOne::GeoJSONGeometry.openapi_discriminator_mapping
# =>
# {
#   :'GeometryCollection' => :'GeoJSONGeometryCollection',
#   :'MultiPolygon' => :'GeoJSONMultiPolygon',
#   :'Point' => :'GeoJSONPoint',
#   :'Polygon' => :'GeoJSONPolygon'
# }
```

### build

Find the appropriate object from the `openapi_one_of` list and casts the data into it.

#### Example

```ruby
require 'talon_one_sdk'

TalonOne::GeoJSONGeometry.build(data)
# => #<GeoJSONGeometryCollection:0x00007fdd4aab02a0>

TalonOne::GeoJSONGeometry.build(data_that_doesnt_match)
# => nil
```

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **data** | **Mixed** | data to be matched against the list of oneOf items |

#### Return type

- `GeoJSONGeometryCollection`
- `GeoJSONMultiPolygon`
- `GeoJSONPoint`
- `GeoJSONPolygon`
- `nil` (if no type matches)

