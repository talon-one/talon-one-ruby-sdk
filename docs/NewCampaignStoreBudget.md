# TalonOne::NewCampaignStoreBudget

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **action** | **String** |  |  |
| **store_limits** | [**Array&lt;NewCampaignStoreBudgetStoreLimit&gt;**](NewCampaignStoreBudgetStoreLimit.md) | The set of budget limits for stores linked to the campaign. |  |
| **period** | **String** |  | [optional] |

## Example

```ruby
require 'talon_one'

instance = TalonOne::NewCampaignStoreBudget.new(
  action: null,
  store_limits: null,
  period: null
)
```

