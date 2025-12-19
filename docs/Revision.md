# TalonOne::Revision

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** | Unique ID for this entity. Not to be confused with the Integration ID, which is set by your integration layer and used in most endpoints. |  |
| **activate_at** | **Time** |  | [optional] |
| **account_id** | **Integer** |  |  |
| **application_id** | **Integer** |  |  |
| **campaign_id** | **Integer** |  |  |
| **created** | **Time** |  |  |
| **created_by** | **Integer** |  |  |
| **activated_at** | **Time** |  | [optional] |
| **activated_by** | **Integer** |  | [optional] |
| **current_version** | [**RevisionVersion**](RevisionVersion.md) |  | [optional] |

## Example

```ruby
require 'talon_one'

instance = TalonOne::Revision.new(
  id: 6,
  activate_at: null,
  account_id: null,
  application_id: null,
  campaign_id: null,
  created: null,
  created_by: null,
  activated_at: null,
  activated_by: null,
  current_version: null
)
```

