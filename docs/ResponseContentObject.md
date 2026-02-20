# TalonOne::ResponseContentObject

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **response_content** | **Array&lt;String&gt;** | Extends the response with the chosen data entities. Use this property to get as much data back as needed from one request instead of sending extra requests to other endpoints.  | [optional] |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::ResponseContentObject.new(
  response_content: [triggeredCampaigns, customerProfile]
)
```

