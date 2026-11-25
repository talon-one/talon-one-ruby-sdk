# TalonOne::UpdateLoyaltyProgramMembershipBlock

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** | Unique identifier for this block. | [optional][readonly] |
| **type** | **String** | Identifies the block variant and determines which additional properties are present in it. |  |
| **tags** | **Array&lt;String&gt;** | Semantic labels attached to this block. | [optional][readonly] |
| **operator** | **String** | The action to perform. &#x60;join&#x60; adds the customer to the loyalty program. |  |
| **program** | [**UpdateLoyaltyProgramMembershipBlock1Program**](UpdateLoyaltyProgramMembershipBlock1Program.md) |  |  |
| **join_date** | **Object** | The date and time the customer joins the program. Cannot be in the future. Accepts one of: - An absolute timestamp in RFC 3339 format (e.g. &#x60;2026-01-15T10:00:00Z&#x60;). - A reference to a value, such as &#x60;{{$Now}}&#x60; or an attribute. - A relative time: an object with a &#x60;baseline&#x60; time, a &#x60;duration&#x60;, and an &#x60;operator&#x60;   that is &#x60;laterBy&#x60; or &#x60;earlierBy&#x60;. - A rounded time: an object with a &#x60;baseline&#x60; time, a &#x60;unit&#x60; (such as &#x60;day&#x60;, &#x60;hour&#x60; or   &#x60;month&#x60;), and a &#x60;direction&#x60; that is &#x60;start&#x60; or &#x60;end&#x60;. The baseline must be a relative   time whose duration uses the same unit.  See the examples for each form. |  |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::UpdateLoyaltyProgramMembershipBlock.new(
  id: a1b2c3d4-e5f6-7890-abcd-ef1234567890,
  type: null,
  tags: null,
  operator: join,
  program: null,
  join_date: {{$Now}}
)
```

