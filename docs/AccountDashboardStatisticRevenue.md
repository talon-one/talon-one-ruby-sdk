# TalonOne::AccountDashboardStatisticRevenue

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **total** | **Float** | All revenue that went through the client&#39;s shop (including purchases that didn’t trigger an effect). |  |
| **influenced** | **Float** | The revenue that was created by a purchase that triggered an effect (excluding web hooks, notifications). |  |
| **datetime** | **Time** | Values aggregated for the specified date. |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::AccountDashboardStatisticRevenue.new(
  total: null,
  influenced: null,
  datetime: null
)
```

