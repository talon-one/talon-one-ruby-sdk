# TalonOne::DigitalPass

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **pass_id** | **String** | The ID of the generated digital pass. |  |
| **pass_template_id** | **String** | The ID of the digital pass template used to generate the pass. |  |
| **status** | **String** | The status of the digital pass.  &#x60;created&#x60; indicates that the pass was generated and is ready to be added to a wallet.  |  |
| **pass_url** | **String** | The URL you can use to let the customer add the digital pass to their wallet.  **Note**: For Google Wallet, the URL is valid for 30 days. After 30 days, create the pass again to get a new URL.  |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::DigitalPass.new(
  pass_id: 9c3f1a2b-4d5e-4f60-8a71-b2c3d4e5f607,
  pass_template_id: 3fa85f64-5717-4562-b3fc-2c963f66afa6,
  status: created,
  pass_url: https://wallet.example.com/passes/9c3f1a2b-4d5e-4f60-8a71-b2c3d4e5f607
)
```

