# TalonOne::NewCampaignCollection

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **description** | **String** | A short description of the purpose of this collection. | [optional] |
| **name** | **String** | The name of this collection. |  |

## Example

```ruby
require 'talon_one'

instance = TalonOne::NewCampaignCollection.new(
  description: My collection of SKUs,
  name: My collection
)
```

