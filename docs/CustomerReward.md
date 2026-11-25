# TalonOne::CustomerReward

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **application_id** | **Integer** | The ID of the Application in which the reward was unlocked. |  |
| **profile_integration_id** | **String** | The integration ID of the customer profile that unlocked this reward. |  |
| **integration_id** | **String** | The integration ID assigned to this reward unlock. |  |
| **unlocked_at** | **Time** | The date and time when the reward was unlocked. |  |
| **expiry_date** | **Time** | The date and time when the customer reward expires, based on the  &#x60;validityDuration&#x60; or &#x60;expiryDate&#x60; of the reward when the reward was  unlocked. If the reward does not specify either property, the customer reward  has unlimited validity and this field is omitted.  **Note**: The expiry date is calculated using the time zone of the  Application connected to the reward.  | [optional] |
| **used_at** | **Time** | The date and time when the reward was used. | [optional] |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::CustomerReward.new(
  application_id: 3,
  profile_integration_id: customer1,
  integration_id: reward-unlock-123,
  unlocked_at: 2024-01-01T00:00:00Z,
  expiry_date: 2024-03-31T23:59:59Z,
  used_at: 2024-01-02T00:00:00Z
)
```

