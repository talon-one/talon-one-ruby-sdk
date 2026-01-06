# TalonOne::UpdateAccount

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **attributes** | **Object** | Arbitrary properties associated with this campaign. | [optional] |
| **company_name** | **String** | Name of your company. |  |
| **billing_email** | **String** | The billing email address associated with your company account. |  |
| **state** | **String** | State of the account (active, deactivated). | [optional] |
| **plan_expires** | **Time** | The point in time at which your current plan expires. | [optional] |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::UpdateAccount.new(
  attributes: null,
  company_name: null,
  billing_email: null,
  state: null,
  plan_expires: null
)
```

