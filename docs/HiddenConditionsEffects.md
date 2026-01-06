# TalonOne::HiddenConditionsEffects

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **built_in_effects** | **Array&lt;String&gt;** | List of hidden built-in effects. | [optional] |
| **conditions** | **Array&lt;String&gt;** | List of hidden conditions. | [optional] |
| **custom_effects** | **Array&lt;Integer&gt;** | List of the IDs of hidden custom effects. | [optional] |
| **webhooks** | **Array&lt;Integer&gt;** | List of the IDs of hidden webhooks. | [optional] |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::HiddenConditionsEffects.new(
  built_in_effects: [&quot;addFreeItem&quot;,&quot;createNotification&quot;],
  conditions: [&quot;checkAttributeValue&quot;,&quot;couponCodeIsValid&quot;],
  custom_effects: [1,2],
  webhooks: [3,4]
)
```

