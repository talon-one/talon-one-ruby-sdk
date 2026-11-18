# TalonOne::NewDigitalPass

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **loyalty_program_id** | **Integer** | The ID of the associated loyalty program. |  |
| **pass_template_id** | **String** | The ID of the digital pass template used to generate the pass. |  |
| **profile_integration_id** | **String** | The integration ID of the customer profile the pass is issued for. |  |
| **loyalty_card_id** | **String** | The identifier of the loyalty card the pass is issued for.  **Note**: Only applicable for card-based loyalty programs.  | [optional] |
| **platform** | **String** | The wallet platform the pass is generated for. Possible values:  - &#x60;apple&#x60;: The digital pass is generated for Apple Wallet. - &#x60;google&#x60;: The digital pass is generated for Google Wallet.  |  |
| **attributes** | **Hash&lt;String, String&gt;** | A map of placeholder values that you provide to fill in the pass template. Pass templates reference each value as &#x60;CustomerProfile.Attributes.&lt;key&gt;&#x60;.  Each key must start with a letter or an underscore and can contain only letters, digits, and underscores. If the template requires a value that is missing, the request fails with a &#x60;422&#x60; error.  | [optional] |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::NewDigitalPass.new(
  loyalty_program_id: 42,
  pass_template_id: 3fa85f64-5717-4562-b3fc-2c963f66afa6,
  profile_integration_id: 12412412421,
  loyalty_card_id: summer-loyalty-0e2f,
  platform: google,
  attributes: {hm_member_name&#x3D;Jane Doe}
)
```

