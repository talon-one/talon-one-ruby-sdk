# TalonOne::Giveaway

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **Integer** | The internal ID of this entity. |  |
| **created** | **Time** | The time this entity was created. |  |
| **code** | **String** | The code value of this giveaway. |  |
| **pool_id** | **Integer** | The ID of the pool to return giveaway codes from. |  |
| **start_date** | **Time** | Timestamp at which point the giveaway becomes valid. | [optional] |
| **end_date** | **Time** | Timestamp at which point the giveaway becomes invalid. | [optional] |
| **attributes** | **Object** | Arbitrary properties associated with this giveaway. | [optional] |
| **used** | **Boolean** | Indicates whether this giveaway code was given before. | [optional] |
| **import_id** | **Integer** | The ID of the Import which created this giveaway. | [optional] |
| **profile_integration_id** | **String** | The third-party integration ID of the customer profile that was awarded the giveaway, if the giveaway was awarded. | [optional] |
| **profile_id** | **Integer** | The internal ID of the customer profile that was awarded the giveaway, if the giveaway was awarded and an internal ID exists. | [optional] |

## Example

```ruby
require 'talon_one'

instance = TalonOne::Giveaway.new(
  id: 6,
  created: 2020-06-10T09:05:27.993483Z,
  code: GIVEAWAY1,
  pool_id: 1,
  start_date: 2022-01-02T15:04:05Z07:00,
  end_date: 2023-01-02T15:04:05Z07:00,
  attributes: null,
  used: true,
  import_id: 4,
  profile_integration_id: R195412,
  profile_id: 1
)
```

