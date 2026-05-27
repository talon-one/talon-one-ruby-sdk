# TalonOne::RewardPointsRequired

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** | The ID of the &#x60;pointsRequired&#x60; entry. When updating a reward, include this property to update an existing entry. Omit it to create a new one.  | [optional] |
| **amount** | **Float** | The number of loyalty points required to activate the reward. |  |
| **loyalty_program_id** | **Integer** | The ID of the associated loyalty program. |  |
| **subledger_id** | **String** | The ID of the subledger within the loyalty program from which points are deducted when activating the reward.  To specify the main ledger, provide an empty string (\&quot;\&quot;).  |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::RewardPointsRequired.new(
  id: 1,
  amount: 500,
  loyalty_program_id: 10,
  subledger_id: mysubledger
)
```

