# TalonOne::WithinCheckAttributeBlock

## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **operator** | **String** | The range comparison operator. Must be &#x60;within&#x60; or &#x60;not(within)&#x60;. | [optional] |
| **start** | **Object** |  |  |
| **_end** | **Object** |  |  |
| **start_inclusive** | **Boolean** | When &#x60;true&#x60;, the &#x60;start&#x60; value is included in the range for the &#x60;within&#x60; operator. | [optional] |
| **end_inclusive** | **Boolean** | When &#x60;true&#x60;, the &#x60;end&#x60; value is included in the range for the &#x60;within&#x60; operator. | [optional] |
| **timezone_insensitive** | **Boolean** | Indicates whether the &#x60;within&#x60; operator ignores time zones and compares the wall-clock time only. When &#x60;false&#x60;, time zones are taken into account. | [optional] |

## Example

```ruby
require 'talon_one_sdk'

instance = TalonOne::WithinCheckAttributeBlock.new(
  operator: null,
  start: null,
  _end: null,
  start_inclusive: true,
  end_inclusive: true,
  timezone_insensitive: false
)
```

