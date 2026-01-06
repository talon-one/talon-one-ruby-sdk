# TalonOne::IntegrationStoreEntity

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **store_integration_id** | **String** | The integration ID of the store. You choose this ID when you create a store. | [optional] |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::IntegrationStoreEntity.new(
  store_integration_id: STORE-001
)
```

