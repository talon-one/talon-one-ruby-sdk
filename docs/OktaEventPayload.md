# TalonOne::OktaEventPayload

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **data** | [**OktaEventPayloadData**](OktaEventPayloadData.md) |  |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::OktaEventPayload.new(
  data: {&quot;data&quot;:{&quot;events&quot;:[{&quot;eventType&quot;:&quot;application.user_membership.add&quot;,&quot;target&quot;:[{&quot;type&quot;:&quot;AppUser&quot;,&quot;alternateId&quot;:&quot;john.doe@example.com&quot;,&quot;displayName&quot;:&quot;John Doe&quot;}]}]}}
)
```

