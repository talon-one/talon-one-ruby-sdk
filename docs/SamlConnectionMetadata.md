# TalonOne::SamlConnectionMetadata

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **name** | **String** | ID of the SAML service. |  |
| **enabled** | **Boolean** | Determines if this SAML connection active. |  |
| **account_id** | **Float** |  |  |
| **metadata_document** | **String** | Identity Provider metadata XML document. |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::SamlConnectionMetadata.new(
  name: null,
  enabled: null,
  account_id: null,
  metadata_document: null
)
```

