# TalonOne::ScimServiceProviderConfigResponseFilter

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **max_results** | **Integer** | The maximum number of resources that can be returned in a single filtered query response. | [optional] |
| **supported** | **Boolean** | Indicates whether the SCIM service provider supports filtering operations. | [optional] |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::ScimServiceProviderConfigResponseFilter.new(
  max_results: null,
  supported: null
)
```

