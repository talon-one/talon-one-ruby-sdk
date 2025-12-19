# TalonOne::CatalogSyncRequest

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **actions** | **Array&lt;Object&gt;** |  |  |
| **version** | **Integer** | The version number of the catalog to apply the actions on. | [optional] |

## Example

```ruby
require 'talon_one'

instance = TalonOne::CatalogSyncRequest.new(
  actions: null,
  version: 244
)
```

