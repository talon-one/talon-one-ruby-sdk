# TalonOne::LoyaltyCardBatch

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **number_of_cards** | **Integer** | Number of loyalty cards in the batch. |  |
| **batch_id** | **String** | ID of the loyalty card batch. | [optional] |
| **status** | **String** | Status of the loyalty cards in the batch. | [optional][default to &#39;active&#39;] |
| **attributes** | **Object** | Set values for the [custom attributes](https://docs.talon.one/docs/dev/concepts/attributes#custom-attributes) of a loyalty card. These attributes must be created in the Campaign Manager before their values can be updated through this endpoint.  | [optional] |
| **card_code_settings** | [**CodeGeneratorSettings**](CodeGeneratorSettings.md) |  | [optional] |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::LoyaltyCardBatch.new(
  number_of_cards: 5000,
  batch_id: hwernpjz,
  status: active,
  attributes: {PIN&#x3D;1234, Language&#x3D;DE},
  card_code_settings: null
)
```

