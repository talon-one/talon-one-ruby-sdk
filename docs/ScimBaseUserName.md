# TalonOne::ScimBaseUserName

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **formatted** | **String** | The full name, including all middle names, titles, and suffixes as appropriate, formatted for display. | [optional] |

## Example

```ruby
require 'talon_one'

instance = TalonOne::ScimBaseUserName.new(
  formatted: Mr. John J Doe
)
```

