# TalonOne::CampaignLogSummary

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **name** | **String** | Name of the user that performed the change. |  |
| **email** | **String** | E-mail of the user that performed the change. |  |
| **created** | **Time** | Date and time the change was performed. |  |
| **action** | **String** | Action performed by the user. |  |
| **summary** | **String** | AI-generated summary of the action performed. |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::CampaignLogSummary.new(
  name: Admin,
  email: admin@talon.one,
  created: 2022-01-02T15:04:05Z07:00,
  action: create,
  summary: null
)
```

