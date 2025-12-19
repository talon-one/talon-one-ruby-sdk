# TalonOne::OutgoingIntegrationCleverTapPolicy

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **base_url** | **String** | The base URL that is based on the region key of your CleverTap account. |  |
| **account_id** | **String** | The CleverTap Project ID. |  |
| **passcode** | **String** | The CleverTap Project passcode. |  |

## Example

```ruby
require 'talon_one'

instance = TalonOne::OutgoingIntegrationCleverTapPolicy.new(
  base_url: your-clevertap-url.com,
  account_id: A9X-7A6-4A6B,
  passcode: ABB-BAF-AWZP
)
```

