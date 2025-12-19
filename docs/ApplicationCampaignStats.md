# TalonOne::ApplicationCampaignStats

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **disabled** | **Integer** | Number of disabled campaigns. |  |
| **staged** | **Integer** | Number of staged campaigns. |  |
| **scheduled** | **Integer** | Number of scheduled campaigns. |  |
| **running** | **Integer** | Number of running campaigns. |  |
| **expired** | **Integer** | Number of expired campaigns. |  |
| **archived** | **Integer** | Number of archived campaigns. |  |

## Example

```ruby
require 'talon_one'

instance = TalonOne::ApplicationCampaignStats.new(
  disabled: null,
  staged: null,
  scheduled: null,
  running: null,
  expired: null,
  archived: null
)
```

