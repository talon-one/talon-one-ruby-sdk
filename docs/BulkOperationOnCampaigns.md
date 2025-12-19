# TalonOne::BulkOperationOnCampaigns

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **operation** | **String** | The operation to perform on the specified campaign IDs.  |  |
| **campaign_ids** | **Array&lt;Integer&gt;** | The list of campaign IDs on which the operation will be performed. |  |
| **activate_at** | **Time** | Timestamp when the revisions are finalized after the &#x60;activate_revision&#x60; operation. The current time is used when left blank.  **Note:** It must be an RFC3339 timestamp string.  | [optional] |

## Example

```ruby
require 'talon_one'

instance = TalonOne::BulkOperationOnCampaigns.new(
  operation: null,
  campaign_ids: [1,2,3],
  activate_at: 2024-10-01T16:00:05Z07:00
)
```

