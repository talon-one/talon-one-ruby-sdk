# TalonOne::CouponDeletionJob

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** | The internal ID of this entity. |  |
| **created** | **Time** | The time this entity was created. |  |
| **application_id** | **Integer** | The ID of the Application that owns this entity. |  |
| **account_id** | **Integer** | The ID of the account that owns this entity. |  |
| **filters** | [**CouponDeletionFilters**](CouponDeletionFilters.md) |  |  |
| **status** | **String** | The current status of this request. Possible values: - &#x60;not_ready&#x60; - &#x60;pending&#x60; - &#x60;completed&#x60; - &#x60;failed&#x60;  |  |
| **deleted_amount** | **Integer** | The number of coupon codes that were already deleted for this request. | [optional] |
| **fail_count** | **Integer** | The number of times this job failed. |  |
| **errors** | **Array&lt;String&gt;** | An array of individual problems encountered during the request. |  |
| **created_by** | **Integer** | ID of the user who created this effect. |  |
| **communicated** | **Boolean** | Indicates whether the user that created this job was notified of its final state. |  |
| **campaign_ids** | **Array&lt;Integer&gt;** |  | [optional] |

## Example

```ruby
require 'talon_one'

instance = TalonOne::CouponDeletionJob.new(
  id: 6,
  created: 2020-06-10T09:05:27.993483Z,
  application_id: 322,
  account_id: 3886,
  filters: null,
  status: pending,
  deleted_amount: 1000000,
  fail_count: 10,
  errors: [&quot;Connection to database was reset&quot;,&quot;failed to delete codes&quot;],
  created_by: 1,
  communicated: false,
  campaign_ids: null
)
```

