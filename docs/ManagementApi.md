# TalonOne::ManagementApi

All URIs are relative to *https://yourbaseurl.talon.one*

| Method | HTTP request | Description |
| ------ | ------------ | ----------- |
| [**coupon_created_event**](ManagementApi.md#coupon_created_event) | **POST** /CouponCreatedEvent | Coupon Created Event |
| [**coupon_deleted_event**](ManagementApi.md#coupon_deleted_event) | **POST** /CouponDeletedEvent | Coupon Deleted Event |
| [**coupon_updated_event**](ManagementApi.md#coupon_updated_event) | **POST** /CouponUpdatedEvent | Coupon Updated Event |
| [**loyalty_points_changed_event**](ManagementApi.md#loyalty_points_changed_event) | **POST** /LoyaltyPointsChangedEvent | Changed Loyalty Points Event |
| [**loyalty_tier_downgrade_event**](ManagementApi.md#loyalty_tier_downgrade_event) | **POST** /LoyaltyTierDowngradeEvent | Loyalty Tier Downgrade Event |
| [**loyalty_tier_upgrade_event**](ManagementApi.md#loyalty_tier_upgrade_event) | **POST** /LoyaltyTierUpgradeEvent | Loyalty Tier Upgrade Event |


## coupon_created_event

> coupon_created_event(coupon_created_event_request)

Coupon Created Event

### Examples

```ruby
require 'time'
require 'talon_one_sdk'
# setup authorization
TalonOne.configure do |config|
  # Configure API key authorization: management_key
  config.api_key['Authorization'] = 'YOUR API KEY'
  # Uncomment the following line to set a prefix for the API key, e.g. 'Bearer' (defaults to nil)
  # config.api_key_prefix['Authorization'] = 'Bearer'

  # Configure API key authorization: manager_auth
  config.api_key['Authorization'] = 'YOUR API KEY'
  # Uncomment the following line to set a prefix for the API key, e.g. 'Bearer' (defaults to nil)
  # config.api_key_prefix['Authorization'] = 'Bearer'

  # Configure API key authorization: api_key_v1
  config.api_key['Authorization'] = 'YOUR API KEY'
  # Uncomment the following line to set a prefix for the API key, e.g. 'Bearer' (defaults to nil)
  # config.api_key_prefix['Authorization'] = 'Bearer'
end

api_instance = TalonOne::ManagementApi.new
coupon_created_event_request =  # CouponCreatedEventRequest | ...

begin
  # Coupon Created Event
  api_instance.coupon_created_event(coupon_created_event_request)
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->coupon_created_event: #{e}"
end
```

#### Using the coupon_created_event_with_http_info variant

This returns an Array which contains the response data (`nil` in this case), status code and headers.

> <Array(nil, Integer, Hash)> coupon_created_event_with_http_info(coupon_created_event_request)

```ruby
begin
  # Coupon Created Event
  data, status_code, headers = api_instance.coupon_created_event_with_http_info(coupon_created_event_request)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => nil
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->coupon_created_event_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **coupon_created_event_request** | [**CouponCreatedEventRequest**](CouponCreatedEventRequest.md) | ... |  |

### Return type

nil (empty response body)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined


## coupon_deleted_event

> coupon_deleted_event(coupon_deleted_event_request)

Coupon Deleted Event

### Examples

```ruby
require 'time'
require 'talon_one_sdk'
# setup authorization
TalonOne.configure do |config|
  # Configure API key authorization: management_key
  config.api_key['Authorization'] = 'YOUR API KEY'
  # Uncomment the following line to set a prefix for the API key, e.g. 'Bearer' (defaults to nil)
  # config.api_key_prefix['Authorization'] = 'Bearer'

  # Configure API key authorization: manager_auth
  config.api_key['Authorization'] = 'YOUR API KEY'
  # Uncomment the following line to set a prefix for the API key, e.g. 'Bearer' (defaults to nil)
  # config.api_key_prefix['Authorization'] = 'Bearer'

  # Configure API key authorization: api_key_v1
  config.api_key['Authorization'] = 'YOUR API KEY'
  # Uncomment the following line to set a prefix for the API key, e.g. 'Bearer' (defaults to nil)
  # config.api_key_prefix['Authorization'] = 'Bearer'
end

api_instance = TalonOne::ManagementApi.new
coupon_deleted_event_request =  # CouponDeletedEventRequest | ...

begin
  # Coupon Deleted Event
  api_instance.coupon_deleted_event(coupon_deleted_event_request)
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->coupon_deleted_event: #{e}"
end
```

#### Using the coupon_deleted_event_with_http_info variant

This returns an Array which contains the response data (`nil` in this case), status code and headers.

> <Array(nil, Integer, Hash)> coupon_deleted_event_with_http_info(coupon_deleted_event_request)

```ruby
begin
  # Coupon Deleted Event
  data, status_code, headers = api_instance.coupon_deleted_event_with_http_info(coupon_deleted_event_request)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => nil
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->coupon_deleted_event_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **coupon_deleted_event_request** | [**CouponDeletedEventRequest**](CouponDeletedEventRequest.md) | ... |  |

### Return type

nil (empty response body)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined


## coupon_updated_event

> coupon_updated_event(coupon_updated_event_request)

Coupon Updated Event

### Examples

```ruby
require 'time'
require 'talon_one_sdk'
# setup authorization
TalonOne.configure do |config|
  # Configure API key authorization: management_key
  config.api_key['Authorization'] = 'YOUR API KEY'
  # Uncomment the following line to set a prefix for the API key, e.g. 'Bearer' (defaults to nil)
  # config.api_key_prefix['Authorization'] = 'Bearer'

  # Configure API key authorization: manager_auth
  config.api_key['Authorization'] = 'YOUR API KEY'
  # Uncomment the following line to set a prefix for the API key, e.g. 'Bearer' (defaults to nil)
  # config.api_key_prefix['Authorization'] = 'Bearer'

  # Configure API key authorization: api_key_v1
  config.api_key['Authorization'] = 'YOUR API KEY'
  # Uncomment the following line to set a prefix for the API key, e.g. 'Bearer' (defaults to nil)
  # config.api_key_prefix['Authorization'] = 'Bearer'
end

api_instance = TalonOne::ManagementApi.new
coupon_updated_event_request =  # CouponUpdatedEventRequest | ...

begin
  # Coupon Updated Event
  api_instance.coupon_updated_event(coupon_updated_event_request)
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->coupon_updated_event: #{e}"
end
```

#### Using the coupon_updated_event_with_http_info variant

This returns an Array which contains the response data (`nil` in this case), status code and headers.

> <Array(nil, Integer, Hash)> coupon_updated_event_with_http_info(coupon_updated_event_request)

```ruby
begin
  # Coupon Updated Event
  data, status_code, headers = api_instance.coupon_updated_event_with_http_info(coupon_updated_event_request)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => nil
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->coupon_updated_event_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **coupon_updated_event_request** | [**CouponUpdatedEventRequest**](CouponUpdatedEventRequest.md) | ... |  |

### Return type

nil (empty response body)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined


## loyalty_points_changed_event

> loyalty_points_changed_event(loyalty_points_changed_event_request)

Changed Loyalty Points Event

### Examples

```ruby
require 'time'
require 'talon_one_sdk'
# setup authorization
TalonOne.configure do |config|
  # Configure API key authorization: management_key
  config.api_key['Authorization'] = 'YOUR API KEY'
  # Uncomment the following line to set a prefix for the API key, e.g. 'Bearer' (defaults to nil)
  # config.api_key_prefix['Authorization'] = 'Bearer'

  # Configure API key authorization: manager_auth
  config.api_key['Authorization'] = 'YOUR API KEY'
  # Uncomment the following line to set a prefix for the API key, e.g. 'Bearer' (defaults to nil)
  # config.api_key_prefix['Authorization'] = 'Bearer'

  # Configure API key authorization: api_key_v1
  config.api_key['Authorization'] = 'YOUR API KEY'
  # Uncomment the following line to set a prefix for the API key, e.g. 'Bearer' (defaults to nil)
  # config.api_key_prefix['Authorization'] = 'Bearer'
end

api_instance = TalonOne::ManagementApi.new
loyalty_points_changed_event_request =  # LoyaltyPointsChangedEventRequest | ...

begin
  # Changed Loyalty Points Event
  api_instance.loyalty_points_changed_event(loyalty_points_changed_event_request)
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->loyalty_points_changed_event: #{e}"
end
```

#### Using the loyalty_points_changed_event_with_http_info variant

This returns an Array which contains the response data (`nil` in this case), status code and headers.

> <Array(nil, Integer, Hash)> loyalty_points_changed_event_with_http_info(loyalty_points_changed_event_request)

```ruby
begin
  # Changed Loyalty Points Event
  data, status_code, headers = api_instance.loyalty_points_changed_event_with_http_info(loyalty_points_changed_event_request)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => nil
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->loyalty_points_changed_event_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **loyalty_points_changed_event_request** | [**LoyaltyPointsChangedEventRequest**](LoyaltyPointsChangedEventRequest.md) | ... |  |

### Return type

nil (empty response body)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined


## loyalty_tier_downgrade_event

> loyalty_tier_downgrade_event(loyalty_tier_downgrade_event_request)

Loyalty Tier Downgrade Event

### Examples

```ruby
require 'time'
require 'talon_one_sdk'
# setup authorization
TalonOne.configure do |config|
  # Configure API key authorization: management_key
  config.api_key['Authorization'] = 'YOUR API KEY'
  # Uncomment the following line to set a prefix for the API key, e.g. 'Bearer' (defaults to nil)
  # config.api_key_prefix['Authorization'] = 'Bearer'

  # Configure API key authorization: manager_auth
  config.api_key['Authorization'] = 'YOUR API KEY'
  # Uncomment the following line to set a prefix for the API key, e.g. 'Bearer' (defaults to nil)
  # config.api_key_prefix['Authorization'] = 'Bearer'

  # Configure API key authorization: api_key_v1
  config.api_key['Authorization'] = 'YOUR API KEY'
  # Uncomment the following line to set a prefix for the API key, e.g. 'Bearer' (defaults to nil)
  # config.api_key_prefix['Authorization'] = 'Bearer'
end

api_instance = TalonOne::ManagementApi.new
loyalty_tier_downgrade_event_request =  # LoyaltyTierDowngradeEventRequest | ...

begin
  # Loyalty Tier Downgrade Event
  api_instance.loyalty_tier_downgrade_event(loyalty_tier_downgrade_event_request)
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->loyalty_tier_downgrade_event: #{e}"
end
```

#### Using the loyalty_tier_downgrade_event_with_http_info variant

This returns an Array which contains the response data (`nil` in this case), status code and headers.

> <Array(nil, Integer, Hash)> loyalty_tier_downgrade_event_with_http_info(loyalty_tier_downgrade_event_request)

```ruby
begin
  # Loyalty Tier Downgrade Event
  data, status_code, headers = api_instance.loyalty_tier_downgrade_event_with_http_info(loyalty_tier_downgrade_event_request)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => nil
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->loyalty_tier_downgrade_event_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **loyalty_tier_downgrade_event_request** | [**LoyaltyTierDowngradeEventRequest**](LoyaltyTierDowngradeEventRequest.md) | ... |  |

### Return type

nil (empty response body)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined


## loyalty_tier_upgrade_event

> loyalty_tier_upgrade_event(loyalty_tier_upgrade_event_request)

Loyalty Tier Upgrade Event

### Examples

```ruby
require 'time'
require 'talon_one_sdk'
# setup authorization
TalonOne.configure do |config|
  # Configure API key authorization: management_key
  config.api_key['Authorization'] = 'YOUR API KEY'
  # Uncomment the following line to set a prefix for the API key, e.g. 'Bearer' (defaults to nil)
  # config.api_key_prefix['Authorization'] = 'Bearer'

  # Configure API key authorization: manager_auth
  config.api_key['Authorization'] = 'YOUR API KEY'
  # Uncomment the following line to set a prefix for the API key, e.g. 'Bearer' (defaults to nil)
  # config.api_key_prefix['Authorization'] = 'Bearer'

  # Configure API key authorization: api_key_v1
  config.api_key['Authorization'] = 'YOUR API KEY'
  # Uncomment the following line to set a prefix for the API key, e.g. 'Bearer' (defaults to nil)
  # config.api_key_prefix['Authorization'] = 'Bearer'
end

api_instance = TalonOne::ManagementApi.new
loyalty_tier_upgrade_event_request =  # LoyaltyTierUpgradeEventRequest | ...

begin
  # Loyalty Tier Upgrade Event
  api_instance.loyalty_tier_upgrade_event(loyalty_tier_upgrade_event_request)
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->loyalty_tier_upgrade_event: #{e}"
end
```

#### Using the loyalty_tier_upgrade_event_with_http_info variant

This returns an Array which contains the response data (`nil` in this case), status code and headers.

> <Array(nil, Integer, Hash)> loyalty_tier_upgrade_event_with_http_info(loyalty_tier_upgrade_event_request)

```ruby
begin
  # Loyalty Tier Upgrade Event
  data, status_code, headers = api_instance.loyalty_tier_upgrade_event_with_http_info(loyalty_tier_upgrade_event_request)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => nil
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->loyalty_tier_upgrade_event_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **loyalty_tier_upgrade_event_request** | [**LoyaltyTierUpgradeEventRequest**](LoyaltyTierUpgradeEventRequest.md) | ... |  |

### Return type

nil (empty response body)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined

