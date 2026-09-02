# TalonOne::IntegrationRewardsCatalog200Response

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **catalog** | [**IntegrationRewardsCatalog200ResponseCatalog**](IntegrationRewardsCatalog200ResponseCatalog.md) |  |  |
| **loyalty** | [**Hash&lt;String, LoyaltyBalances&gt;**](LoyaltyBalances.md) | The customer&#39;s loyalty balances for the specified loyalty program. Returned only when &#x60;loyaltyProgramId&#x60; is provided together with &#x60;profileIntegrationId&#x60; or &#x60;loyaltyCardId&#x60;.  | [optional] |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::IntegrationRewardsCatalog200Response.new(
  catalog: null,
  loyalty: null
)
```

