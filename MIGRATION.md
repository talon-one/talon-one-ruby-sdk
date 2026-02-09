# Migration guide

This document provides guidance on how to migrate from the [legacy version](https://github.com/talon-one/talon_one.rb)
of the SDK to the latest version. Follow the steps below to ensure a smooth transition.

## Breaking changes summary

| Change                      | Impact                                                       |
| --------------------------- | ------------------------------------------------------------ |
| Gem renamed                 | `gem 'talon_one'` → `gem 'talon_one_sdk'`                    |
| Require statement           | `require 'talon_one'` → `require 'talon_one_sdk'`            |
| Ruby version requirement    | Unchanged (`>= 1.9`)                                         |
| Auth key names              | **No change** (still `config.api_key['Authorization']`)      |
| Module namespace            | **No change** (still `TalonOne`)                             |
| API method parameter names  | `body` → typed parameter names (e.g., `integration_request`) |
| Model base class            | Models now inherit from `ApiModelBase`                       |
| DateTime → Time             | `DateTime` replaced with `Time` throughout                   |
| Removed `timeout` attribute | `ApiError#timeout` removed                                   |
| New API methods             | 6 new methods across Integration and Management APIs         |
| OpenAPI Generator           | 4.3.1 → 7.19.0                                               |
| Versioning scheme           | Semantic (`11.0.0`) → Calendar-based (`26.02`)               |
| Stricter model construction | Models now enforce required fields on `initialize`           |

## Changes

### Gem renamed

**Before**

```ruby
gem 'talon_one', '~> 11.0.0'
```

**After**

```ruby
gem 'talon_one_sdk', '~> 26.02'
```

### Installation

**Before**

```bash
gem install talon_one
```

**After**

```bash
gem install talon_one_sdk
```

### Require statement changed

**Before**

```ruby
require 'talon_one'
```

**After**

```ruby
require 'talon_one_sdk'
```

The module namespace remains `TalonOne`, so all class references like
`TalonOne::IntegrationApi` remain unchanged.

### Authentication configuration (no change)

The Ruby SDK authentication configuration is **unchanged**. Both old and new SDKs use the
same pattern:

```ruby
TalonOne.configure do |config|
  config.scheme = 'https'
  config.host = 'yourbaseurl.talon.one'

  # Integration API
  config.api_key['Authorization'] = 'your-api-key'
  config.api_key_prefix['Authorization'] = 'ApiKey-v1'

  # OR Management API
  config.api_key['Authorization'] = 'your-management-key'
  config.api_key_prefix['Authorization'] = 'ManagementKey-v1'
end
```

The `auth_settings` method in `configuration.rb` defines three auth schemes (`api_key_v1`,
`management_key`, `manager_auth`), but they all resolve to the `'Authorization'` header
key. No code changes needed.

### API method parameter renames

**This is the most impactful breaking change.** Across both APIs, generic `body`
parameters have been renamed to typed, descriptive parameter names.

If you are calling methods using **positional arguments**, this change does **not** affect
you:

```ruby
# This works identically in both SDKs
integration_api.update_customer_session_v2('session-id', integration_request)
```

However, if you are using **keyword arguments**, you must update the parameter names:

**Before**

```ruby
integration_api.update_customer_session_v2('session-id', body: integration_request)
```

**After**

```ruby
integration_api.update_customer_session_v2('session-id', integration_request: integration_request)
```

### Integration API parameter renames

| Method                                    | Old Parameter | New Parameter                                   |
| ----------------------------------------- | ------------- | ----------------------------------------------- |
| `best_prior_price`                        | `body`        | `best_prior_price_request`                      |
| `create_audience_v2`                      | `body`        | `new_audience`                                  |
| `create_coupon_reservation`               | `body`        | `coupon_reservations`                           |
| `create_referral`                         | `body`        | `new_referral`                                  |
| `create_referrals_for_multiple_advocates` | `body`        | `new_referrals_for_multiple_advocates`          |
| `delete_coupon_reservation`               | `body`        | `coupon_reservations`                           |
| `generate_loyalty_card`                   | `body`        | `generate_loyalty_card`                         |
| `link_loyalty_card_to_profile`            | `body`        | `loyalty_card_registration`                     |
| `return_cart_items`                       | `body`        | `return_integration_request`                    |
| `sync_catalog`                            | `body`        | `catalog_sync_request`                          |
| `track_event_v2`                          | `body`        | `integration_event_v2_request`                  |
| `update_audience_v2`                      | `body`        | `update_audience`                               |
| `update_customer_profile_audiences`       | `body`        | `customer_profile_audience_request`             |
| `update_customer_profile_v2`              | `body`        | `customer_profile_integration_request_v2`       |
| `update_customer_profiles_v2`             | `body`        | `multiple_customer_profile_integration_request` |
| `update_customer_session_v2`              | `body`        | `integration_request`                           |

> [!NOTE]
> `update_audience_customers_attributes` still uses `body` (unchanged).

### Management API parameter renames (selected)

| Method                          | Old Parameter | New Parameter                   |
| ------------------------------- | ------------- | ------------------------------- |
| `activate_user_by_email`        | `body`        | `activate_user_request`         |
| `add_loyalty_card_points`       | `body`        | `add_loyalty_points`            |
| `add_loyalty_points`            | `body`        | `add_loyalty_points`            |
| `copy_campaign_to_applications` | `body`        | `campaign_copy`                 |
| `create_account_collection`     | `body`        | `new_collection`                |
| `create_additional_cost`        | `body`        | `new_additional_cost`           |
| `create_attribute`              | `body`        | `new_attribute`                 |
| `create_coupons`                | `body`        | `new_coupons`                   |
| `create_session`                | `body`        | `login_params`                  |
| `create_store`                  | `body`        | `new_store`                     |
| `get_campaign_by_attributes`    | `body`        | `campaign_search`               |
| `get_customers_by_attributes`   | `body`        | `customer_profile_search_query` |
| `reset_password`                | `body`        | `new_password`                  |
| `update_campaign`               | `body`        | `update_campaign`               |
| `update_coupon`                 | `body`        | `update_coupon`                 |
| `update_user`                   | `body`        | `update_user`                   |

> [!NOTE]
> `search_coupons_advanced_application_wide_without_total_count` and
> `search_coupons_advanced_without_total_count` still use `body`.

### New API methods

#### Integration API

| Method                                     | Endpoint                                                                     | Description                                       |
| ------------------------------------------ | ---------------------------------------------------------------------------- | ------------------------------------------------- |
| `activate_loyalty_points`                  | `POST /v1/loyalty_programs/{id}/activate_points`                             | Activate loyalty points                           |
| `delete_loyalty_transactions_from_ledgers` | `POST /v1/loyalty_programs/{id}/profile/{integrationId}/delete_transactions` | Delete customer transactions from loyalty ledgers |
| `unlink_loyalty_card_from_profile`         | `POST /v2/loyalty_programs/{id}/cards/{cardId}/unlink_profile`               | Unlink customer profile from loyalty card         |

#### Management API

| Method                                            | Endpoint | Description                                     |
| ------------------------------------------------- | -------- | ----------------------------------------------- |
| `generate_coupon_rejections`                      | n/a      | Generate coupon rejections                      |
| `get_loyalty_ledger_balances`                     | n/a      | Get loyalty ledger balances                     |
| `get_loyalty_program_profile_ledger_transactions` | n/a      | Get loyalty program profile ledger transactions |

### Model base class change

All models in the new SDK inherit from `TalonOne::ApiModelBase`, which provides shared
serialization/deserialization methods.

**Before**

```ruby
module TalonOne
  class CartItem
    # standalone class, each model has its own _deserialize, to_s, to_body, _to_hash methods
  end
end
```

**After**

```ruby
module TalonOne
  class CartItem < ApiModelBase
    # inherits _deserialize, to_s, to_body, _to_hash from ApiModelBase
  end
end
```

Additionally, models now have the following:

- `acceptable_attribute_map` class method
- `acceptable_attributes` class method
- Deprecation warnings on `list_invalid_properties` and `valid?`

This change is **backward compatible** for consumers — `to_hash`, `to_body`,
`build_from_hash` all still work.

### Stricter model construction (required fields enforced)

The new SDK enforces required fields when constructing model objects. In the old SDK, you
could create a model with no arguments and set the fields later. In the new SDK, omitting
required fields raises an `ArgumentError`.

Before (permissive):

```ruby
# This worked fine in the old SDK
cart_item = TalonOne::CartItem.new
cart_item.name = 'Test'
cart_item.sku = 'test-001'
cart_item.quantity = 1
cart_item.price = 10.0
```

After (strict):

```ruby
# This raises ArgumentError: sku cannot be nil
cart_item = TalonOne::CartItem.new

# Instead, provide required fields at construction time
cart_item = TalonOne::CartItem.new(
  name: 'Test',
  sku: 'test-001',
  quantity: 1,
  price: 10.0,
  category: 'Test'
)
```

If your code builds models incrementally (setting fields after construction), you must
refactor to pass all required fields in the constructor.

### DateTime replaced with Time

Throughout the SDK, `DateTime` has been replaced with `Time`:

- Model attributes that were typed as `DateTime` now use `Time`
- `api_client.rb` `convert_to_type` uses `Time.parse` instead of `DateTime.parse`
- JSON parse error rescue catches `Time` instead of `DateTime`

If your code stores or processes return values as `DateTime`, update accordingly:

**Before**

```ruby
campaign.created  # => #<DateTime: ...>
```

**After**

```ruby
campaign.created  # => #<Time: ...>
```

### Exception handling changes

Both SDKs use a single `TalonOne::ApiError` class. **No granular exception types** (like
`BadRequestException`, `NotFoundException`) exist in either version.

Key change: The `timeout` attribute was **removed** from `ApiError` in the new SDK.

**Before**

```ruby
rescue TalonOne::ApiError => e
  e.code            # HTTP status code
  e.response_headers # Response headers
  e.response_body    # Response body
  e.timeout          # Boolean - was it a timeout?
end
```

**After**

```ruby
rescue TalonOne::ApiError => e
  e.code            # HTTP status code
  e.response_headers # Response headers
  e.response_body    # Response body
  # e.timeout is NO LONGER AVAILABLE
  # Timeout errors are now raised with message 'Connection timed out'
end
```

To detect timeouts in the new SDK:

```ruby
rescue TalonOne::ApiError => e
  if e.message == 'Connection timed out'
    # Handle timeout
  end
end
```

### InlineResponse model renames

The old SDK had 53 `InlineResponse*` models. Of these, 52 have been renamed to descriptive
names following the pattern `{MethodName}{StatusCode}Response`. One
(`InlineResponse20049`) was removed/consolidated and has no direct equivalent in the new
SDK.

#### Selected mapping (representative examples)

| Old Model             | New Model                                                |
| --------------------- | -------------------------------------------------------- |
| `InlineResponse200`   | `GetCustomerProfiles200Response`                         |
| `InlineResponse2001`  | `GetCustomerAchievements200Response`                     |
| `InlineResponse2002`  | `GetReservedCustomers200Response`                        |
| `InlineResponse2003`  | `GetLoyaltyCardTransactionLogs200Response`               |
| `InlineResponse2004`  | `GetLoyaltyCardPoints200Response`                        |
| `InlineResponse2005`  | `GetLoyaltyCardTransactions200Response`                  |
| `InlineResponse2006`  | `GetCustomerAchievementHistory200Response`               |
| `InlineResponse2007`  | `GetLoyaltyProgramProfilePoints200Response`              |
| `InlineResponse2008`  | `GetLoyaltyProgramProfileTransactions200Response`        |
| `InlineResponse2009`  | `GetLoyaltyProgramTransactions200Response`               |
| `InlineResponse20010` | `GetCouponsWithoutTotalCount200Response`                 |
| `InlineResponse20011` | `GetReferralsWithoutTotalCount200Response`               |
| `InlineResponse20012` | `GetCustomerActivityReportsWithoutTotalCount200Response` |
| `InlineResponse20013` | `GetAccessLogsWithoutTotalCount200Response`              |
| `InlineResponse20014` | `GetApplicationEventsWithoutTotalCount200Response`       |
| `InlineResponse20015` | `GetApplicationSessions200Response`                      |
| `InlineResponse20016` | `GetApplicationCustomerFriends200Response`               |
| `InlineResponse20017` | `GetCampaigns200Response`                                |
| `InlineResponse20018` | `GetCampaignAnalytics200Response`                        |
| `InlineResponse20019` | `GetCampaignGroups200Response`                           |
| `InlineResponse20020` | `GetCampaignTemplates200Response`                        |
| `InlineResponse20021` | `GetApplications200Response`                             |
| `InlineResponse20022` | `GetChanges200Response`                                  |
| `InlineResponse20023` | `GetAttributes200Response`                               |
| `InlineResponse20024` | `GetAdditionalCosts200Response`                          |
| `InlineResponse20025` | `GetAudiences200Response`                                |
| `InlineResponse20026` | `GetAudienceMemberships200Response`                      |
| `InlineResponse20027` | `GetApplicationCustomers200Response`                     |
| `InlineResponse20028` | `GetApplicationCustomersByAttributes200Response`         |
| `InlineResponse20029` | `GetCustomersByAttributes200Response`                    |
| `InlineResponse20030` | `GetEventTypes200Response`                               |
| `InlineResponse20031` | `GetApplicationEventTypes200Response`                    |
| `InlineResponse20032` | `GetExports200Response`                                  |
| `InlineResponse20033` | `GetRulesets200Response`                                 |
| `InlineResponse20034` | `GetCollectionItems200Response`                          |
| `InlineResponse20035` | `GetUsers200Response`                                    |
| `InlineResponse20036` | `GetWebhooks200Response`                                 |
| `InlineResponse20037` | `GetLoyaltyCards200Response`                             |
| `InlineResponse20038` | `GetLoyaltyPrograms200Response`                          |
| `InlineResponse20039` | `GetAudiencesAnalytics200Response`                       |
| `InlineResponse20040` | `GetCustomerProfileAchievementProgress200Response`       |
| `InlineResponse20041` | `GetDashboardStatistics200Response`                      |
| `InlineResponse20042` | Reserved / Internal                                      |
| `InlineResponse20043` | Reserved / Internal                                      |
| `InlineResponse20044` | Reserved / Internal                                      |
| `InlineResponse20045` | Reserved / Internal                                      |
| `InlineResponse20046` | Reserved / Internal                                      |
| `InlineResponse20047` | Reserved / Internal                                      |
| `InlineResponse20048` | Reserved / Internal                                      |
| `InlineResponse20049` | Reserved / Internal                                      |
| `InlineResponse20050` | Reserved / Internal                                      |
| `InlineResponse20051` | Reserved / Internal                                      |
| `InlineResponse201`   | `CreateReferralsForMultipleAdvocates201Response`         |

> [!NOTE]
> You typically do not reference these models directly in user code — they are
> return types used internally by the API methods. However, if you perform type checking
> or use these classes directly, you will need to update references.

### New models

Notable new models added in the new SDK:

- `ActivateLoyaltyPoints` / `ActivateLoyaltyPointsResponse` — Loyalty points activation
- `DeleteLoyaltyTransactionsRequest` — Delete loyalty transactions
- `EventV3` / `IntegrationEventV3Request` / `IntegrationEventV3Response` — V3 event
  support
- `CatalogRule` — Catalog rules
- `CouponFailureSummary` — Coupon failure tracking
- `GenerateCampaignSummary` / `CampaignLogSummary` — Campaign summaries
- `UpdateCustomerProfileV2409Response` / `UpdateCustomerSessionV2409Response` — Conflict
  responses
- `ListAccountCollections200Response`, `ListAchievements200Response`,
  `ListAllRolesV2200Response`, `ListCatalogItems200Response`, `ListStores200Response`,
  `ListCampaignStoreBudgetLimits200Response` — List response models
- `SummarizeCampaignStoreBudget200Response`, `GenerateCouponRejections200Response` — New
  operation response models
- `PrismaticConfig`, `PrismaticEventPayload*`, `PrismaticFlow*` — Prismatic integration
  models
- `RoleV2Readonly` — Read-only role representation
- `CartItemFilterTemplate` — Cart item filtering

### Removed models

Only **4** loaded model constants (accessible via `require 'talon_one'`) were removed in
the new SDK:

- `BestPriorPriceRequestTarget` — renamed to `BestPriorTarget`
- `CatalogAction` — removed entirely
- `JWT` — removed entirely
- `WebhookAuthenticationBase` — removed entirely

> [!NOTE]
> The old SDK repository contains additional model source files (e.g.,
> `AccountDashboardStatisticApiCalls`, `FeedNotification`, `CampaignSetV2`,
> `WebhookLogEntry`) that exist as `.rb` files but are **not loaded** by
> `require 'talon_one'`. These were never accessible via the gem and are not a migration
> concern.

### Configuration changes

#### New configuration parameters

| Parameter                    | Type      | Default | Description                              |
| ---------------------------- | --------- | ------- | ---------------------------------------- |
| `server_index`               | `Integer` | `nil`   | Server configuration index               |
| `server_operation_index`     | `Hash`    | `{}`    | Per-operation server index               |
| `server_variables`           | `Hash`    | `{}`    | Default server variables                 |
| `server_operation_variables` | `Hash`    | `{}`    | Per-operation server variables           |
| `access_token_getter`        | `Proc`    | `nil`   | Dynamic access token refresh             |
| `return_binary_data`         | `Boolean` | `false` | Return binary data instead of temp files |
| `ignore_operation_servers`   | `Boolean` | `false` | Ignore per-operation server settings     |

#### Changed methods

- `base_url` now accepts an optional `operation` parameter for per-operation server
  selection
- `api_key_with_prefix` now accepts an optional `param_alias` parameter
- `server_url` now accepts an optional `servers` parameter
- New method: `access_token_with_refresh` for dynamic token refresh
- New method: `operation_server_settings` (returns empty hash by default)

### API client changes

Key changes in `api_client.rb`:

- **File download redesigned**: Now uses block-based yielding instead of instance
  variables
- **`DateTime` → `Time`**: All date-time parsing uses `Time.parse` instead of
  `DateTime.parse`
- **oneOf/anyOf support**: Added polymorphic deserialization for OpenAPI 3.1+ schemas
- **`select_header_content_type`**: Now returns `nil` instead of `'application/json'` when
  no content types provided
- **`follow_location`**: New HTTP request option (defaults to `true`)
- **JSON MIME regex**: Added `^` anchor for stricter matching
- **Typo fix**: Error message corrected from "query of header" to "query or header"

### Gemspec / dependency notes

Dependencies are **unchanged** between versions:

| Dependency            | Version            |
| --------------------- | ------------------ |
| `typhoeus` (runtime)  | `~> 1.0, >= 1.0.1` |
| `json` (runtime)      | `~> 2.1, >= 2.1.0` |
| `rspec` (development) | `~> 3.6, >= 3.6.0` |

The Ruby version requirement remains `>= 1.9` in both versions. The Ruby SDK has not
changed this.

## Complete example

### Integration API (new SDK)

```ruby
require 'talon_one_sdk'

# Configure the SDK
TalonOne.configure do |config|
  config.scheme = 'https'
  config.host = 'yourbaseurl.talon.one'
  config.api_key['Authorization'] = ENV['TALON_API_KEY']
  config.api_key_prefix['Authorization'] = 'ApiKey-v1'
end

# Create the Integration API client
integration_api = TalonOne::IntegrationApi.new

# Build the customer session
customer_session = TalonOne::NewCustomerSessionV2.new(
  profile_id: 'customer-123',
  state: 'open',
  cart_items: [
    TalonOne::CartItem.new(
      name: 'Premium Widget',
      sku: 'WIDGET-001',
      quantity: 2,
      price: 29.99,
      category: 'Widgets'
    )
  ],
  total: 59.98
)

# Build the integration request
integration_request = TalonOne::IntegrationRequest.new(
  customer_session: customer_session,
  response_content: ['customerSession', 'customerProfile', 'triggeredCampaigns']
)

begin
  # Update the customer session
  result = integration_api.update_customer_session_v2(
    'session-abc-123',
    integration_request
  )

  puts "Session state: #{result.customer_session.state}"
  puts "Effects: #{result.effects.length}"

  result.effects.each do |effect|
    puts "  - #{effect.effect_type}: #{effect.props}"
  end
rescue TalonOne::ApiError => e
  puts "API Error: #{e.message} (HTTP #{e.code})"
  puts "Response: #{e.response_body}"
end
```

### Management API (new SDK)

```ruby
require 'talon_one_sdk'

# Configure for Management API
TalonOne.configure do |config|
  config.scheme = 'https'
  config.host = 'yourbaseurl.talon.one'
  config.api_key['Authorization'] = ENV['TALON_MGMT_KEY']
  config.api_key_prefix['Authorization'] = 'ManagementKey-v1'
end

management_api = TalonOne::ManagementApi.new

begin
  # Get application details
  app = management_api.get_application(7)
  puts "Application: #{app.name} (ID: #{app.id})"

  # List campaigns
  campaigns = management_api.get_campaigns(7)
  campaigns.data.each do |campaign|
    puts "  Campaign: #{campaign.name} (#{campaign.state})"
  end
rescue TalonOne::ApiError => e
  puts "API Error: #{e.message} (HTTP #{e.code})"
end
```

## Migration checklist

- [ ] Update `Gemfile`: `gem 'talon_one'` → `gem 'talon_one_sdk'`
- [ ] Run `bundle install`
- [ ] Find and replace all `require 'talon_one'` → `require 'talon_one_sdk'`
- [ ] If using keyword `body:` argument in API calls, rename to the typed parameter name
- [ ] If referencing `InlineResponse*` models directly, update to new descriptive names
- [ ] If checking `ApiError#timeout`, switch to checking
  `e.message == 'Connection timed out'`
- [ ] If using `DateTime` return values, update to handle `Time` objects
- [ ] If using any removed models, find the replacement or remove usage
- [ ] If constructing models without all required fields, refactor to pass required fields
  in the constructor
- [ ] Run your test suite and fix any remaining issues
