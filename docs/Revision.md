# TalonOne::Revision

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** | Unique ID for this entity. Not to be confused with the Integration ID, which is set by your integration layer and used in most endpoints. |  |
| **activate_at** | **Time** | Timestamp when the revision will be activated. | [optional] |
| **account_id** | **Integer** | The ID of the account that owns this entity. |  |
| **application_id** | **Integer** | The ID of the Application that owns this entity. |  |
| **campaign_id** | **Integer** | The ID of the campaign that the revision was created from. |  |
| **created** | **Time** | Timestamp when the revision was created. |  |
| **created_by** | **Integer** | The ID of the user who created this revision. |  |
| **activated_at** | **Time** | Timestamp when this revision was activated. | [optional] |
| **activated_by** | **Integer** | The ID of the user who activated this revision. | [optional] |
| **current_version** | [**RevisionVersion**](RevisionVersion.md) | The current version of this revision. | [optional] |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::Revision.new(
  id: 6,
  activate_at: 2026-10-08T09:30:00Z,
  account_id: 3886,
  application_id: 42,
  campaign_id: 18,
  created: 2026-10-01T08:00:00Z,
  created_by: 134,
  activated_at: 2026-10-08T09:30:00Z,
  activated_by: 334,
  current_version: {id&#x3D;6, accountId&#x3D;3886, applicationId&#x3D;42, campaignId&#x3D;18, created&#x3D;2026-10-01T08:00:00Z, createdBy&#x3D;134, revisionId&#x3D;6, version&#x3D;1, name&#x3D;Summer promotions}
)
```

