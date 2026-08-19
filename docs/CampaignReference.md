# TalonOne::CampaignReference

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** | The ID of the campaign that references this achievement. |  |
| **application_id** | **Integer** | The ID of the Application the campaign belongs to. |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::CampaignReference.new(
  id: 1,
  application_id: 2
)
```

