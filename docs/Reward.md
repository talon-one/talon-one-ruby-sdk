# TalonOne::Reward

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** | The internal ID of this entity. |  |
| **created** | **Time** | The time this entity was created. |  |
| **account_id** | **Integer** | The ID of the account that owns this entity. |  |
| **name** | **String** | The name of the reward. |  |
| **api_name** | **String** | A unique identifier used to reference the reward in API integrations. |  |
| **description** | **String** | A description of the reward. | [optional] |
| **application_ids** | **Array&lt;Integer&gt;** | The IDs of the Applications this reward is connected to.   **Note**: Currently, a reward can only be connected to one Application.  |  |
| **sandbox** | **Boolean** | Indicates if this is a live or sandbox reward. Rewards of a given type can only be connected to Applications of the same type. |  |
| **status** | **String** | The status of the reward. |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::Reward.new(
  id: 6,
  created: 2020-06-10T09:05:27.993483Z,
  account_id: 3886,
  name: Free Coffee,
  api_name: free-coffee,
  description: This reward gets you one free coffee.,
  application_ids: [1, 2, 3],
  sandbox: true,
  status: active
)
```

