# TalonOne::CreateCouponData

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **data** | [**Array&lt;ExtendedCoupon&gt;**](ExtendedCoupon.md) | The array of coupons codes. If 1000 or fewer coupons are requested, all coupon data is sent. If 1001 or more coupons are requested, only &#x60;BatchID&#x60; is sent. | [optional] |
| **total_result_size** | **Integer** |  | [optional] |
| **batch_id** | **String** | The ID of the batch to which the coupon belongs.  **Note:** The Batch ID is generated when coupons are created.  | [optional] |
| **type_of_change** | **String** |  |  |
| **operation** | **String** |  |  |
| **employee_name** | **String** |  |  |
| **notification_type** | **String** | The type of the not |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::CreateCouponData.new(
  data: [{&quot;id&quot;:1,&quot;created&quot;:&quot;2023-01-31T15:19:25.18417+01:00&quot;,&quot;campaignId&quot;:1,&quot;value&quot;:&quot;73KXKKFP&quot;,&quot;usageLimit&quot;:1,&quot;reservationLimit&quot;:0,&quot;usageCounter&quot;:0,&quot;attributes&quot;:{},&quot;reservation&quot;:true,&quot;batchId&quot;:&quot;nqylhnni&quot;},{&quot;id&quot;:2,&quot;created&quot;:&quot;2023-01-31T15:19:25.18417+01:00&quot;,&quot;campaignId&quot;:1,&quot;value&quot;:&quot;BH3CXXLW&quot;,&quot;usageLimit&quot;:1,&quot;reservationLimit&quot;:0,&quot;usageCounter&quot;:0,&quot;attributes&quot;:{},&quot;reservation&quot;:true,&quot;batchId&quot;:&quot;nqylhnni&quot;}],
  total_result_size: 1,
  batch_id: haanlypn,
  type_of_change: campaign_manager,
  operation: AsyncCouponsCreated,
  employee_name: Franziska Schneider,
  notification_type: null
)
```

