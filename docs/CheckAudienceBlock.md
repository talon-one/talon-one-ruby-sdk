# TalonOne::CheckAudienceBlock

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **id** | **String** | Unique identifier for this block. |  |
| **type** | **String** | Identifies the block variant and determines which additional properties are present in it. |  |
| **tags** | **Array&lt;String&gt;** | Semantic labels attached to this block. | [optional] |
| **operator** | **String** | An indicator of how the block compares its elements. |  |
| **profile** | **String** | The customer profile to check against the audience. &#x60;Current&#x60; targets the customer in the current session; &#x60;Advocate&#x60; targets the person who invited their friend via referral program. |  |
| **audience** | [**CheckAudienceBlock1Audience**](CheckAudienceBlock1Audience.md) |  |  |
| **on_failure** | **Array&lt;Object&gt;** | Promotion blocks evaluated when this block fails or returns false. | [optional] |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::CheckAudienceBlock.new(
  id: a1b2c3d4-e5f6-7890-abcd-ef1234567890,
  type: null,
  tags: null,
  operator: member,
  profile: Current,
  audience: null,
  on_failure: null
)
```

