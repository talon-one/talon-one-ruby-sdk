# TalonOne::ManagementApi

All URIs are relative to *https://yourbaseurl.talon.one*

| Method | HTTP request | Description |
| ------ | ------------ | ----------- |
| [**activate_user_by_email**](ManagementApi.md#activate_user_by_email) | **POST** /v1/users/activate | Enable user by email address |
| [**add_loyalty_card_points**](ManagementApi.md#add_loyalty_card_points) | **PUT** /v1/loyalty_programs/{loyaltyProgramId}/cards/{loyaltyCardId}/add_points | Add points to card |
| [**add_loyalty_points**](ManagementApi.md#add_loyalty_points) | **PUT** /v1/loyalty_programs/{loyaltyProgramId}/profile/{integrationId}/add_points | Add points to customer profile |
| [**copy_campaign_to_applications**](ManagementApi.md#copy_campaign_to_applications) | **POST** /v1/applications/{applicationId}/campaigns/{campaignId}/copy | Copy the campaign into the specified Application |
| [**create_account_collection**](ManagementApi.md#create_account_collection) | **POST** /v1/collections | Create account-level collection |
| [**create_achievement**](ManagementApi.md#create_achievement) | **POST** /v1/applications/{applicationId}/campaigns/{campaignId}/achievements | Create achievement |
| [**create_additional_cost**](ManagementApi.md#create_additional_cost) | **POST** /v1/additional_costs | Create additional cost |
| [**create_attribute**](ManagementApi.md#create_attribute) | **POST** /v1/attributes | Create custom attribute |
| [**create_batch_loyalty_cards**](ManagementApi.md#create_batch_loyalty_cards) | **POST** /v1/loyalty_programs/{loyaltyProgramId}/cards/batch | Create loyalty cards |
| [**create_campaign_from_template**](ManagementApi.md#create_campaign_from_template) | **POST** /v1/applications/{applicationId}/create_campaign_from_template | Create campaign from campaign template |
| [**create_campaign_store_budget**](ManagementApi.md#create_campaign_store_budget) | **POST** /v1/applications/{applicationId}/campaigns/{campaignId}/stores/budgets | Create campaign store budget |
| [**create_collection**](ManagementApi.md#create_collection) | **POST** /v1/applications/{applicationId}/campaigns/{campaignId}/collections | Create campaign-level collection |
| [**create_coupons**](ManagementApi.md#create_coupons) | **POST** /v1/applications/{applicationId}/campaigns/{campaignId}/coupons | Create coupons |
| [**create_coupons_async**](ManagementApi.md#create_coupons_async) | **POST** /v1/applications/{applicationId}/campaigns/{campaignId}/coupons_async | Create coupons asynchronously |
| [**create_coupons_deletion_job**](ManagementApi.md#create_coupons_deletion_job) | **POST** /v1/applications/{applicationId}/campaigns/{campaignId}/coupons_deletion_jobs | Creates a coupon deletion job |
| [**create_coupons_for_multiple_recipients**](ManagementApi.md#create_coupons_for_multiple_recipients) | **POST** /v1/applications/{applicationId}/campaigns/{campaignId}/coupons_with_recipients | Create coupons for multiple recipients |
| [**create_invite_email**](ManagementApi.md#create_invite_email) | **POST** /v1/invite_emails | Resend invitation email |
| [**create_invite_v2**](ManagementApi.md#create_invite_v2) | **POST** /v2/invites | Invite user |
| [**create_password_recovery_email**](ManagementApi.md#create_password_recovery_email) | **POST** /v1/password_recovery_emails | Request a password reset |
| [**create_session**](ManagementApi.md#create_session) | **POST** /v1/sessions | Create session |
| [**create_store**](ManagementApi.md#create_store) | **POST** /v1/applications/{applicationId}/stores | Create store |
| [**deactivate_user_by_email**](ManagementApi.md#deactivate_user_by_email) | **POST** /v1/users/deactivate | Disable user by email address |
| [**deduct_loyalty_card_points**](ManagementApi.md#deduct_loyalty_card_points) | **PUT** /v1/loyalty_programs/{loyaltyProgramId}/cards/{loyaltyCardId}/deduct_points | Deduct points from card |
| [**delete_account_collection**](ManagementApi.md#delete_account_collection) | **DELETE** /v1/collections/{collectionId} | Delete account-level collection |
| [**delete_achievement**](ManagementApi.md#delete_achievement) | **DELETE** /v1/applications/{applicationId}/campaigns/{campaignId}/achievements/{achievementId} | Delete achievement |
| [**delete_campaign**](ManagementApi.md#delete_campaign) | **DELETE** /v1/applications/{applicationId}/campaigns/{campaignId} | Delete campaign |
| [**delete_campaign_store_budgets**](ManagementApi.md#delete_campaign_store_budgets) | **DELETE** /v1/applications/{applicationId}/campaigns/{campaignId}/stores/budgets | Delete campaign store budgets |
| [**delete_collection**](ManagementApi.md#delete_collection) | **DELETE** /v1/applications/{applicationId}/campaigns/{campaignId}/collections/{collectionId} | Delete campaign-level collection |
| [**delete_coupon**](ManagementApi.md#delete_coupon) | **DELETE** /v1/applications/{applicationId}/campaigns/{campaignId}/coupons/{couponId} | Delete coupon |
| [**delete_coupons**](ManagementApi.md#delete_coupons) | **DELETE** /v1/applications/{applicationId}/campaigns/{campaignId}/coupons | Delete coupons |
| [**delete_loyalty_card**](ManagementApi.md#delete_loyalty_card) | **DELETE** /v1/loyalty_programs/{loyaltyProgramId}/cards/{loyaltyCardId} | Delete loyalty card |
| [**delete_referral**](ManagementApi.md#delete_referral) | **DELETE** /v1/applications/{applicationId}/campaigns/{campaignId}/referrals/{referralId} | Delete referral |
| [**delete_store**](ManagementApi.md#delete_store) | **DELETE** /v1/applications/{applicationId}/stores/{storeId} | Delete store |
| [**delete_user**](ManagementApi.md#delete_user) | **DELETE** /v1/users/{userId} | Delete user |
| [**delete_user_by_email**](ManagementApi.md#delete_user_by_email) | **POST** /v1/users/delete | Delete user by email address |
| [**destroy_session**](ManagementApi.md#destroy_session) | **DELETE** /v1/sessions | Destroy session |
| [**disconnect_campaign_stores**](ManagementApi.md#disconnect_campaign_stores) | **DELETE** /v1/applications/{applicationId}/campaigns/{campaignId}/stores | Disconnect stores |
| [**export_account_collection_items**](ManagementApi.md#export_account_collection_items) | **GET** /v1/collections/{collectionId}/export | Export account-level collection&#39;s items |
| [**export_achievements**](ManagementApi.md#export_achievements) | **GET** /v1/applications/{applicationId}/campaigns/{campaignId}/achievements/{achievementId}/export | Export achievement customer data |
| [**export_audiences_memberships**](ManagementApi.md#export_audiences_memberships) | **GET** /v1/audiences/{audienceId}/memberships/export | Export audience members |
| [**export_campaign_store_budgets**](ManagementApi.md#export_campaign_store_budgets) | **GET** /v1/applications/{applicationId}/campaigns/{campaignId}/stores/budgets/export | Export campaign store budgets |
| [**export_campaign_stores**](ManagementApi.md#export_campaign_stores) | **GET** /v1/applications/{applicationId}/campaigns/{campaignId}/stores/export | Export stores |
| [**export_collection_items**](ManagementApi.md#export_collection_items) | **GET** /v1/applications/{applicationId}/campaigns/{campaignId}/collections/{collectionId}/export | Export campaign-level collection&#39;s items |
| [**export_coupons**](ManagementApi.md#export_coupons) | **GET** /v1/applications/{applicationId}/export_coupons | Export coupons |
| [**export_customer_sessions**](ManagementApi.md#export_customer_sessions) | **GET** /v1/applications/{applicationId}/export_customer_sessions | Export customer sessions |
| [**export_customers_tiers**](ManagementApi.md#export_customers_tiers) | **GET** /v1/loyalty_programs/{loyaltyProgramId}/export_customers_tiers | Export customers&#39; tier data |
| [**export_effects**](ManagementApi.md#export_effects) | **GET** /v1/applications/{applicationId}/export_effects | Export triggered effects |
| [**export_loyalty_balance**](ManagementApi.md#export_loyalty_balance) | **GET** /v1/loyalty_programs/{loyaltyProgramId}/export_customer_balance | Export customer loyalty balance to CSV |
| [**export_loyalty_balances**](ManagementApi.md#export_loyalty_balances) | **GET** /v1/loyalty_programs/{loyaltyProgramId}/export_customer_balances | Export customer loyalty balances |
| [**export_loyalty_card_balances**](ManagementApi.md#export_loyalty_card_balances) | **GET** /v1/loyalty_programs/{loyaltyProgramId}/export_card_balances | Export all card transaction logs |
| [**export_loyalty_card_ledger**](ManagementApi.md#export_loyalty_card_ledger) | **GET** /v1/loyalty_programs/{loyaltyProgramId}/cards/{loyaltyCardId}/export_log | Export card&#39;s ledger log |
| [**export_loyalty_cards**](ManagementApi.md#export_loyalty_cards) | **GET** /v1/loyalty_programs/{loyaltyProgramId}/cards/export | Export loyalty cards |
| [**export_loyalty_ledger**](ManagementApi.md#export_loyalty_ledger) | **GET** /v1/loyalty_programs/{loyaltyProgramId}/profile/{integrationId}/export_log | Export customer&#39;s transaction logs |
| [**export_pool_giveaways**](ManagementApi.md#export_pool_giveaways) | **GET** /v1/giveaways/pools/{poolId}/export | Export giveaway codes of a giveaway pool |
| [**export_referrals**](ManagementApi.md#export_referrals) | **GET** /v1/applications/{applicationId}/export_referrals | Export referrals |
| [**generate_coupon_rejections**](ManagementApi.md#generate_coupon_rejections) | **GET** /v1/coupon_rejections | Summarize coupon redemption failures in session |
| [**get_access_logs_without_total_count**](ManagementApi.md#get_access_logs_without_total_count) | **GET** /v1/applications/{applicationId}/access_logs/no_total | Get access logs for Application |
| [**get_account**](ManagementApi.md#get_account) | **GET** /v1/accounts/{accountId} | Get account details |
| [**get_account_analytics**](ManagementApi.md#get_account_analytics) | **GET** /v1/accounts/{accountId}/analytics | Get account analytics |
| [**get_account_collection**](ManagementApi.md#get_account_collection) | **GET** /v1/collections/{collectionId} | Get account-level collection |
| [**get_achievement**](ManagementApi.md#get_achievement) | **GET** /v1/applications/{applicationId}/campaigns/{campaignId}/achievements/{achievementId} | Get achievement |
| [**get_additional_cost**](ManagementApi.md#get_additional_cost) | **GET** /v1/additional_costs/{additionalCostId} | Get additional cost |
| [**get_additional_costs**](ManagementApi.md#get_additional_costs) | **GET** /v1/additional_costs | List additional costs |
| [**get_application**](ManagementApi.md#get_application) | **GET** /v1/applications/{applicationId} | Get Application |
| [**get_application_api_health**](ManagementApi.md#get_application_api_health) | **GET** /v1/applications/{applicationId}/health_report | Get Application health |
| [**get_application_customer**](ManagementApi.md#get_application_customer) | **GET** /v1/applications/{applicationId}/customers/{customerId} | Get application&#39;s customer |
| [**get_application_customer_friends**](ManagementApi.md#get_application_customer_friends) | **GET** /v1/applications/{applicationId}/profile/{integrationId}/friends | List friends referred by customer profile |
| [**get_application_customers**](ManagementApi.md#get_application_customers) | **GET** /v1/applications/{applicationId}/customers | List application&#39;s customers |
| [**get_application_customers_by_attributes**](ManagementApi.md#get_application_customers_by_attributes) | **POST** /v1/applications/{applicationId}/customer_search | List application customers matching the given attributes |
| [**get_application_event_types**](ManagementApi.md#get_application_event_types) | **GET** /v1/applications/{applicationId}/event_types | List Applications event types |
| [**get_application_events_without_total_count**](ManagementApi.md#get_application_events_without_total_count) | **GET** /v1/applications/{applicationId}/events/no_total | List Applications events |
| [**get_application_session**](ManagementApi.md#get_application_session) | **GET** /v1/applications/{applicationId}/sessions/{sessionId} | Get Application session |
| [**get_application_sessions**](ManagementApi.md#get_application_sessions) | **GET** /v1/applications/{applicationId}/sessions | List Application sessions |
| [**get_applications**](ManagementApi.md#get_applications) | **GET** /v1/applications | List Applications |
| [**get_attribute**](ManagementApi.md#get_attribute) | **GET** /v1/attributes/{attributeId} | Get custom attribute |
| [**get_attributes**](ManagementApi.md#get_attributes) | **GET** /v1/attributes | List custom attributes |
| [**get_audience_memberships**](ManagementApi.md#get_audience_memberships) | **GET** /v1/audiences/{audienceId}/memberships | List audience members |
| [**get_audiences**](ManagementApi.md#get_audiences) | **GET** /v1/audiences | List audiences |
| [**get_audiences_analytics**](ManagementApi.md#get_audiences_analytics) | **GET** /v1/audiences/analytics | List audience analytics |
| [**get_campaign**](ManagementApi.md#get_campaign) | **GET** /v1/applications/{applicationId}/campaigns/{campaignId} | Get campaign |
| [**get_campaign_analytics**](ManagementApi.md#get_campaign_analytics) | **GET** /v1/applications/{applicationId}/campaigns/{campaignId}/analytics | Get analytics of campaigns |
| [**get_campaign_by_attributes**](ManagementApi.md#get_campaign_by_attributes) | **POST** /v1/applications/{applicationId}/campaigns_search | List campaigns that match the given attributes |
| [**get_campaign_group**](ManagementApi.md#get_campaign_group) | **GET** /v1/campaign_groups/{campaignGroupId} | Get campaign access group |
| [**get_campaign_groups**](ManagementApi.md#get_campaign_groups) | **GET** /v1/campaign_groups | List campaign access groups |
| [**get_campaign_templates**](ManagementApi.md#get_campaign_templates) | **GET** /v1/campaign_templates | List campaign templates |
| [**get_campaigns**](ManagementApi.md#get_campaigns) | **GET** /v1/applications/{applicationId}/campaigns | List campaigns |
| [**get_changes**](ManagementApi.md#get_changes) | **GET** /v1/changes | Get audit logs for an account |
| [**get_collection**](ManagementApi.md#get_collection) | **GET** /v1/applications/{applicationId}/campaigns/{campaignId}/collections/{collectionId} | Get campaign-level collection |
| [**get_collection_items**](ManagementApi.md#get_collection_items) | **GET** /v1/collections/{collectionId}/items | Get collection items |
| [**get_coupons_without_total_count**](ManagementApi.md#get_coupons_without_total_count) | **GET** /v1/applications/{applicationId}/campaigns/{campaignId}/coupons/no_total | List coupons |
| [**get_customer_activity_report**](ManagementApi.md#get_customer_activity_report) | **GET** /v1/applications/{applicationId}/customer_activity_reports/{customerId} | Get customer&#39;s activity report |
| [**get_customer_activity_reports_without_total_count**](ManagementApi.md#get_customer_activity_reports_without_total_count) | **GET** /v1/applications/{applicationId}/customer_activity_reports/no_total | Get Activity Reports for Application Customers |
| [**get_customer_analytics**](ManagementApi.md#get_customer_analytics) | **GET** /v1/applications/{applicationId}/customers/{customerId}/analytics | Get customer&#39;s analytics report |
| [**get_customer_profile**](ManagementApi.md#get_customer_profile) | **GET** /v1/customers/{customerId} | Get customer profile |
| [**get_customer_profile_achievement_progress**](ManagementApi.md#get_customer_profile_achievement_progress) | **GET** /v1/applications/{applicationId}/achievement_progress/{integrationId} | List customer achievements |
| [**get_customer_profiles**](ManagementApi.md#get_customer_profiles) | **GET** /v1/customers/no_total | List customer profiles |
| [**get_customers_by_attributes**](ManagementApi.md#get_customers_by_attributes) | **POST** /v1/customer_search/no_total | List customer profiles matching the given attributes |
| [**get_dashboard_statistics**](ManagementApi.md#get_dashboard_statistics) | **GET** /v1/loyalty_programs/{loyaltyProgramId}/dashboard | Get statistics for loyalty dashboard |
| [**get_event_types**](ManagementApi.md#get_event_types) | **GET** /v1/event_types | List event types |
| [**get_exports**](ManagementApi.md#get_exports) | **GET** /v1/exports | Get exports |
| [**get_loyalty_card**](ManagementApi.md#get_loyalty_card) | **GET** /v1/loyalty_programs/{loyaltyProgramId}/cards/{loyaltyCardId} | Get loyalty card |
| [**get_loyalty_card_transaction_logs**](ManagementApi.md#get_loyalty_card_transaction_logs) | **GET** /v1/loyalty_programs/{loyaltyProgramId}/cards/{loyaltyCardId}/logs | List card&#39;s transactions |
| [**get_loyalty_cards**](ManagementApi.md#get_loyalty_cards) | **GET** /v1/loyalty_programs/{loyaltyProgramId}/cards | List loyalty cards |
| [**get_loyalty_ledger_balances**](ManagementApi.md#get_loyalty_ledger_balances) | **GET** /v1/loyalty_programs/{loyaltyProgramId}/profile/{integrationId}/ledger_balances | Get customer&#39;s loyalty balances |
| [**get_loyalty_points**](ManagementApi.md#get_loyalty_points) | **GET** /v1/loyalty_programs/{loyaltyProgramId}/profile/{integrationId} | Get customer&#39;s full loyalty ledger |
| [**get_loyalty_program**](ManagementApi.md#get_loyalty_program) | **GET** /v1/loyalty_programs/{loyaltyProgramId} | Get loyalty program |
| [**get_loyalty_program_profile_ledger_transactions**](ManagementApi.md#get_loyalty_program_profile_ledger_transactions) | **GET** /v1/loyalty_programs/{loyaltyProgramId}/profile/{integrationId}/ledger_transactions | List customer&#39;s loyalty transactions |
| [**get_loyalty_program_transactions**](ManagementApi.md#get_loyalty_program_transactions) | **GET** /v1/loyalty_programs/{loyaltyProgramId}/transactions | List loyalty program transactions |
| [**get_loyalty_programs**](ManagementApi.md#get_loyalty_programs) | **GET** /v1/loyalty_programs | List loyalty programs |
| [**get_loyalty_statistics**](ManagementApi.md#get_loyalty_statistics) | **GET** /v1/loyalty_programs/{loyaltyProgramId}/statistics | Get loyalty program statistics |
| [**get_message_logs**](ManagementApi.md#get_message_logs) | **GET** /v1/message_logs | List message log entries |
| [**get_referrals_without_total_count**](ManagementApi.md#get_referrals_without_total_count) | **GET** /v1/applications/{applicationId}/campaigns/{campaignId}/referrals/no_total | List referrals |
| [**get_role_v2**](ManagementApi.md#get_role_v2) | **GET** /v2/roles/{roleId} | Get role |
| [**get_ruleset**](ManagementApi.md#get_ruleset) | **GET** /v1/applications/{applicationId}/campaigns/{campaignId}/rulesets/{rulesetId} | Get ruleset |
| [**get_rulesets**](ManagementApi.md#get_rulesets) | **GET** /v1/applications/{applicationId}/campaigns/{campaignId}/rulesets | List campaign rulesets |
| [**get_store**](ManagementApi.md#get_store) | **GET** /v1/applications/{applicationId}/stores/{storeId} | Get store |
| [**get_user**](ManagementApi.md#get_user) | **GET** /v1/users/{userId} | Get user |
| [**get_users**](ManagementApi.md#get_users) | **GET** /v1/users | List users in account |
| [**get_webhook**](ManagementApi.md#get_webhook) | **GET** /v1/webhooks/{webhookId} | Get webhook |
| [**get_webhooks**](ManagementApi.md#get_webhooks) | **GET** /v1/webhooks | List webhooks |
| [**import_account_collection**](ManagementApi.md#import_account_collection) | **POST** /v1/collections/{collectionId}/import | Import data into existing account-level collection |
| [**import_allowed_list**](ManagementApi.md#import_allowed_list) | **POST** /v1/attributes/{attributeId}/allowed_list/import | Import allowed values for attribute |
| [**import_audiences_memberships**](ManagementApi.md#import_audiences_memberships) | **POST** /v1/audiences/{audienceId}/memberships/import | Import audience members |
| [**import_campaign_store_budget**](ManagementApi.md#import_campaign_store_budget) | **POST** /v1/applications/{applicationId}/campaigns/{campaignId}/stores/budgets/import | Import campaign store budgets |
| [**import_campaign_stores**](ManagementApi.md#import_campaign_stores) | **POST** /v1/applications/{applicationId}/campaigns/{campaignId}/stores/import | Import stores |
| [**import_collection**](ManagementApi.md#import_collection) | **POST** /v1/applications/{applicationId}/campaigns/{campaignId}/collections/{collectionId}/import | Import data into existing campaign-level collection |
| [**import_coupons**](ManagementApi.md#import_coupons) | **POST** /v1/applications/{applicationId}/campaigns/{campaignId}/import_coupons | Import coupons |
| [**import_loyalty_cards**](ManagementApi.md#import_loyalty_cards) | **POST** /v1/loyalty_programs/{loyaltyProgramId}/import_cards | Import loyalty cards |
| [**import_loyalty_customers_tiers**](ManagementApi.md#import_loyalty_customers_tiers) | **POST** /v1/loyalty_programs/{loyaltyProgramId}/import_customers_tiers | Import customers into loyalty tiers |
| [**import_loyalty_points**](ManagementApi.md#import_loyalty_points) | **POST** /v1/loyalty_programs/{loyaltyProgramId}/import_points | Import loyalty points |
| [**import_pool_giveaways**](ManagementApi.md#import_pool_giveaways) | **POST** /v1/giveaways/pools/{poolId}/import | Import giveaway codes into a giveaway pool |
| [**import_referrals**](ManagementApi.md#import_referrals) | **POST** /v1/applications/{applicationId}/campaigns/{campaignId}/import_referrals | Import referrals |
| [**invite_user_external**](ManagementApi.md#invite_user_external) | **POST** /v1/users/invite | Invite user from identity provider |
| [**list_account_collections**](ManagementApi.md#list_account_collections) | **GET** /v1/collections | List collections in account |
| [**list_achievements**](ManagementApi.md#list_achievements) | **GET** /v1/applications/{applicationId}/campaigns/{campaignId}/achievements | List achievements |
| [**list_all_roles_v2**](ManagementApi.md#list_all_roles_v2) | **GET** /v2/roles | List roles |
| [**list_campaign_store_budget_limits**](ManagementApi.md#list_campaign_store_budget_limits) | **GET** /v1/applications/{applicationId}/campaigns/{campaignId}/stores/budgets | List campaign store budget limits |
| [**list_catalog_items**](ManagementApi.md#list_catalog_items) | **GET** /v1/catalogs/{catalogId}/items | List items in a catalog |
| [**list_collections**](ManagementApi.md#list_collections) | **GET** /v1/applications/{applicationId}/campaigns/{campaignId}/collections | List collections in campaign |
| [**list_collections_in_application**](ManagementApi.md#list_collections_in_application) | **GET** /v1/applications/{applicationId}/collections | List collections in Application |
| [**list_stores**](ManagementApi.md#list_stores) | **GET** /v1/applications/{applicationId}/stores | List stores |
| [**okta_event_handler_challenge**](ManagementApi.md#okta_event_handler_challenge) | **GET** /v1/provisioning/okta | Validate Okta API ownership |
| [**remove_loyalty_points**](ManagementApi.md#remove_loyalty_points) | **PUT** /v1/loyalty_programs/{loyaltyProgramId}/profile/{integrationId}/deduct_points | Deduct points from customer profile |
| [**reset_password**](ManagementApi.md#reset_password) | **POST** /v1/reset_password | Reset password |
| [**scim_create_group**](ManagementApi.md#scim_create_group) | **POST** /v1/provisioning/scim/Groups | Create SCIM group |
| [**scim_create_user**](ManagementApi.md#scim_create_user) | **POST** /v1/provisioning/scim/Users | Create SCIM user |
| [**scim_delete_group**](ManagementApi.md#scim_delete_group) | **DELETE** /v1/provisioning/scim/Groups/{groupId} | Delete SCIM group |
| [**scim_delete_user**](ManagementApi.md#scim_delete_user) | **DELETE** /v1/provisioning/scim/Users/{userId} | Delete SCIM user |
| [**scim_get_group**](ManagementApi.md#scim_get_group) | **GET** /v1/provisioning/scim/Groups/{groupId} | Get SCIM group |
| [**scim_get_groups**](ManagementApi.md#scim_get_groups) | **GET** /v1/provisioning/scim/Groups | List SCIM groups |
| [**scim_get_resource_types**](ManagementApi.md#scim_get_resource_types) | **GET** /v1/provisioning/scim/ResourceTypes | List supported SCIM resource types |
| [**scim_get_schemas**](ManagementApi.md#scim_get_schemas) | **GET** /v1/provisioning/scim/Schemas | List supported SCIM schemas |
| [**scim_get_service_provider_config**](ManagementApi.md#scim_get_service_provider_config) | **GET** /v1/provisioning/scim/ServiceProviderConfig | Get SCIM service provider configuration |
| [**scim_get_user**](ManagementApi.md#scim_get_user) | **GET** /v1/provisioning/scim/Users/{userId} | Get SCIM user |
| [**scim_get_users**](ManagementApi.md#scim_get_users) | **GET** /v1/provisioning/scim/Users | List SCIM users |
| [**scim_patch_group**](ManagementApi.md#scim_patch_group) | **PATCH** /v1/provisioning/scim/Groups/{groupId} | Update SCIM group attributes |
| [**scim_patch_user**](ManagementApi.md#scim_patch_user) | **PATCH** /v1/provisioning/scim/Users/{userId} | Update SCIM user attributes |
| [**scim_replace_group_attributes**](ManagementApi.md#scim_replace_group_attributes) | **PUT** /v1/provisioning/scim/Groups/{groupId} | Update SCIM group |
| [**scim_replace_user_attributes**](ManagementApi.md#scim_replace_user_attributes) | **PUT** /v1/provisioning/scim/Users/{userId} | Update SCIM user |
| [**search_coupons_advanced_application_wide_without_total_count**](ManagementApi.md#search_coupons_advanced_application_wide_without_total_count) | **POST** /v1/applications/{applicationId}/coupons_search_advanced/no_total | List coupons that match the given attributes (without total count) |
| [**search_coupons_advanced_without_total_count**](ManagementApi.md#search_coupons_advanced_without_total_count) | **POST** /v1/applications/{applicationId}/campaigns/{campaignId}/coupons_search_advanced/no_total | List coupons that match the given attributes in campaign (without total count) |
| [**summarize_campaign_store_budget**](ManagementApi.md#summarize_campaign_store_budget) | **GET** /v1/applications/{applicationId}/campaigns/{campaignId}/stores/budgets/summary | Get summary of campaign store budgets |
| [**transfer_loyalty_card**](ManagementApi.md#transfer_loyalty_card) | **PUT** /v1/loyalty_programs/{loyaltyProgramId}/cards/{loyaltyCardId}/transfer | Transfer card data |
| [**update_account_collection**](ManagementApi.md#update_account_collection) | **PUT** /v1/collections/{collectionId} | Update account-level collection |
| [**update_achievement**](ManagementApi.md#update_achievement) | **PUT** /v1/applications/{applicationId}/campaigns/{campaignId}/achievements/{achievementId} | Update achievement |
| [**update_additional_cost**](ManagementApi.md#update_additional_cost) | **PUT** /v1/additional_costs/{additionalCostId} | Update additional cost |
| [**update_attribute**](ManagementApi.md#update_attribute) | **PUT** /v1/attributes/{attributeId} | Update custom attribute |
| [**update_campaign**](ManagementApi.md#update_campaign) | **PUT** /v1/applications/{applicationId}/campaigns/{campaignId} | Update campaign |
| [**update_collection**](ManagementApi.md#update_collection) | **PUT** /v1/applications/{applicationId}/campaigns/{campaignId}/collections/{collectionId} | Update campaign-level collection&#39;s description |
| [**update_coupon**](ManagementApi.md#update_coupon) | **PUT** /v1/applications/{applicationId}/campaigns/{campaignId}/coupons/{couponId} | Update coupon |
| [**update_coupon_batch**](ManagementApi.md#update_coupon_batch) | **PUT** /v1/applications/{applicationId}/campaigns/{campaignId}/coupons | Update coupons |
| [**update_loyalty_card**](ManagementApi.md#update_loyalty_card) | **PUT** /v1/loyalty_programs/{loyaltyProgramId}/cards/{loyaltyCardId} | Update loyalty card status |
| [**update_referral**](ManagementApi.md#update_referral) | **PUT** /v1/applications/{applicationId}/campaigns/{campaignId}/referrals/{referralId} | Update referral |
| [**update_role_v2**](ManagementApi.md#update_role_v2) | **PUT** /v2/roles/{roleId} | Update role |
| [**update_store**](ManagementApi.md#update_store) | **PUT** /v1/applications/{applicationId}/stores/{storeId} | Update store |
| [**update_user**](ManagementApi.md#update_user) | **PUT** /v1/users/{userId} | Update user |


## activate_user_by_email

> activate_user_by_email(activate_user_request)

Enable user by email address

Enable a [disabled user](https://docs.talon.one/docs/product/account/account-settings/managing-users#disabling-a-user) by their email address. 

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
activate_user_request = TalonOne::ActivateUserRequest.new({email: 'john.doe@example.com'}) # ActivateUserRequest | body

begin
  # Enable user by email address
  api_instance.activate_user_by_email(activate_user_request)
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->activate_user_by_email: #{e}"
end
```

#### Using the activate_user_by_email_with_http_info variant

This returns an Array which contains the response data (`nil` in this case), status code and headers.

> <Array(nil, Integer, Hash)> activate_user_by_email_with_http_info(activate_user_request)

```ruby
begin
  # Enable user by email address
  data, status_code, headers = api_instance.activate_user_by_email_with_http_info(activate_user_request)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => nil
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->activate_user_by_email_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **activate_user_request** | [**ActivateUserRequest**](ActivateUserRequest.md) | body |  |

### Return type

nil (empty response body)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined


## add_loyalty_card_points

> add_loyalty_card_points(loyalty_program_id, loyalty_card_id, add_loyalty_points)

Add points to card

Add points to the given loyalty card in the specified card-based loyalty program. 

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
loyalty_program_id = 789 # Integer | Identifier of the card-based loyalty program containing the loyalty card. You can get the ID with the [List loyalty programs](https://docs.talon.one/management-api#tag/Loyalty/operation/getLoyaltyPrograms) endpoint. 
loyalty_card_id = 'loyalty_card_id_example' # String | Identifier of the loyalty card. You can get the identifier with the [List loyalty cards](https://docs.talon.one/management-api#tag/Loyalty-cards/operation/getLoyaltyCards) endpoint. 
add_loyalty_points = TalonOne::AddLoyaltyPoints.new({points: 300}) # AddLoyaltyPoints | body

begin
  # Add points to card
  api_instance.add_loyalty_card_points(loyalty_program_id, loyalty_card_id, add_loyalty_points)
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->add_loyalty_card_points: #{e}"
end
```

#### Using the add_loyalty_card_points_with_http_info variant

This returns an Array which contains the response data (`nil` in this case), status code and headers.

> <Array(nil, Integer, Hash)> add_loyalty_card_points_with_http_info(loyalty_program_id, loyalty_card_id, add_loyalty_points)

```ruby
begin
  # Add points to card
  data, status_code, headers = api_instance.add_loyalty_card_points_with_http_info(loyalty_program_id, loyalty_card_id, add_loyalty_points)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => nil
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->add_loyalty_card_points_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **loyalty_program_id** | **Integer** | Identifier of the card-based loyalty program containing the loyalty card. You can get the ID with the [List loyalty programs](https://docs.talon.one/management-api#tag/Loyalty/operation/getLoyaltyPrograms) endpoint.  |  |
| **loyalty_card_id** | **String** | Identifier of the loyalty card. You can get the identifier with the [List loyalty cards](https://docs.talon.one/management-api#tag/Loyalty-cards/operation/getLoyaltyCards) endpoint.  |  |
| **add_loyalty_points** | [**AddLoyaltyPoints**](AddLoyaltyPoints.md) | body |  |

### Return type

nil (empty response body)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## add_loyalty_points

> add_loyalty_points(loyalty_program_id, integration_id, add_loyalty_points)

Add points to customer profile

Add points in the specified loyalty program for the given customer.  To get the `integrationId` of the profile from a `sessionId`, use the [Update customer session](https://docs.talon.one/integration-api#operation/updateCustomerSessionV2) endpoint. 

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
loyalty_program_id = 'loyalty_program_id_example' # String | The identifier for the loyalty program.
integration_id = 'integration_id_example' # String | The integration identifier for this customer profile. Must be: - Unique within the deployment. - Stable for the customer. Do not use an ID that the customer can update themselves. For example, you can use a database ID.  Once set, you cannot update this identifier. 
add_loyalty_points = TalonOne::AddLoyaltyPoints.new({points: 300}) # AddLoyaltyPoints | body

begin
  # Add points to customer profile
  api_instance.add_loyalty_points(loyalty_program_id, integration_id, add_loyalty_points)
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->add_loyalty_points: #{e}"
end
```

#### Using the add_loyalty_points_with_http_info variant

This returns an Array which contains the response data (`nil` in this case), status code and headers.

> <Array(nil, Integer, Hash)> add_loyalty_points_with_http_info(loyalty_program_id, integration_id, add_loyalty_points)

```ruby
begin
  # Add points to customer profile
  data, status_code, headers = api_instance.add_loyalty_points_with_http_info(loyalty_program_id, integration_id, add_loyalty_points)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => nil
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->add_loyalty_points_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **loyalty_program_id** | **String** | The identifier for the loyalty program. |  |
| **integration_id** | **String** | The integration identifier for this customer profile. Must be: - Unique within the deployment. - Stable for the customer. Do not use an ID that the customer can update themselves. For example, you can use a database ID.  Once set, you cannot update this identifier.  |  |
| **add_loyalty_points** | [**AddLoyaltyPoints**](AddLoyaltyPoints.md) | body |  |

### Return type

nil (empty response body)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## copy_campaign_to_applications

> <GetCampaigns200Response> copy_campaign_to_applications(application_id, campaign_id, campaign_copy)

Copy the campaign into the specified Application

Copy the campaign into all specified Applications.

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
application_id = 789 # Integer | The ID of the Application. It is displayed in your Talon.One deployment URL.
campaign_id = 789 # Integer | The ID of the campaign. It is displayed in your Talon.One deployment URL.
campaign_copy = TalonOne::CampaignCopy.new({application_ids: [1,  2,  3]}) # CampaignCopy | body

begin
  # Copy the campaign into the specified Application
  result = api_instance.copy_campaign_to_applications(application_id, campaign_id, campaign_copy)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->copy_campaign_to_applications: #{e}"
end
```

#### Using the copy_campaign_to_applications_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<GetCampaigns200Response>, Integer, Hash)> copy_campaign_to_applications_with_http_info(application_id, campaign_id, campaign_copy)

```ruby
begin
  # Copy the campaign into the specified Application
  data, status_code, headers = api_instance.copy_campaign_to_applications_with_http_info(application_id, campaign_id, campaign_copy)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <GetCampaigns200Response>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->copy_campaign_to_applications_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **application_id** | **Integer** | The ID of the Application. It is displayed in your Talon.One deployment URL. |  |
| **campaign_id** | **Integer** | The ID of the campaign. It is displayed in your Talon.One deployment URL. |  |
| **campaign_copy** | [**CampaignCopy**](CampaignCopy.md) | body |  |

### Return type

[**GetCampaigns200Response**](GetCampaigns200Response.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## create_account_collection

> <Collection> create_account_collection(new_collection)

Create account-level collection

Create an account-level collection.

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
new_collection = TalonOne::NewCollection.new({name: 'My collection'}) # NewCollection | body

begin
  # Create account-level collection
  result = api_instance.create_account_collection(new_collection)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->create_account_collection: #{e}"
end
```

#### Using the create_account_collection_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<Collection>, Integer, Hash)> create_account_collection_with_http_info(new_collection)

```ruby
begin
  # Create account-level collection
  data, status_code, headers = api_instance.create_account_collection_with_http_info(new_collection)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <Collection>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->create_account_collection_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **new_collection** | [**NewCollection**](NewCollection.md) | body |  |

### Return type

[**Collection**](Collection.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## create_achievement

> <Achievement> create_achievement(application_id, campaign_id, create_achievement)

Create achievement

Create a new achievement in a specific campaign.

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
application_id = 789 # Integer | The ID of the Application. It is displayed in your Talon.One deployment URL.
campaign_id = 789 # Integer | The ID of the campaign. It is displayed in your Talon.One deployment URL.
create_achievement = TalonOne::CreateAchievement.new({name: 'Order50Discount', title: '50% off on 50th purchase.', description: '50% off for every 50th purchase in a year.', target: 50}) # CreateAchievement | body

begin
  # Create achievement
  result = api_instance.create_achievement(application_id, campaign_id, create_achievement)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->create_achievement: #{e}"
end
```

#### Using the create_achievement_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<Achievement>, Integer, Hash)> create_achievement_with_http_info(application_id, campaign_id, create_achievement)

```ruby
begin
  # Create achievement
  data, status_code, headers = api_instance.create_achievement_with_http_info(application_id, campaign_id, create_achievement)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <Achievement>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->create_achievement_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **application_id** | **Integer** | The ID of the Application. It is displayed in your Talon.One deployment URL. |  |
| **campaign_id** | **Integer** | The ID of the campaign. It is displayed in your Talon.One deployment URL. |  |
| **create_achievement** | [**CreateAchievement**](CreateAchievement.md) | body |  |

### Return type

[**Achievement**](Achievement.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## create_additional_cost

> <AccountAdditionalCost> create_additional_cost(new_additional_cost)

Create additional cost

Create an [additional cost](https://docs.talon.one/docs/product/account/dev-tools/managing-additional-costs).  These additional costs are shared across all applications in your account, and are never required. 

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
new_additional_cost = TalonOne::NewAdditionalCost.new({name: 'shippingFee', title: 'Shipping fee', description: 'A shipping fee'}) # NewAdditionalCost | body

begin
  # Create additional cost
  result = api_instance.create_additional_cost(new_additional_cost)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->create_additional_cost: #{e}"
end
```

#### Using the create_additional_cost_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<AccountAdditionalCost>, Integer, Hash)> create_additional_cost_with_http_info(new_additional_cost)

```ruby
begin
  # Create additional cost
  data, status_code, headers = api_instance.create_additional_cost_with_http_info(new_additional_cost)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <AccountAdditionalCost>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->create_additional_cost_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **new_additional_cost** | [**NewAdditionalCost**](NewAdditionalCost.md) | body |  |

### Return type

[**AccountAdditionalCost**](AccountAdditionalCost.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## create_attribute

> <Attribute> create_attribute(new_attribute)

Create custom attribute

Create a _custom attribute_ in this account. [Custom attributes](https://docs.talon.one/docs/dev/concepts/attributes) allow you to add data to Talon.One domain entities like campaigns, coupons, customers and so on.  These attributes can then be given values when creating/updating these entities, and these values can be used in your campaign rules.  For example, you could define a `zipCode` field for customer sessions, and add a rule to your campaign that only allows certain ZIP codes.  These attributes are shared across all Applications in your account and are never required. 

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
new_attribute = TalonOne::NewAttribute.new({entity: 'Application', name: 'pageViewed', title: 'Page view event', type: 'string', description: 'Event triggered when a customer displays a page.', suggestions: ['suggestions_example'], editable: true}) # NewAttribute | body

begin
  # Create custom attribute
  result = api_instance.create_attribute(new_attribute)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->create_attribute: #{e}"
end
```

#### Using the create_attribute_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<Attribute>, Integer, Hash)> create_attribute_with_http_info(new_attribute)

```ruby
begin
  # Create custom attribute
  data, status_code, headers = api_instance.create_attribute_with_http_info(new_attribute)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <Attribute>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->create_attribute_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **new_attribute** | [**NewAttribute**](NewAttribute.md) | body |  |

### Return type

[**Attribute**](Attribute.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## create_batch_loyalty_cards

> <LoyaltyCardBatchResponse> create_batch_loyalty_cards(loyalty_program_id, loyalty_card_batch)

Create loyalty cards

Create a batch of loyalty cards in a specified [card-based loyalty program](https://docs.talon.one/docs/product/loyalty-programs/overview#loyalty-program-types).  Customers can use loyalty cards to collect and spend loyalty points.  **Important:**  - The specified card-based loyalty program must have a defined card code format that is used to generate the loyalty card codes. - Trying to create more than 20,000 loyalty cards in a single request returns an error message with a `400` status code. 

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
loyalty_program_id = 789 # Integer | Identifier of the card-based loyalty program containing the loyalty card. You can get the ID with the [List loyalty programs](https://docs.talon.one/management-api#tag/Loyalty/operation/getLoyaltyPrograms) endpoint. 
loyalty_card_batch = TalonOne::LoyaltyCardBatch.new({number_of_cards: 5000}) # LoyaltyCardBatch | body

begin
  # Create loyalty cards
  result = api_instance.create_batch_loyalty_cards(loyalty_program_id, loyalty_card_batch)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->create_batch_loyalty_cards: #{e}"
end
```

#### Using the create_batch_loyalty_cards_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<LoyaltyCardBatchResponse>, Integer, Hash)> create_batch_loyalty_cards_with_http_info(loyalty_program_id, loyalty_card_batch)

```ruby
begin
  # Create loyalty cards
  data, status_code, headers = api_instance.create_batch_loyalty_cards_with_http_info(loyalty_program_id, loyalty_card_batch)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <LoyaltyCardBatchResponse>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->create_batch_loyalty_cards_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **loyalty_program_id** | **Integer** | Identifier of the card-based loyalty program containing the loyalty card. You can get the ID with the [List loyalty programs](https://docs.talon.one/management-api#tag/Loyalty/operation/getLoyaltyPrograms) endpoint.  |  |
| **loyalty_card_batch** | [**LoyaltyCardBatch**](LoyaltyCardBatch.md) | body |  |

### Return type

[**LoyaltyCardBatchResponse**](LoyaltyCardBatchResponse.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## create_campaign_from_template

> <CreateTemplateCampaignResponse> create_campaign_from_template(application_id, create_template_campaign)

Create campaign from campaign template

Use the campaign template referenced in the request body to create a new campaign in one of the connected Applications.  If the template was created from a campaign with rules referencing [campaign collections](https://docs.talon.one/docs/product/campaigns/managing-collections), the corresponding collections for the new campaign are created automatically. 

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
application_id = 789 # Integer | The ID of the Application. It is displayed in your Talon.One deployment URL.
create_template_campaign = TalonOne::CreateTemplateCampaign.new({name: 'Discount campaign', template_id: 4}) # CreateTemplateCampaign | body

begin
  # Create campaign from campaign template
  result = api_instance.create_campaign_from_template(application_id, create_template_campaign)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->create_campaign_from_template: #{e}"
end
```

#### Using the create_campaign_from_template_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<CreateTemplateCampaignResponse>, Integer, Hash)> create_campaign_from_template_with_http_info(application_id, create_template_campaign)

```ruby
begin
  # Create campaign from campaign template
  data, status_code, headers = api_instance.create_campaign_from_template_with_http_info(application_id, create_template_campaign)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <CreateTemplateCampaignResponse>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->create_campaign_from_template_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **application_id** | **Integer** | The ID of the Application. It is displayed in your Talon.One deployment URL. |  |
| **create_template_campaign** | [**CreateTemplateCampaign**](CreateTemplateCampaign.md) | body |  |

### Return type

[**CreateTemplateCampaignResponse**](CreateTemplateCampaignResponse.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## create_campaign_store_budget

> create_campaign_store_budget(application_id, campaign_id, new_campaign_store_budget)

Create campaign store budget

Create a new store budget for a given campaign.

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
application_id = 789 # Integer | The ID of the Application. It is displayed in your Talon.One deployment URL.
campaign_id = 789 # Integer | The ID of the campaign. It is displayed in your Talon.One deployment URL.
new_campaign_store_budget = TalonOne::NewCampaignStoreBudget.new({action: 'setDiscount', store_limits: [TalonOne::NewCampaignStoreBudgetStoreLimit.new({store_id: 17, limit: 1000})]}) # NewCampaignStoreBudget | body

begin
  # Create campaign store budget
  api_instance.create_campaign_store_budget(application_id, campaign_id, new_campaign_store_budget)
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->create_campaign_store_budget: #{e}"
end
```

#### Using the create_campaign_store_budget_with_http_info variant

This returns an Array which contains the response data (`nil` in this case), status code and headers.

> <Array(nil, Integer, Hash)> create_campaign_store_budget_with_http_info(application_id, campaign_id, new_campaign_store_budget)

```ruby
begin
  # Create campaign store budget
  data, status_code, headers = api_instance.create_campaign_store_budget_with_http_info(application_id, campaign_id, new_campaign_store_budget)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => nil
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->create_campaign_store_budget_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **application_id** | **Integer** | The ID of the Application. It is displayed in your Talon.One deployment URL. |  |
| **campaign_id** | **Integer** | The ID of the campaign. It is displayed in your Talon.One deployment URL. |  |
| **new_campaign_store_budget** | [**NewCampaignStoreBudget**](NewCampaignStoreBudget.md) | body |  |

### Return type

nil (empty response body)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## create_collection

> <Collection> create_collection(application_id, campaign_id, new_campaign_collection)

Create campaign-level collection

Create a campaign-level collection in a given campaign.

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
application_id = 789 # Integer | The ID of the Application. It is displayed in your Talon.One deployment URL.
campaign_id = 789 # Integer | The ID of the campaign. It is displayed in your Talon.One deployment URL.
new_campaign_collection = TalonOne::NewCampaignCollection.new({name: 'My collection'}) # NewCampaignCollection | body

begin
  # Create campaign-level collection
  result = api_instance.create_collection(application_id, campaign_id, new_campaign_collection)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->create_collection: #{e}"
end
```

#### Using the create_collection_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<Collection>, Integer, Hash)> create_collection_with_http_info(application_id, campaign_id, new_campaign_collection)

```ruby
begin
  # Create campaign-level collection
  data, status_code, headers = api_instance.create_collection_with_http_info(application_id, campaign_id, new_campaign_collection)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <Collection>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->create_collection_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **application_id** | **Integer** | The ID of the Application. It is displayed in your Talon.One deployment URL. |  |
| **campaign_id** | **Integer** | The ID of the campaign. It is displayed in your Talon.One deployment URL. |  |
| **new_campaign_collection** | [**NewCampaignCollection**](NewCampaignCollection.md) | body |  |

### Return type

[**Collection**](Collection.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## create_coupons

> <CreateCoupons200Response> create_coupons(application_id, campaign_id, new_coupons, opts)

Create coupons

Create coupons according to some pattern. Up to 20.000 coupons can be created without a unique prefix. When a unique prefix is provided, up to 200.000 coupons can be created.

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
application_id = 789 # Integer | The ID of the Application. It is displayed in your Talon.One deployment URL.
campaign_id = 789 # Integer | The ID of the campaign. It is displayed in your Talon.One deployment URL.
new_coupons = TalonOne::NewCoupons.new({number_of_coupons: 1}) # NewCoupons | body
opts = {
  silent: 'silent_example' # String | Possible values: `yes` or `no`. - `yes`: Increases the performance of the API call by returning a 204 response. - `no`: Returns a 200 response that contains the updated customer profiles. 
}

begin
  # Create coupons
  result = api_instance.create_coupons(application_id, campaign_id, new_coupons, opts)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->create_coupons: #{e}"
end
```

#### Using the create_coupons_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<CreateCoupons200Response>, Integer, Hash)> create_coupons_with_http_info(application_id, campaign_id, new_coupons, opts)

```ruby
begin
  # Create coupons
  data, status_code, headers = api_instance.create_coupons_with_http_info(application_id, campaign_id, new_coupons, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <CreateCoupons200Response>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->create_coupons_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **application_id** | **Integer** | The ID of the Application. It is displayed in your Talon.One deployment URL. |  |
| **campaign_id** | **Integer** | The ID of the campaign. It is displayed in your Talon.One deployment URL. |  |
| **new_coupons** | [**NewCoupons**](NewCoupons.md) | body |  |
| **silent** | **String** | Possible values: &#x60;yes&#x60; or &#x60;no&#x60;. - &#x60;yes&#x60;: Increases the performance of the API call by returning a 204 response. - &#x60;no&#x60;: Returns a 200 response that contains the updated customer profiles.  | [optional][default to &#39;yes&#39;] |

### Return type

[**CreateCoupons200Response**](CreateCoupons200Response.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## create_coupons_async

> <AsyncCouponCreationResponse> create_coupons_async(application_id, campaign_id, new_coupon_creation_job)

Create coupons asynchronously

Create up to 5,000,000 coupons asynchronously. You should typically use this enpdoint when you create at least 20,001 coupons. You receive an email when the creation is complete.  If you want to create less than 20,001 coupons, you can use the [Create coupons](https://docs.talon.one/management-api#tag/Coupons/operation/createCoupons) endpoint. 

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
application_id = 789 # Integer | The ID of the Application. It is displayed in your Talon.One deployment URL.
campaign_id = 789 # Integer | The ID of the campaign. It is displayed in your Talon.One deployment URL.
new_coupon_creation_job = TalonOne::NewCouponCreationJob.new({number_of_coupons: 200000, attributes: 3.56}) # NewCouponCreationJob | body

begin
  # Create coupons asynchronously
  result = api_instance.create_coupons_async(application_id, campaign_id, new_coupon_creation_job)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->create_coupons_async: #{e}"
end
```

#### Using the create_coupons_async_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<AsyncCouponCreationResponse>, Integer, Hash)> create_coupons_async_with_http_info(application_id, campaign_id, new_coupon_creation_job)

```ruby
begin
  # Create coupons asynchronously
  data, status_code, headers = api_instance.create_coupons_async_with_http_info(application_id, campaign_id, new_coupon_creation_job)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <AsyncCouponCreationResponse>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->create_coupons_async_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **application_id** | **Integer** | The ID of the Application. It is displayed in your Talon.One deployment URL. |  |
| **campaign_id** | **Integer** | The ID of the campaign. It is displayed in your Talon.One deployment URL. |  |
| **new_coupon_creation_job** | [**NewCouponCreationJob**](NewCouponCreationJob.md) | body |  |

### Return type

[**AsyncCouponCreationResponse**](AsyncCouponCreationResponse.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## create_coupons_deletion_job

> <AsyncCouponDeletionJobResponse> create_coupons_deletion_job(application_id, campaign_id, new_coupon_deletion_job)

Creates a coupon deletion job

This endpoint handles creating a job to delete coupons asynchronously. 

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
application_id = 789 # Integer | The ID of the Application. It is displayed in your Talon.One deployment URL.
campaign_id = 789 # Integer | The ID of the campaign. It is displayed in your Talon.One deployment URL.
new_coupon_deletion_job = TalonOne::NewCouponDeletionJob.new({filters: TalonOne::CouponDeletionFilters.new}) # NewCouponDeletionJob | body

begin
  # Creates a coupon deletion job
  result = api_instance.create_coupons_deletion_job(application_id, campaign_id, new_coupon_deletion_job)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->create_coupons_deletion_job: #{e}"
end
```

#### Using the create_coupons_deletion_job_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<AsyncCouponDeletionJobResponse>, Integer, Hash)> create_coupons_deletion_job_with_http_info(application_id, campaign_id, new_coupon_deletion_job)

```ruby
begin
  # Creates a coupon deletion job
  data, status_code, headers = api_instance.create_coupons_deletion_job_with_http_info(application_id, campaign_id, new_coupon_deletion_job)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <AsyncCouponDeletionJobResponse>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->create_coupons_deletion_job_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **application_id** | **Integer** | The ID of the Application. It is displayed in your Talon.One deployment URL. |  |
| **campaign_id** | **Integer** | The ID of the campaign. It is displayed in your Talon.One deployment URL. |  |
| **new_coupon_deletion_job** | [**NewCouponDeletionJob**](NewCouponDeletionJob.md) | body |  |

### Return type

[**AsyncCouponDeletionJobResponse**](AsyncCouponDeletionJobResponse.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## create_coupons_for_multiple_recipients

> <CreateCoupons200Response> create_coupons_for_multiple_recipients(application_id, campaign_id, new_coupons_for_multiple_recipients, opts)

Create coupons for multiple recipients

Create coupons according to some pattern for up to 1000 recipients.

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
application_id = 789 # Integer | The ID of the Application. It is displayed in your Talon.One deployment URL.
campaign_id = 789 # Integer | The ID of the campaign. It is displayed in your Talon.One deployment URL.
new_coupons_for_multiple_recipients = TalonOne::NewCouponsForMultipleRecipients.new({recipients_integration_ids: [URNGV8294NV,  BZGGC2454PA]}) # NewCouponsForMultipleRecipients | body
opts = {
  silent: 'silent_example' # String | Possible values: `yes` or `no`. - `yes`: Increases the performance of the API call by returning a 204 response. - `no`: Returns a 200 response that contains the updated customer profiles. 
}

begin
  # Create coupons for multiple recipients
  result = api_instance.create_coupons_for_multiple_recipients(application_id, campaign_id, new_coupons_for_multiple_recipients, opts)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->create_coupons_for_multiple_recipients: #{e}"
end
```

#### Using the create_coupons_for_multiple_recipients_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<CreateCoupons200Response>, Integer, Hash)> create_coupons_for_multiple_recipients_with_http_info(application_id, campaign_id, new_coupons_for_multiple_recipients, opts)

```ruby
begin
  # Create coupons for multiple recipients
  data, status_code, headers = api_instance.create_coupons_for_multiple_recipients_with_http_info(application_id, campaign_id, new_coupons_for_multiple_recipients, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <CreateCoupons200Response>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->create_coupons_for_multiple_recipients_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **application_id** | **Integer** | The ID of the Application. It is displayed in your Talon.One deployment URL. |  |
| **campaign_id** | **Integer** | The ID of the campaign. It is displayed in your Talon.One deployment URL. |  |
| **new_coupons_for_multiple_recipients** | [**NewCouponsForMultipleRecipients**](NewCouponsForMultipleRecipients.md) | body |  |
| **silent** | **String** | Possible values: &#x60;yes&#x60; or &#x60;no&#x60;. - &#x60;yes&#x60;: Increases the performance of the API call by returning a 204 response. - &#x60;no&#x60;: Returns a 200 response that contains the updated customer profiles.  | [optional][default to &#39;yes&#39;] |

### Return type

[**CreateCoupons200Response**](CreateCoupons200Response.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## create_invite_email

> <NewInviteEmail> create_invite_email(new_invite_email)

Resend invitation email

Resend an email invitation to an existing user.  **Note:** The invitation token is valid for 24 hours after the email has been sent. 

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
new_invite_email = TalonOne::NewInviteEmail.new({email: 'john.doe@example.com', token: 'Gy9b8w1irmQtEPo5RmbMmSPheL5h4'}) # NewInviteEmail | body

begin
  # Resend invitation email
  result = api_instance.create_invite_email(new_invite_email)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->create_invite_email: #{e}"
end
```

#### Using the create_invite_email_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<NewInviteEmail>, Integer, Hash)> create_invite_email_with_http_info(new_invite_email)

```ruby
begin
  # Resend invitation email
  data, status_code, headers = api_instance.create_invite_email_with_http_info(new_invite_email)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <NewInviteEmail>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->create_invite_email_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **new_invite_email** | [**NewInviteEmail**](NewInviteEmail.md) | body |  |

### Return type

[**NewInviteEmail**](NewInviteEmail.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## create_invite_v2

> <User> create_invite_v2(new_invitation)

Invite user

Create a new user in the account and send an invitation to their email address.  **Note**: The invitation token is valid for 24 hours after the email has been sent. You can resend an invitation to a user with the [Resend invitation email](https://docs.talon.one/management-api#tag/Accounts-and-users/operation/createInviteEmail) endpoint. 

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
new_invitation = TalonOne::NewInvitation.new({email: 'john.doe@example.com'}) # NewInvitation | body

begin
  # Invite user
  result = api_instance.create_invite_v2(new_invitation)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->create_invite_v2: #{e}"
end
```

#### Using the create_invite_v2_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<User>, Integer, Hash)> create_invite_v2_with_http_info(new_invitation)

```ruby
begin
  # Invite user
  data, status_code, headers = api_instance.create_invite_v2_with_http_info(new_invitation)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <User>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->create_invite_v2_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **new_invitation** | [**NewInvitation**](NewInvitation.md) | body |  |

### Return type

[**User**](User.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## create_password_recovery_email

> <NewPasswordEmail> create_password_recovery_email(new_password_email)

Request a password reset

Send an email with a password recovery link to the email address of an existing account.  **Note:** The password recovery link expires 30 minutes after this endpoint is triggered. 

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
new_password_email = TalonOne::NewPasswordEmail.new({email: 'email_example'}) # NewPasswordEmail | body

begin
  # Request a password reset
  result = api_instance.create_password_recovery_email(new_password_email)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->create_password_recovery_email: #{e}"
end
```

#### Using the create_password_recovery_email_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<NewPasswordEmail>, Integer, Hash)> create_password_recovery_email_with_http_info(new_password_email)

```ruby
begin
  # Request a password reset
  data, status_code, headers = api_instance.create_password_recovery_email_with_http_info(new_password_email)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <NewPasswordEmail>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->create_password_recovery_email_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **new_password_email** | [**NewPasswordEmail**](NewPasswordEmail.md) | body |  |

### Return type

[**NewPasswordEmail**](NewPasswordEmail.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## create_session

> <Session> create_session(login_params)

Create session

Create a session to use the Management API endpoints. Use the value of the `token` property provided in the response as bearer token in other API calls.  A token is valid for 3 months. In accordance with best pratices, use your generated token for all your API requests. Do **not** regenerate a token for each request.  This endpoint has a rate limit of 3 to 6 requests per second per account, depending on your setup.  <div class=\"redoc-section\">   <p class=\"title\">Granular API key</p>   Instead of using a session, you can also use the <a href=\"https://docs.talon.one/docs/product/account/dev-tools/managing-mapi-keys\">Management API key feature</a>   in the Campaign Manager to decide which endpoints can be used with a given key. </div> 

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
login_params = TalonOne::LoginParams.new({email: 'john.doe@example.com', password: 'admin123456'}) # LoginParams | body

begin
  # Create session
  result = api_instance.create_session(login_params)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->create_session: #{e}"
end
```

#### Using the create_session_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<Session>, Integer, Hash)> create_session_with_http_info(login_params)

```ruby
begin
  # Create session
  data, status_code, headers = api_instance.create_session_with_http_info(login_params)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <Session>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->create_session_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **login_params** | [**LoginParams**](LoginParams.md) | body |  |

### Return type

[**Session**](Session.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## create_store

> <Store> create_store(application_id, new_store)

Create store

Create a new store in a specific Application.

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
application_id = 789 # Integer | The ID of the Application. It is displayed in your Talon.One deployment URL.
new_store = TalonOne::NewStore.new({name: 'South US store', description: 'This is the description of the store in south US.', integration_id: 'STORE-001'}) # NewStore | body

begin
  # Create store
  result = api_instance.create_store(application_id, new_store)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->create_store: #{e}"
end
```

#### Using the create_store_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<Store>, Integer, Hash)> create_store_with_http_info(application_id, new_store)

```ruby
begin
  # Create store
  data, status_code, headers = api_instance.create_store_with_http_info(application_id, new_store)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <Store>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->create_store_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **application_id** | **Integer** | The ID of the Application. It is displayed in your Talon.One deployment URL. |  |
| **new_store** | [**NewStore**](NewStore.md) | body |  |

### Return type

[**Store**](Store.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## deactivate_user_by_email

> deactivate_user_by_email(deactivate_user_request)

Disable user by email address

[Disable a specific user](https://docs.talon.one/docs/product/account/account-settings/managing-users#disabling-a-user) by their email address. 

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
deactivate_user_request = TalonOne::DeactivateUserRequest.new({email: 'john.doe@example.com'}) # DeactivateUserRequest | body

begin
  # Disable user by email address
  api_instance.deactivate_user_by_email(deactivate_user_request)
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->deactivate_user_by_email: #{e}"
end
```

#### Using the deactivate_user_by_email_with_http_info variant

This returns an Array which contains the response data (`nil` in this case), status code and headers.

> <Array(nil, Integer, Hash)> deactivate_user_by_email_with_http_info(deactivate_user_request)

```ruby
begin
  # Disable user by email address
  data, status_code, headers = api_instance.deactivate_user_by_email_with_http_info(deactivate_user_request)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => nil
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->deactivate_user_by_email_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **deactivate_user_request** | [**DeactivateUserRequest**](DeactivateUserRequest.md) | body |  |

### Return type

nil (empty response body)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined


## deduct_loyalty_card_points

> deduct_loyalty_card_points(loyalty_program_id, loyalty_card_id, deduct_loyalty_points)

Deduct points from card

Deduct points from the given loyalty card in the specified card-based loyalty program. 

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
loyalty_program_id = 789 # Integer | Identifier of the card-based loyalty program containing the loyalty card. You can get the ID with the [List loyalty programs](https://docs.talon.one/management-api#tag/Loyalty/operation/getLoyaltyPrograms) endpoint. 
loyalty_card_id = 'loyalty_card_id_example' # String | Identifier of the loyalty card. You can get the identifier with the [List loyalty cards](https://docs.talon.one/management-api#tag/Loyalty-cards/operation/getLoyaltyCards) endpoint. 
deduct_loyalty_points = TalonOne::DeductLoyaltyPoints.new({points: 300}) # DeductLoyaltyPoints | body

begin
  # Deduct points from card
  api_instance.deduct_loyalty_card_points(loyalty_program_id, loyalty_card_id, deduct_loyalty_points)
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->deduct_loyalty_card_points: #{e}"
end
```

#### Using the deduct_loyalty_card_points_with_http_info variant

This returns an Array which contains the response data (`nil` in this case), status code and headers.

> <Array(nil, Integer, Hash)> deduct_loyalty_card_points_with_http_info(loyalty_program_id, loyalty_card_id, deduct_loyalty_points)

```ruby
begin
  # Deduct points from card
  data, status_code, headers = api_instance.deduct_loyalty_card_points_with_http_info(loyalty_program_id, loyalty_card_id, deduct_loyalty_points)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => nil
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->deduct_loyalty_card_points_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **loyalty_program_id** | **Integer** | Identifier of the card-based loyalty program containing the loyalty card. You can get the ID with the [List loyalty programs](https://docs.talon.one/management-api#tag/Loyalty/operation/getLoyaltyPrograms) endpoint.  |  |
| **loyalty_card_id** | **String** | Identifier of the loyalty card. You can get the identifier with the [List loyalty cards](https://docs.talon.one/management-api#tag/Loyalty-cards/operation/getLoyaltyCards) endpoint.  |  |
| **deduct_loyalty_points** | [**DeductLoyaltyPoints**](DeductLoyaltyPoints.md) | body |  |

### Return type

nil (empty response body)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## delete_account_collection

> delete_account_collection(collection_id)

Delete account-level collection

Delete a given account-level collection.

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
collection_id = 789 # Integer | The ID of the collection. You can get it with the [List collections in account](#operation/listAccountCollections) endpoint.

begin
  # Delete account-level collection
  api_instance.delete_account_collection(collection_id)
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->delete_account_collection: #{e}"
end
```

#### Using the delete_account_collection_with_http_info variant

This returns an Array which contains the response data (`nil` in this case), status code and headers.

> <Array(nil, Integer, Hash)> delete_account_collection_with_http_info(collection_id)

```ruby
begin
  # Delete account-level collection
  data, status_code, headers = api_instance.delete_account_collection_with_http_info(collection_id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => nil
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->delete_account_collection_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **collection_id** | **Integer** | The ID of the collection. You can get it with the [List collections in account](#operation/listAccountCollections) endpoint. |  |

### Return type

nil (empty response body)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## delete_achievement

> delete_achievement(application_id, campaign_id, achievement_id)

Delete achievement

Delete the specified achievement.

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
application_id = 789 # Integer | The ID of the Application. It is displayed in your Talon.One deployment URL.
campaign_id = 789 # Integer | The ID of the campaign. It is displayed in your Talon.One deployment URL.
achievement_id = 789 # Integer | The ID of the achievement. You can get this ID with the [List achievement](https://docs.talon.one/management-api#tag/Achievements/operation/listAchievements) endpoint.

begin
  # Delete achievement
  api_instance.delete_achievement(application_id, campaign_id, achievement_id)
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->delete_achievement: #{e}"
end
```

#### Using the delete_achievement_with_http_info variant

This returns an Array which contains the response data (`nil` in this case), status code and headers.

> <Array(nil, Integer, Hash)> delete_achievement_with_http_info(application_id, campaign_id, achievement_id)

```ruby
begin
  # Delete achievement
  data, status_code, headers = api_instance.delete_achievement_with_http_info(application_id, campaign_id, achievement_id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => nil
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->delete_achievement_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **application_id** | **Integer** | The ID of the Application. It is displayed in your Talon.One deployment URL. |  |
| **campaign_id** | **Integer** | The ID of the campaign. It is displayed in your Talon.One deployment URL. |  |
| **achievement_id** | **Integer** | The ID of the achievement. You can get this ID with the [List achievement](https://docs.talon.one/management-api#tag/Achievements/operation/listAchievements) endpoint. |  |

### Return type

nil (empty response body)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## delete_campaign

> delete_campaign(application_id, campaign_id)

Delete campaign

Delete the given campaign.

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
application_id = 789 # Integer | The ID of the Application. It is displayed in your Talon.One deployment URL.
campaign_id = 789 # Integer | The ID of the campaign. It is displayed in your Talon.One deployment URL.

begin
  # Delete campaign
  api_instance.delete_campaign(application_id, campaign_id)
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->delete_campaign: #{e}"
end
```

#### Using the delete_campaign_with_http_info variant

This returns an Array which contains the response data (`nil` in this case), status code and headers.

> <Array(nil, Integer, Hash)> delete_campaign_with_http_info(application_id, campaign_id)

```ruby
begin
  # Delete campaign
  data, status_code, headers = api_instance.delete_campaign_with_http_info(application_id, campaign_id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => nil
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->delete_campaign_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **application_id** | **Integer** | The ID of the Application. It is displayed in your Talon.One deployment URL. |  |
| **campaign_id** | **Integer** | The ID of the campaign. It is displayed in your Talon.One deployment URL. |  |

### Return type

nil (empty response body)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined


## delete_campaign_store_budgets

> delete_campaign_store_budgets(application_id, campaign_id, opts)

Delete campaign store budgets

Delete the store budgets for a given campaign.

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
application_id = 789 # Integer | The ID of the Application. It is displayed in your Talon.One deployment URL.
campaign_id = 789 # Integer | The ID of the campaign. It is displayed in your Talon.One deployment URL.
opts = {
  action: 'setDiscount', # String | The action that this budget is limiting.
  period: 'overall' # String | The period to which the limit applies.  **Note**: For budgets with no period, set this to `overall`. 
}

begin
  # Delete campaign store budgets
  api_instance.delete_campaign_store_budgets(application_id, campaign_id, opts)
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->delete_campaign_store_budgets: #{e}"
end
```

#### Using the delete_campaign_store_budgets_with_http_info variant

This returns an Array which contains the response data (`nil` in this case), status code and headers.

> <Array(nil, Integer, Hash)> delete_campaign_store_budgets_with_http_info(application_id, campaign_id, opts)

```ruby
begin
  # Delete campaign store budgets
  data, status_code, headers = api_instance.delete_campaign_store_budgets_with_http_info(application_id, campaign_id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => nil
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->delete_campaign_store_budgets_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **application_id** | **Integer** | The ID of the Application. It is displayed in your Talon.One deployment URL. |  |
| **campaign_id** | **Integer** | The ID of the campaign. It is displayed in your Talon.One deployment URL. |  |
| **action** | **String** | The action that this budget is limiting. | [optional] |
| **period** | **String** | The period to which the limit applies.  **Note**: For budgets with no period, set this to &#x60;overall&#x60;.  | [optional] |

### Return type

nil (empty response body)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## delete_collection

> delete_collection(application_id, campaign_id, collection_id)

Delete campaign-level collection

Delete a given campaign-level collection.

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
application_id = 789 # Integer | The ID of the Application. It is displayed in your Talon.One deployment URL.
campaign_id = 789 # Integer | The ID of the campaign. It is displayed in your Talon.One deployment URL.
collection_id = 789 # Integer | The ID of the collection. You can get it with the [List collections in Application](#operation/listCollectionsInApplication) endpoint.

begin
  # Delete campaign-level collection
  api_instance.delete_collection(application_id, campaign_id, collection_id)
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->delete_collection: #{e}"
end
```

#### Using the delete_collection_with_http_info variant

This returns an Array which contains the response data (`nil` in this case), status code and headers.

> <Array(nil, Integer, Hash)> delete_collection_with_http_info(application_id, campaign_id, collection_id)

```ruby
begin
  # Delete campaign-level collection
  data, status_code, headers = api_instance.delete_collection_with_http_info(application_id, campaign_id, collection_id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => nil
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->delete_collection_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **application_id** | **Integer** | The ID of the Application. It is displayed in your Talon.One deployment URL. |  |
| **campaign_id** | **Integer** | The ID of the campaign. It is displayed in your Talon.One deployment URL. |  |
| **collection_id** | **Integer** | The ID of the collection. You can get it with the [List collections in Application](#operation/listCollectionsInApplication) endpoint. |  |

### Return type

nil (empty response body)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## delete_coupon

> delete_coupon(application_id, campaign_id, coupon_id)

Delete coupon

Delete the specified coupon.

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
application_id = 789 # Integer | The ID of the Application. It is displayed in your Talon.One deployment URL.
campaign_id = 789 # Integer | The ID of the campaign. It is displayed in your Talon.One deployment URL.
coupon_id = 'coupon_id_example' # String | The internal ID of the coupon code. You can find this value in the `id` property from the [List coupons](https://docs.talon.one/management-api#tag/Coupons/operation/getCouponsWithoutTotalCount) endpoint response. 

begin
  # Delete coupon
  api_instance.delete_coupon(application_id, campaign_id, coupon_id)
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->delete_coupon: #{e}"
end
```

#### Using the delete_coupon_with_http_info variant

This returns an Array which contains the response data (`nil` in this case), status code and headers.

> <Array(nil, Integer, Hash)> delete_coupon_with_http_info(application_id, campaign_id, coupon_id)

```ruby
begin
  # Delete coupon
  data, status_code, headers = api_instance.delete_coupon_with_http_info(application_id, campaign_id, coupon_id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => nil
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->delete_coupon_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **application_id** | **Integer** | The ID of the Application. It is displayed in your Talon.One deployment URL. |  |
| **campaign_id** | **Integer** | The ID of the campaign. It is displayed in your Talon.One deployment URL. |  |
| **coupon_id** | **String** | The internal ID of the coupon code. You can find this value in the &#x60;id&#x60; property from the [List coupons](https://docs.talon.one/management-api#tag/Coupons/operation/getCouponsWithoutTotalCount) endpoint response.  |  |

### Return type

nil (empty response body)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined


## delete_coupons

> delete_coupons(application_id, campaign_id, opts)

Delete coupons

Deletes all the coupons matching the specified criteria.

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
application_id = 789 # Integer | The ID of the Application. It is displayed in your Talon.One deployment URL.
campaign_id = 789 # Integer | The ID of the campaign. It is displayed in your Talon.One deployment URL.
opts = {
  value: 'value_example', # String | Filter results performing case-insensitive matching against the coupon code. Both the code and the query are folded to remove all non-alpha-numeric characters.
  created_before: Time.parse('2013-10-20T19:20:30+01:00'), # Time | Filter results comparing the parameter value, expected to be an RFC3339 timestamp string, to the coupon creation timestamp. You can use any time zone setting. Talon.One will convert to UTC internally.
  created_after: Time.parse('2013-10-20T19:20:30+01:00'), # Time | Filter results comparing the parameter value, expected to be an RFC3339 timestamp string, to the coupon creation timestamp. You can use any time zone setting. Talon.One will convert to UTC internally.
  starts_after: Time.parse('2013-10-20T19:20:30+01:00'), # Time | Filter results comparing the parameter value, expected to be an RFC3339 timestamp string, to the coupon start date timestamp. You can use any time zone setting. Talon.One will convert to UTC internally.
  starts_before: Time.parse('2013-10-20T19:20:30+01:00'), # Time | Filter results comparing the parameter value, expected to be an RFC3339 timestamp string, to the coupon start date timestamp. You can use any time zone setting. Talon.One will convert to UTC internally.
  expires_after: Time.parse('2013-10-20T19:20:30+01:00'), # Time | Filter results comparing the parameter value, expected to be an RFC3339 timestamp string, to the coupon expiration date timestamp. You can use any time zone setting. Talon.One will convert to UTC internally.
  expires_before: Time.parse('2013-10-20T19:20:30+01:00'), # Time | Filter results comparing the parameter value, expected to be an RFC3339 timestamp string, to the coupon expiration date timestamp. You can use any time zone setting. Talon.One will convert to UTC internally.
  valid: 'expired', # String | - `expired`: Matches coupons in which the expiration date is set and in the past. - `validNow`: Matches coupons in which start date is null or in the past and expiration date is null or in the future. - `validFuture`: Matches coupons in which start date is set and in the future. 
  batch_id: 'batch_id_example', # String | Filter results by batches of coupons
  usable: 'true', # String | - `true`: only coupons where `usageCounter < usageLimit` will be returned. - `false`: only coupons where `usageCounter >= usageLimit` will be returned. 
  referral_id: 789, # Integer | Filter the results by matching them with the ID of a referral. This filter shows the coupons created by redeeming a referral code.
  recipient_integration_id: 'recipient_integration_id_example', # String | Filter results by match with a profile ID specified in the coupon's `RecipientIntegrationId` field. 
  exact_match: true # Boolean | Filter results to an exact case-insensitive matching against the coupon code
}

begin
  # Delete coupons
  api_instance.delete_coupons(application_id, campaign_id, opts)
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->delete_coupons: #{e}"
end
```

#### Using the delete_coupons_with_http_info variant

This returns an Array which contains the response data (`nil` in this case), status code and headers.

> <Array(nil, Integer, Hash)> delete_coupons_with_http_info(application_id, campaign_id, opts)

```ruby
begin
  # Delete coupons
  data, status_code, headers = api_instance.delete_coupons_with_http_info(application_id, campaign_id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => nil
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->delete_coupons_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **application_id** | **Integer** | The ID of the Application. It is displayed in your Talon.One deployment URL. |  |
| **campaign_id** | **Integer** | The ID of the campaign. It is displayed in your Talon.One deployment URL. |  |
| **value** | **String** | Filter results performing case-insensitive matching against the coupon code. Both the code and the query are folded to remove all non-alpha-numeric characters. | [optional] |
| **created_before** | **Time** | Filter results comparing the parameter value, expected to be an RFC3339 timestamp string, to the coupon creation timestamp. You can use any time zone setting. Talon.One will convert to UTC internally. | [optional] |
| **created_after** | **Time** | Filter results comparing the parameter value, expected to be an RFC3339 timestamp string, to the coupon creation timestamp. You can use any time zone setting. Talon.One will convert to UTC internally. | [optional] |
| **starts_after** | **Time** | Filter results comparing the parameter value, expected to be an RFC3339 timestamp string, to the coupon start date timestamp. You can use any time zone setting. Talon.One will convert to UTC internally. | [optional] |
| **starts_before** | **Time** | Filter results comparing the parameter value, expected to be an RFC3339 timestamp string, to the coupon start date timestamp. You can use any time zone setting. Talon.One will convert to UTC internally. | [optional] |
| **expires_after** | **Time** | Filter results comparing the parameter value, expected to be an RFC3339 timestamp string, to the coupon expiration date timestamp. You can use any time zone setting. Talon.One will convert to UTC internally. | [optional] |
| **expires_before** | **Time** | Filter results comparing the parameter value, expected to be an RFC3339 timestamp string, to the coupon expiration date timestamp. You can use any time zone setting. Talon.One will convert to UTC internally. | [optional] |
| **valid** | **String** | - &#x60;expired&#x60;: Matches coupons in which the expiration date is set and in the past. - &#x60;validNow&#x60;: Matches coupons in which start date is null or in the past and expiration date is null or in the future. - &#x60;validFuture&#x60;: Matches coupons in which start date is set and in the future.  | [optional] |
| **batch_id** | **String** | Filter results by batches of coupons | [optional] |
| **usable** | **String** | - &#x60;true&#x60;: only coupons where &#x60;usageCounter &lt; usageLimit&#x60; will be returned. - &#x60;false&#x60;: only coupons where &#x60;usageCounter &gt;&#x3D; usageLimit&#x60; will be returned.  | [optional] |
| **referral_id** | **Integer** | Filter the results by matching them with the ID of a referral. This filter shows the coupons created by redeeming a referral code. | [optional] |
| **recipient_integration_id** | **String** | Filter results by match with a profile ID specified in the coupon&#39;s &#x60;RecipientIntegrationId&#x60; field.  | [optional] |
| **exact_match** | **Boolean** | Filter results to an exact case-insensitive matching against the coupon code | [optional][default to false] |

### Return type

nil (empty response body)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined


## delete_loyalty_card

> delete_loyalty_card(loyalty_program_id, loyalty_card_id)

Delete loyalty card

Delete the given loyalty card.

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
loyalty_program_id = 789 # Integer | Identifier of the card-based loyalty program containing the loyalty card. You can get the ID with the [List loyalty programs](https://docs.talon.one/management-api#tag/Loyalty/operation/getLoyaltyPrograms) endpoint. 
loyalty_card_id = 'loyalty_card_id_example' # String | Identifier of the loyalty card. You can get the identifier with the [List loyalty cards](https://docs.talon.one/management-api#tag/Loyalty-cards/operation/getLoyaltyCards) endpoint. 

begin
  # Delete loyalty card
  api_instance.delete_loyalty_card(loyalty_program_id, loyalty_card_id)
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->delete_loyalty_card: #{e}"
end
```

#### Using the delete_loyalty_card_with_http_info variant

This returns an Array which contains the response data (`nil` in this case), status code and headers.

> <Array(nil, Integer, Hash)> delete_loyalty_card_with_http_info(loyalty_program_id, loyalty_card_id)

```ruby
begin
  # Delete loyalty card
  data, status_code, headers = api_instance.delete_loyalty_card_with_http_info(loyalty_program_id, loyalty_card_id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => nil
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->delete_loyalty_card_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **loyalty_program_id** | **Integer** | Identifier of the card-based loyalty program containing the loyalty card. You can get the ID with the [List loyalty programs](https://docs.talon.one/management-api#tag/Loyalty/operation/getLoyaltyPrograms) endpoint.  |  |
| **loyalty_card_id** | **String** | Identifier of the loyalty card. You can get the identifier with the [List loyalty cards](https://docs.talon.one/management-api#tag/Loyalty-cards/operation/getLoyaltyCards) endpoint.  |  |

### Return type

nil (empty response body)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## delete_referral

> delete_referral(application_id, campaign_id, referral_id)

Delete referral

Delete the specified referral.

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
application_id = 789 # Integer | The ID of the Application. It is displayed in your Talon.One deployment URL.
campaign_id = 789 # Integer | The ID of the campaign. It is displayed in your Talon.One deployment URL.
referral_id = 'referral_id_example' # String | The ID of the referral code.

begin
  # Delete referral
  api_instance.delete_referral(application_id, campaign_id, referral_id)
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->delete_referral: #{e}"
end
```

#### Using the delete_referral_with_http_info variant

This returns an Array which contains the response data (`nil` in this case), status code and headers.

> <Array(nil, Integer, Hash)> delete_referral_with_http_info(application_id, campaign_id, referral_id)

```ruby
begin
  # Delete referral
  data, status_code, headers = api_instance.delete_referral_with_http_info(application_id, campaign_id, referral_id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => nil
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->delete_referral_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **application_id** | **Integer** | The ID of the Application. It is displayed in your Talon.One deployment URL. |  |
| **campaign_id** | **Integer** | The ID of the campaign. It is displayed in your Talon.One deployment URL. |  |
| **referral_id** | **String** | The ID of the referral code. |  |

### Return type

nil (empty response body)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined


## delete_store

> delete_store(application_id, store_id)

Delete store

Delete the specified store.

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
application_id = 789 # Integer | The ID of the Application. It is displayed in your Talon.One deployment URL.
store_id = 'store_id_example' # String | The ID of the store. You can get this ID with the [List stores](#tag/Stores/operation/listStores) endpoint. 

begin
  # Delete store
  api_instance.delete_store(application_id, store_id)
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->delete_store: #{e}"
end
```

#### Using the delete_store_with_http_info variant

This returns an Array which contains the response data (`nil` in this case), status code and headers.

> <Array(nil, Integer, Hash)> delete_store_with_http_info(application_id, store_id)

```ruby
begin
  # Delete store
  data, status_code, headers = api_instance.delete_store_with_http_info(application_id, store_id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => nil
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->delete_store_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **application_id** | **Integer** | The ID of the Application. It is displayed in your Talon.One deployment URL. |  |
| **store_id** | **String** | The ID of the store. You can get this ID with the [List stores](#tag/Stores/operation/listStores) endpoint.  |  |

### Return type

nil (empty response body)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## delete_user

> delete_user(user_id)

Delete user

Delete a specific user.

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
user_id = 789 # Integer | The ID of the user.

begin
  # Delete user
  api_instance.delete_user(user_id)
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->delete_user: #{e}"
end
```

#### Using the delete_user_with_http_info variant

This returns an Array which contains the response data (`nil` in this case), status code and headers.

> <Array(nil, Integer, Hash)> delete_user_with_http_info(user_id)

```ruby
begin
  # Delete user
  data, status_code, headers = api_instance.delete_user_with_http_info(user_id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => nil
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->delete_user_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **user_id** | **Integer** | The ID of the user. |  |

### Return type

nil (empty response body)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined


## delete_user_by_email

> delete_user_by_email(delete_user_request)

Delete user by email address

[Delete a specific user](https://docs.talon.one/docs/product/account/account-settings/managing-users#deleting-a-user) by their email address. 

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
delete_user_request = TalonOne::DeleteUserRequest.new({email: 'john.doe@example.com'}) # DeleteUserRequest | body

begin
  # Delete user by email address
  api_instance.delete_user_by_email(delete_user_request)
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->delete_user_by_email: #{e}"
end
```

#### Using the delete_user_by_email_with_http_info variant

This returns an Array which contains the response data (`nil` in this case), status code and headers.

> <Array(nil, Integer, Hash)> delete_user_by_email_with_http_info(delete_user_request)

```ruby
begin
  # Delete user by email address
  data, status_code, headers = api_instance.delete_user_by_email_with_http_info(delete_user_request)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => nil
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->delete_user_by_email_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **delete_user_request** | [**DeleteUserRequest**](DeleteUserRequest.md) | body |  |

### Return type

nil (empty response body)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined


## destroy_session

> destroy_session

Destroy session

Destroys the session.

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

begin
  # Destroy session
  api_instance.destroy_session
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->destroy_session: #{e}"
end
```

#### Using the destroy_session_with_http_info variant

This returns an Array which contains the response data (`nil` in this case), status code and headers.

> <Array(nil, Integer, Hash)> destroy_session_with_http_info

```ruby
begin
  # Destroy session
  data, status_code, headers = api_instance.destroy_session_with_http_info
  p status_code # => 2xx
  p headers # => { ... }
  p data # => nil
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->destroy_session_with_http_info: #{e}"
end
```

### Parameters

This endpoint does not need any parameter.

### Return type

nil (empty response body)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined


## disconnect_campaign_stores

> disconnect_campaign_stores(application_id, campaign_id)

Disconnect stores

Disconnect the stores linked to a specific campaign.

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
application_id = 789 # Integer | The ID of the Application. It is displayed in your Talon.One deployment URL.
campaign_id = 789 # Integer | The ID of the campaign. It is displayed in your Talon.One deployment URL.

begin
  # Disconnect stores
  api_instance.disconnect_campaign_stores(application_id, campaign_id)
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->disconnect_campaign_stores: #{e}"
end
```

#### Using the disconnect_campaign_stores_with_http_info variant

This returns an Array which contains the response data (`nil` in this case), status code and headers.

> <Array(nil, Integer, Hash)> disconnect_campaign_stores_with_http_info(application_id, campaign_id)

```ruby
begin
  # Disconnect stores
  data, status_code, headers = api_instance.disconnect_campaign_stores_with_http_info(application_id, campaign_id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => nil
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->disconnect_campaign_stores_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **application_id** | **Integer** | The ID of the Application. It is displayed in your Talon.One deployment URL. |  |
| **campaign_id** | **Integer** | The ID of the campaign. It is displayed in your Talon.One deployment URL. |  |

### Return type

nil (empty response body)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## export_account_collection_items

> String export_account_collection_items(collection_id)

Export account-level collection's items

Download a CSV file containing items from a given account-level collection.  **Tip:** If the exported CSV file is too large to view, you can [split it into multiple files](https://www.makeuseof.com/tag/how-to-split-a-huge-csv-excel-workbook-into-seperate-files/). 

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
collection_id = 789 # Integer | The ID of the collection. You can get it with the [List collections in account](#operation/listAccountCollections) endpoint.

begin
  # Export account-level collection's items
  result = api_instance.export_account_collection_items(collection_id)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->export_account_collection_items: #{e}"
end
```

#### Using the export_account_collection_items_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(String, Integer, Hash)> export_account_collection_items_with_http_info(collection_id)

```ruby
begin
  # Export account-level collection's items
  data, status_code, headers = api_instance.export_account_collection_items_with_http_info(collection_id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => String
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->export_account_collection_items_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **collection_id** | **Integer** | The ID of the collection. You can get it with the [List collections in account](#operation/listAccountCollections) endpoint. |  |

### Return type

**String**

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/csv


## export_achievements

> String export_achievements(application_id, campaign_id, achievement_id)

Export achievement customer data

Download a CSV file containing a list of all the customers who have participated in and are currently participating in the given achievement.  The CSV file contains the following columns: - `profileIntegrationID`: The integration ID of the customer profile participating in the achievement. - `title`: The display name of the achievement in the Campaign Manager. - `target`: The required number of actions or the transactional milestone to complete the achievement. - `progress`: The current progress of the customer in the achievement. - `status`: The status of the achievement. Can be one of: ['inprogress', 'completed', 'expired']. - `startDate`: The date on which the customer profile started the achievement in RFC3339. - `endDate`: The date on which the achievement ends and resets for the customer profile in RFC3339. - `completionDate`: The date on which the customer profile completed the achievement in RFC3339. 

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
application_id = 789 # Integer | The ID of the Application. It is displayed in your Talon.One deployment URL.
campaign_id = 789 # Integer | The ID of the campaign. It is displayed in your Talon.One deployment URL.
achievement_id = 789 # Integer | The ID of the achievement. You can get this ID with the [List achievement](https://docs.talon.one/management-api#tag/Achievements/operation/listAchievements) endpoint.

begin
  # Export achievement customer data
  result = api_instance.export_achievements(application_id, campaign_id, achievement_id)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->export_achievements: #{e}"
end
```

#### Using the export_achievements_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(String, Integer, Hash)> export_achievements_with_http_info(application_id, campaign_id, achievement_id)

```ruby
begin
  # Export achievement customer data
  data, status_code, headers = api_instance.export_achievements_with_http_info(application_id, campaign_id, achievement_id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => String
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->export_achievements_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **application_id** | **Integer** | The ID of the Application. It is displayed in your Talon.One deployment URL. |  |
| **campaign_id** | **Integer** | The ID of the campaign. It is displayed in your Talon.One deployment URL. |  |
| **achievement_id** | **Integer** | The ID of the achievement. You can get this ID with the [List achievement](https://docs.talon.one/management-api#tag/Achievements/operation/listAchievements) endpoint. |  |

### Return type

**String**

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/csv


## export_audiences_memberships

> String export_audiences_memberships(audience_id)

Export audience members

Download a CSV file containing the integration IDs of the members of an audience.  **Tip:** If the exported CSV file is too large to view, you can [split it into multiple files](https://www.makeuseof.com/tag/how-to-split-a-huge-csv-excel-workbook-into-seperate-files/).  The file contains the following column: - `profileintegrationid`: The integration ID of the customer profile. 

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
audience_id = 789 # Integer | The ID of the audience.

begin
  # Export audience members
  result = api_instance.export_audiences_memberships(audience_id)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->export_audiences_memberships: #{e}"
end
```

#### Using the export_audiences_memberships_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(String, Integer, Hash)> export_audiences_memberships_with_http_info(audience_id)

```ruby
begin
  # Export audience members
  data, status_code, headers = api_instance.export_audiences_memberships_with_http_info(audience_id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => String
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->export_audiences_memberships_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **audience_id** | **Integer** | The ID of the audience. |  |

### Return type

**String**

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/csv


## export_campaign_store_budgets

> String export_campaign_store_budgets(application_id, campaign_id, opts)

Export campaign store budgets

Download a CSV file containing the store budgets for a given campaign.  **Tip:** If the exported CSV file is too large to view, you can [split it into multiple files](https://www.makeuseof.com/tag/how-to-split-a-huge-csv-excel-workbook-into-seperate-files/).  The CSV file contains the following columns:  - `store_integration_id`: The identifier of the store. - `limit`: The budget limit for the store. 

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
application_id = 789 # Integer | The ID of the Application. It is displayed in your Talon.One deployment URL.
campaign_id = 789 # Integer | The ID of the campaign. It is displayed in your Talon.One deployment URL.
opts = {
  action: 'setDiscount', # String | The action that this budget is limiting.
  period: 'overall' # String | The period to which the limit applies.  **Note**: For budgets with no period, set this to `overall`. 
}

begin
  # Export campaign store budgets
  result = api_instance.export_campaign_store_budgets(application_id, campaign_id, opts)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->export_campaign_store_budgets: #{e}"
end
```

#### Using the export_campaign_store_budgets_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(String, Integer, Hash)> export_campaign_store_budgets_with_http_info(application_id, campaign_id, opts)

```ruby
begin
  # Export campaign store budgets
  data, status_code, headers = api_instance.export_campaign_store_budgets_with_http_info(application_id, campaign_id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => String
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->export_campaign_store_budgets_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **application_id** | **Integer** | The ID of the Application. It is displayed in your Talon.One deployment URL. |  |
| **campaign_id** | **Integer** | The ID of the campaign. It is displayed in your Talon.One deployment URL. |  |
| **action** | **String** | The action that this budget is limiting. | [optional] |
| **period** | **String** | The period to which the limit applies.  **Note**: For budgets with no period, set this to &#x60;overall&#x60;.  | [optional] |

### Return type

**String**

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/csv


## export_campaign_stores

> String export_campaign_stores(application_id, campaign_id)

Export stores

Download a CSV file containing the stores linked to a specific campaign.  **Tip:** If the exported CSV file is too large to view, you can [split it into multiple files](https://www.makeuseof.com/tag/how-to-split-a-huge-csv-excel-workbook-into-seperate-files/).  The CSV file contains the following column:  - `store_integration_id`: The identifier of the store. 

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
application_id = 789 # Integer | The ID of the Application. It is displayed in your Talon.One deployment URL.
campaign_id = 789 # Integer | The ID of the campaign. It is displayed in your Talon.One deployment URL.

begin
  # Export stores
  result = api_instance.export_campaign_stores(application_id, campaign_id)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->export_campaign_stores: #{e}"
end
```

#### Using the export_campaign_stores_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(String, Integer, Hash)> export_campaign_stores_with_http_info(application_id, campaign_id)

```ruby
begin
  # Export stores
  data, status_code, headers = api_instance.export_campaign_stores_with_http_info(application_id, campaign_id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => String
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->export_campaign_stores_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **application_id** | **Integer** | The ID of the Application. It is displayed in your Talon.One deployment URL. |  |
| **campaign_id** | **Integer** | The ID of the campaign. It is displayed in your Talon.One deployment URL. |  |

### Return type

**String**

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/csv


## export_collection_items

> String export_collection_items(application_id, campaign_id, collection_id)

Export campaign-level collection's items

Download a CSV file containing items from a given campaign-level collection.  **Tip:** If the exported CSV file is too large to view, you can [split it into multiple files](https://www.makeuseof.com/tag/how-to-split-a-huge-csv-excel-workbook-into-seperate-files/). 

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
application_id = 789 # Integer | The ID of the Application. It is displayed in your Talon.One deployment URL.
campaign_id = 789 # Integer | The ID of the campaign. It is displayed in your Talon.One deployment URL.
collection_id = 789 # Integer | The ID of the collection. You can get it with the [List collections in Application](#operation/listCollectionsInApplication) endpoint.

begin
  # Export campaign-level collection's items
  result = api_instance.export_collection_items(application_id, campaign_id, collection_id)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->export_collection_items: #{e}"
end
```

#### Using the export_collection_items_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(String, Integer, Hash)> export_collection_items_with_http_info(application_id, campaign_id, collection_id)

```ruby
begin
  # Export campaign-level collection's items
  data, status_code, headers = api_instance.export_collection_items_with_http_info(application_id, campaign_id, collection_id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => String
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->export_collection_items_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **application_id** | **Integer** | The ID of the Application. It is displayed in your Talon.One deployment URL. |  |
| **campaign_id** | **Integer** | The ID of the campaign. It is displayed in your Talon.One deployment URL. |  |
| **collection_id** | **Integer** | The ID of the collection. You can get it with the [List collections in Application](#operation/listCollectionsInApplication) endpoint. |  |

### Return type

**String**

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/csv


## export_coupons

> String export_coupons(application_id, opts)

Export coupons

Download a CSV file containing the coupons that match the given properties.  **Tip:** If the exported CSV file is too large to view, you can [split it into multiple files](https://www.makeuseof.com/tag/how-to-split-a-huge-csv-excel-workbook-into-seperate-files/).  The CSV file can contain the following columns:  - `accountid`: The ID of your deployment. - `applicationid`: The ID of the Application this coupon is related to. - `attributes`: A json object describing _custom_ referral attribute names and their values. - `batchid`: The ID of the batch this coupon is part of. - `campaignid`: The ID of the campaign this coupon is related to. - `counter`: The number of times this coupon has been redeemed. - `created`: The creation date in RFC3339 of the coupon code. - `deleted`: Whether the coupon code is deleted. - `deleted_changelogid`: The ID of the delete event in the logs. - `discount_counter`: The amount of discount given by this coupon. - `discount_limitval`: The maximum discount amount that can be given be this coupon. - `expirydate`: The end date in RFC3339 of the code redemption period. - `id`: The internal ID of the coupon code. - `importid`: The ID of the import job that created this coupon. - `is_reservation_mandatory`: Whether this coupon requires a reservation to be redeemed. - `limits`: The limits set on this coupon. - `limitval`: The maximum number of redemptions of this code. - `recipientintegrationid`: The integration ID of the recipient of the coupon.   Only the customer with this integration ID can redeem this code. Available only for personal codes. - `referralid`: The ID of the referral code that triggered the creation of this coupon (create coupon effect). - `reservation`: Whether the coupon can be reserved for multiple customers. - `reservation_counter`: How many times this coupon has been reserved. - `reservation_limitval`: The maximum of number of reservations this coupon can have. - `startdate`: The start date in RFC3339 of the code redemption period. - `value`: The coupon code. 

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
application_id = 789 # Integer | The ID of the Application. It is displayed in your Talon.One deployment URL.
opts = {
  campaign_id: 8.14, # Float | Filter results by campaign ID.
  sort: 'sort_example', # String | The field by which results should be sorted. By default, results are sorted in ascending order. To sort them in descending order, prefix the field name with `-`.  **Note:** You may not be able to use all fields for sorting. This is due to performance limitations. 
  value: 'value_example', # String | Filter results performing case-insensitive matching against the coupon code. Both the code and the query are folded to remove all non-alpha-numeric characters.
  created_before: Time.parse('2013-10-20T19:20:30+01:00'), # Time | Filter results comparing the parameter value, expected to be an RFC3339 timestamp string, to the coupon creation timestamp. You can use any time zone setting. Talon.One will convert to UTC internally.
  created_after: Time.parse('2013-10-20T19:20:30+01:00'), # Time | Filter results comparing the parameter value, expected to be an RFC3339 timestamp string, to the coupon creation timestamp. You can use any time zone setting. Talon.One will convert to UTC internally.
  valid: 'expired', # String | Either \"expired\", \"validNow\", or \"validFuture\". The first option matches coupons in which the expiration date is set and in the past. The second matches coupons in which start date is null or in the past and expiration date is null or in the future, the third matches coupons in which start date is set and in the future. 
  usable: 'true', # String | Either \"true\" or \"false\". If \"true\", only coupons where `usageCounter < usageLimit` will be returned, \"false\" will return only coupons where `usageCounter >= usageLimit`. 
  referral_id: 789, # Integer | Filter the results by matching them with the ID of a referral. This filter shows the coupons created by redeeming a referral code.
  recipient_integration_id: 'recipient_integration_id_example', # String | Filter results by match with a profile id specified in the coupon's RecipientIntegrationId field.
  batch_id: 'batch_id_example', # String | Filter results by batches of coupons
  exact_match: true, # Boolean | Filter results to an exact case-insensitive matching against the coupon code.
  date_format: 'excel', # String | Determines the format of dates in the export document.
  campaign_state: 'enabled', # String | Filter results by the state of the campaign.  - `enabled`: Campaigns that are scheduled, running (activated), or expired. - `running`: Campaigns that are running (activated). - `disabled`: Campaigns that are disabled. - `expired`: Campaigns that are expired. - `archived`: Campaigns that are archived. 
  values_only: true # Boolean | Filter results to only return the coupon codes (`value` column) without the associated coupon data.
}

begin
  # Export coupons
  result = api_instance.export_coupons(application_id, opts)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->export_coupons: #{e}"
end
```

#### Using the export_coupons_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(String, Integer, Hash)> export_coupons_with_http_info(application_id, opts)

```ruby
begin
  # Export coupons
  data, status_code, headers = api_instance.export_coupons_with_http_info(application_id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => String
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->export_coupons_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **application_id** | **Integer** | The ID of the Application. It is displayed in your Talon.One deployment URL. |  |
| **campaign_id** | **Float** | Filter results by campaign ID. | [optional] |
| **sort** | **String** | The field by which results should be sorted. By default, results are sorted in ascending order. To sort them in descending order, prefix the field name with &#x60;-&#x60;.  **Note:** You may not be able to use all fields for sorting. This is due to performance limitations.  | [optional] |
| **value** | **String** | Filter results performing case-insensitive matching against the coupon code. Both the code and the query are folded to remove all non-alpha-numeric characters. | [optional] |
| **created_before** | **Time** | Filter results comparing the parameter value, expected to be an RFC3339 timestamp string, to the coupon creation timestamp. You can use any time zone setting. Talon.One will convert to UTC internally. | [optional] |
| **created_after** | **Time** | Filter results comparing the parameter value, expected to be an RFC3339 timestamp string, to the coupon creation timestamp. You can use any time zone setting. Talon.One will convert to UTC internally. | [optional] |
| **valid** | **String** | Either \&quot;expired\&quot;, \&quot;validNow\&quot;, or \&quot;validFuture\&quot;. The first option matches coupons in which the expiration date is set and in the past. The second matches coupons in which start date is null or in the past and expiration date is null or in the future, the third matches coupons in which start date is set and in the future.  | [optional] |
| **usable** | **String** | Either \&quot;true\&quot; or \&quot;false\&quot;. If \&quot;true\&quot;, only coupons where &#x60;usageCounter &lt; usageLimit&#x60; will be returned, \&quot;false\&quot; will return only coupons where &#x60;usageCounter &gt;&#x3D; usageLimit&#x60;.  | [optional] |
| **referral_id** | **Integer** | Filter the results by matching them with the ID of a referral. This filter shows the coupons created by redeeming a referral code. | [optional] |
| **recipient_integration_id** | **String** | Filter results by match with a profile id specified in the coupon&#39;s RecipientIntegrationId field. | [optional] |
| **batch_id** | **String** | Filter results by batches of coupons | [optional] |
| **exact_match** | **Boolean** | Filter results to an exact case-insensitive matching against the coupon code. | [optional][default to false] |
| **date_format** | **String** | Determines the format of dates in the export document. | [optional] |
| **campaign_state** | **String** | Filter results by the state of the campaign.  - &#x60;enabled&#x60;: Campaigns that are scheduled, running (activated), or expired. - &#x60;running&#x60;: Campaigns that are running (activated). - &#x60;disabled&#x60;: Campaigns that are disabled. - &#x60;expired&#x60;: Campaigns that are expired. - &#x60;archived&#x60;: Campaigns that are archived.  | [optional] |
| **values_only** | **Boolean** | Filter results to only return the coupon codes (&#x60;value&#x60; column) without the associated coupon data. | [optional][default to false] |

### Return type

**String**

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/csv


## export_customer_sessions

> String export_customer_sessions(application_id, opts)

Export customer sessions

Download a CSV file containing the customer sessions that match the request.  **Important:** Archived sessions cannot be exported. See the [retention policy](https://docs.talon.one/docs/dev/server-infrastructure-and-data-retention).  **Tip:** If the exported CSV file is too large to view, you can [split it into multiple files](https://www.makeuseof.com/tag/how-to-split-a-huge-csv-excel-workbook-into-seperate-files/).  - `id`: The internal ID of the session. - `firstsession`: Whether this is a first session. - `integrationid`: The integration ID of the session. - `applicationid`: The ID of the Application. - `profileid`: The internal ID of the customer profile. - `profileintegrationid`: The integration ID of the customer profile. - `created`: The timestamp when the session was created. - `state`: The [state](https://docs.talon.one/docs/dev/concepts/entities/customer-sessions#customer-session-states) of the session. - `cartitems`: The cart items in the session. - `discounts`: The discounts in the session. - `total`: The total value of cart items and additional costs in the session, before any discounts are applied. - `attributes`: The attributes set in the session. - `closedat`: Timestamp when the session was closed. - `cancelledat`: Timestamp when the session was cancelled. - `referral`: The referral code in the session. - `identifiers`: The identifiers in the session. - `additional_costs`: The [additional costs](https://docs.talon.one/docs/product/account/dev-tools/managing-additional-costs) in the session. - `updated`: Timestamp of the last session update. - `store_integration_id`: The integration ID of the store. - `coupons`: Coupon codes in the session. 

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
application_id = 789 # Integer | The ID of the Application. It is displayed in your Talon.One deployment URL.
opts = {
  created_before: Time.parse('2013-10-20T19:20:30+01:00'), # Time | Filter results comparing the parameter value, expected to be an RFC3339 timestamp string.
  created_after: Time.parse('2013-10-20T19:20:30+01:00'), # Time | Filter results comparing the parameter value, expected to be an RFC3339 timestamp string.
  profile_integration_id: 'profile_integration_id_example', # String | Only return sessions for the customer that matches this customer integration ID.
  date_format: 'excel', # String | Determines the format of dates in the export document.
  customer_session_state: 'open' # String | Filter results by state.
}

begin
  # Export customer sessions
  result = api_instance.export_customer_sessions(application_id, opts)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->export_customer_sessions: #{e}"
end
```

#### Using the export_customer_sessions_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(String, Integer, Hash)> export_customer_sessions_with_http_info(application_id, opts)

```ruby
begin
  # Export customer sessions
  data, status_code, headers = api_instance.export_customer_sessions_with_http_info(application_id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => String
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->export_customer_sessions_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **application_id** | **Integer** | The ID of the Application. It is displayed in your Talon.One deployment URL. |  |
| **created_before** | **Time** | Filter results comparing the parameter value, expected to be an RFC3339 timestamp string. | [optional] |
| **created_after** | **Time** | Filter results comparing the parameter value, expected to be an RFC3339 timestamp string. | [optional] |
| **profile_integration_id** | **String** | Only return sessions for the customer that matches this customer integration ID. | [optional] |
| **date_format** | **String** | Determines the format of dates in the export document. | [optional] |
| **customer_session_state** | **String** | Filter results by state. | [optional] |

### Return type

**String**

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/csv


## export_customers_tiers

> String export_customers_tiers(loyalty_program_id, opts)

Export customers' tier data

Download a CSV file containing the tier information for customers of the specified loyalty program.  The generated file contains the following columns:  - `programid`: The identifier of the loyalty program. It is displayed in your Talon.One deployment URL. - `subledgerid`: The ID of the subledger associated with the loyalty program. This column is empty if the loyalty program has no subledger. In this case, refer to the export file name to get the ID of the loyalty program. - `customerprofileid`: The ID used to integrate customer profiles with the loyalty program. - `tiername`: The name of the tier. - `startdate`: The tier start date in RFC3339. - `expirydate`: The tier expiry date in RFC3339.  You can filter the results by providing the following optional input parameters:  - `subledgerIds` (optional): Filter results by an array of subledger IDs. If no value is provided, all subledger data for the specified loyalty program will be exported. - `tierNames` (optional): Filter results by an array of tier names. If no value is provided, all tier data for the specified loyalty program will be exported. 

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
loyalty_program_id = 'loyalty_program_id_example' # String | The identifier for the loyalty program.
opts = {
  subledger_ids: ['inner_example'], # Array<String> | An array of subledgers IDs to filter the export by.
  tier_names: ['inner_example'] # Array<String> | An array of tier names to filter the export by.
}

begin
  # Export customers' tier data
  result = api_instance.export_customers_tiers(loyalty_program_id, opts)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->export_customers_tiers: #{e}"
end
```

#### Using the export_customers_tiers_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(String, Integer, Hash)> export_customers_tiers_with_http_info(loyalty_program_id, opts)

```ruby
begin
  # Export customers' tier data
  data, status_code, headers = api_instance.export_customers_tiers_with_http_info(loyalty_program_id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => String
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->export_customers_tiers_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **loyalty_program_id** | **String** | The identifier for the loyalty program. |  |
| **subledger_ids** | [**Array&lt;String&gt;**](String.md) | An array of subledgers IDs to filter the export by. | [optional] |
| **tier_names** | [**Array&lt;String&gt;**](String.md) | An array of tier names to filter the export by. | [optional] |

### Return type

**String**

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/csv


## export_effects

> String export_effects(application_id, opts)

Export triggered effects

Download a CSV file containing the triggered effects that match the given attributes.  **Tip:** If the exported CSV file is too large to view, you can [split it into multiple files](https://www.makeuseof.com/tag/how-to-split-a-huge-csv-excel-workbook-into-seperate-files/).  The generated file can contain the following columns:  - `applicationid`: The ID of the Application. - `campaignid`: The ID of the campaign. - `couponid`: The ID of the coupon, when applicable to the effect. - `created`: The timestamp of the effect. - `event_type`: The name of the event. See the [docs](https://docs.talon.one/docs/dev/concepts/entities/events). - `eventid`: The internal ID of the effect. - `name`: The effect name. See the [docs](https://docs.talon.one/docs/dev/integration-api/api-effects). - `profileintegrationid`: The ID of the customer profile, when applicable. - `props`: The [properties](https://docs.talon.one/docs/dev/integration-api/api-effects) of the effect. - `ruleindex`: The index of the rule. - `rulesetid`: The ID of the rule set. - `sessionid`: The internal ID of the session that triggered the effect. - `profileid`: The internal ID of the customer profile. - `sessionintegrationid`: The integration ID of the session. - `total_revenue`: The total revenue. - `store_integration_id`: The integration ID of the store. You choose this ID when you create a store. 

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
application_id = 789 # Integer | The ID of the Application. It is displayed in your Talon.One deployment URL.
opts = {
  campaign_id: 8.14, # Float | Filter results by campaign ID.
  created_before: Time.parse('2013-10-20T19:20:30+01:00'), # Time | Filter results comparing the parameter value, expected to be an RFC3339 timestamp string. You can use any time zone setting. Talon.One will convert to UTC internally.
  created_after: Time.parse('2013-10-20T19:20:30+01:00'), # Time | Filter results comparing the parameter value, expected to be an RFC3339 timestamp string. You can use any time zone setting. Talon.One will convert to UTC internally.
  date_format: 'excel' # String | Determines the format of dates in the export document.
}

begin
  # Export triggered effects
  result = api_instance.export_effects(application_id, opts)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->export_effects: #{e}"
end
```

#### Using the export_effects_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(String, Integer, Hash)> export_effects_with_http_info(application_id, opts)

```ruby
begin
  # Export triggered effects
  data, status_code, headers = api_instance.export_effects_with_http_info(application_id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => String
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->export_effects_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **application_id** | **Integer** | The ID of the Application. It is displayed in your Talon.One deployment URL. |  |
| **campaign_id** | **Float** | Filter results by campaign ID. | [optional] |
| **created_before** | **Time** | Filter results comparing the parameter value, expected to be an RFC3339 timestamp string. You can use any time zone setting. Talon.One will convert to UTC internally. | [optional] |
| **created_after** | **Time** | Filter results comparing the parameter value, expected to be an RFC3339 timestamp string. You can use any time zone setting. Talon.One will convert to UTC internally. | [optional] |
| **date_format** | **String** | Determines the format of dates in the export document. | [optional] |

### Return type

**String**

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/csv


## export_loyalty_balance

> String export_loyalty_balance(loyalty_program_id, opts)

Export customer loyalty balance to CSV

⚠️ Deprecation notice: Support for requests to this endpoint will end soon. To export customer loyalty balances to CSV, use the [Export customer loyalty balances to CSV](/management-api#tag/Loyalty/operation/exportLoyaltyBalances) endpoint.  Download a CSV file containing the balance of each customer in the loyalty program.  **Tip:** If the exported CSV file is too large to view, you can [split it into multiple files](https://www.makeuseof.com/tag/how-to-split-a-huge-csv-excel-workbook-into-seperate-files/). 

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
loyalty_program_id = 'loyalty_program_id_example' # String | The identifier for the loyalty program.
opts = {
  end_date: Time.parse('2013-10-20T19:20:30+01:00') # Time | Used to return expired, active, and pending loyalty balances before this timestamp. You can enter any past, present, or future timestamp value.  **Note:**  - It must be an RFC3339 timestamp string. - You can include a time component in your string, for example, `T23:59:59` to specify the end of the day. The time zone setting considered is `UTC`. If you do not include a time component, a default time value of `T00:00:00` (midnight) in `UTC` is considered. 
}

begin
  # Export customer loyalty balance to CSV
  result = api_instance.export_loyalty_balance(loyalty_program_id, opts)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->export_loyalty_balance: #{e}"
end
```

#### Using the export_loyalty_balance_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(String, Integer, Hash)> export_loyalty_balance_with_http_info(loyalty_program_id, opts)

```ruby
begin
  # Export customer loyalty balance to CSV
  data, status_code, headers = api_instance.export_loyalty_balance_with_http_info(loyalty_program_id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => String
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->export_loyalty_balance_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **loyalty_program_id** | **String** | The identifier for the loyalty program. |  |
| **end_date** | **Time** | Used to return expired, active, and pending loyalty balances before this timestamp. You can enter any past, present, or future timestamp value.  **Note:**  - It must be an RFC3339 timestamp string. - You can include a time component in your string, for example, &#x60;T23:59:59&#x60; to specify the end of the day. The time zone setting considered is &#x60;UTC&#x60;. If you do not include a time component, a default time value of &#x60;T00:00:00&#x60; (midnight) in &#x60;UTC&#x60; is considered.  | [optional] |

### Return type

**String**

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/csv


## export_loyalty_balances

> String export_loyalty_balances(loyalty_program_id, opts)

Export customer loyalty balances

Download a CSV file containing the balance of each customer in the loyalty program.  **Tip:** If the exported CSV file is too large to view, you can [split it into multiple files](https://www.makeuseof.com/tag/how-to-split-a-huge-csv-excel-workbook-into-seperate-files/).  The generated file can contain the following columns:  - `loyaltyProgramID`: The ID of the loyalty program. - `loyaltySubledger`: The name of the subdleger, when applicatble. - `profileIntegrationID`: The integration ID of the customer profile. - `currentBalance`: The current point balance. - `pendingBalance`: The number of pending points. - `expiredBalance`: The number of expired points. - `spentBalance`: The number of spent points. - `currentTier`: The tier that the customer is in at the time of the export. 

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
loyalty_program_id = 'loyalty_program_id_example' # String | The identifier for the loyalty program.
opts = {
  end_date: Time.parse('2013-10-20T19:20:30+01:00') # Time | Used to return expired, active, and pending loyalty balances before this timestamp. You can enter any past, present, or future timestamp value.  **Note:**  - It must be an RFC3339 timestamp string. - You can include a time component in your string, for example, `T23:59:59` to specify the end of the day. The time zone setting considered is `UTC`. If you do not include a time component, a default time value of `T00:00:00` (midnight) in `UTC` is considered. - This parameter does not affect the `currentTier` field in the CSV file,  which shows the customer's tier at the time of export. 
}

begin
  # Export customer loyalty balances
  result = api_instance.export_loyalty_balances(loyalty_program_id, opts)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->export_loyalty_balances: #{e}"
end
```

#### Using the export_loyalty_balances_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(String, Integer, Hash)> export_loyalty_balances_with_http_info(loyalty_program_id, opts)

```ruby
begin
  # Export customer loyalty balances
  data, status_code, headers = api_instance.export_loyalty_balances_with_http_info(loyalty_program_id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => String
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->export_loyalty_balances_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **loyalty_program_id** | **String** | The identifier for the loyalty program. |  |
| **end_date** | **Time** | Used to return expired, active, and pending loyalty balances before this timestamp. You can enter any past, present, or future timestamp value.  **Note:**  - It must be an RFC3339 timestamp string. - You can include a time component in your string, for example, &#x60;T23:59:59&#x60; to specify the end of the day. The time zone setting considered is &#x60;UTC&#x60;. If you do not include a time component, a default time value of &#x60;T00:00:00&#x60; (midnight) in &#x60;UTC&#x60; is considered. - This parameter does not affect the &#x60;currentTier&#x60; field in the CSV file,  which shows the customer&#39;s tier at the time of export.  | [optional] |

### Return type

**String**

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/csv


## export_loyalty_card_balances

> String export_loyalty_card_balances(loyalty_program_id, opts)

Export all card transaction logs

Download a CSV file containing the balances of all cards in the loyalty program.  **Tip:** If the exported CSV file is too large to view, you can [split it into multiple files](https://www.makeuseof.com/tag/how-to-split-a-huge-csv-excel-workbook-into-seperate-files/).  The CSV file contains the following columns: - `loyaltyProgramID`: The ID of the loyalty program. - `loyaltySubledger`: The name of the subdleger, when applicatble. - `cardIdentifier`: The alphanumeric identifier of the loyalty card. - `cardState`:The state of the loyalty card. It can be `active` or `inactive`. - `currentBalance`: The current point balance. - `pendingBalance`: The number of pending points. - `expiredBalance`: The number of expired points. - `spentBalance`: The number of spent points. 

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
loyalty_program_id = 789 # Integer | Identifier of the card-based loyalty program containing the loyalty card. You can get the ID with the [List loyalty programs](https://docs.talon.one/management-api#tag/Loyalty/operation/getLoyaltyPrograms) endpoint. 
opts = {
  end_date: Time.parse('2013-10-20T19:20:30+01:00') # Time | Used to return expired, active, and pending loyalty balances before this timestamp. You can enter any past, present, or future timestamp value.  **Note:**  - It must be an RFC3339 timestamp string. - You can include a time component in your string, for example, `T23:59:59` to specify the end of the day. The time zone setting considered is `UTC`. If you do not include a time component, a default time value of `T00:00:00` (midnight) in `UTC` is considered. 
}

begin
  # Export all card transaction logs
  result = api_instance.export_loyalty_card_balances(loyalty_program_id, opts)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->export_loyalty_card_balances: #{e}"
end
```

#### Using the export_loyalty_card_balances_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(String, Integer, Hash)> export_loyalty_card_balances_with_http_info(loyalty_program_id, opts)

```ruby
begin
  # Export all card transaction logs
  data, status_code, headers = api_instance.export_loyalty_card_balances_with_http_info(loyalty_program_id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => String
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->export_loyalty_card_balances_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **loyalty_program_id** | **Integer** | Identifier of the card-based loyalty program containing the loyalty card. You can get the ID with the [List loyalty programs](https://docs.talon.one/management-api#tag/Loyalty/operation/getLoyaltyPrograms) endpoint.  |  |
| **end_date** | **Time** | Used to return expired, active, and pending loyalty balances before this timestamp. You can enter any past, present, or future timestamp value.  **Note:**  - It must be an RFC3339 timestamp string. - You can include a time component in your string, for example, &#x60;T23:59:59&#x60; to specify the end of the day. The time zone setting considered is &#x60;UTC&#x60;. If you do not include a time component, a default time value of &#x60;T00:00:00&#x60; (midnight) in &#x60;UTC&#x60; is considered.  | [optional] |

### Return type

**String**

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/csv


## export_loyalty_card_ledger

> String export_loyalty_card_ledger(loyalty_program_id, loyalty_card_id, range_start, range_end, opts)

Export card's ledger log

Download a CSV file containing a loyalty card ledger log of the loyalty program.  **Tip:** If the exported CSV file is too large to view, you can [split it into multiple files](https://www.makeuseof.com/tag/how-to-split-a-huge-csv-excel-workbook-into-seperate-files/). 

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
loyalty_program_id = 789 # Integer | Identifier of the card-based loyalty program containing the loyalty card. You can get the ID with the [List loyalty programs](https://docs.talon.one/management-api#tag/Loyalty/operation/getLoyaltyPrograms) endpoint. 
loyalty_card_id = 'loyalty_card_id_example' # String | Identifier of the loyalty card. You can get the identifier with the [List loyalty cards](https://docs.talon.one/management-api#tag/Loyalty-cards/operation/getLoyaltyCards) endpoint. 
range_start = Time.parse('2013-10-20T19:20:30+01:00') # Time | Only return results from after this timestamp.  **Note:** - This must be an RFC3339 timestamp string. - You can include a time component in your string, for example, `T23:59:59` to specify the end of the day. The time zone setting considered is `UTC`. If you do not include a time component, a default time value of `T00:00:00` (midnight) in `UTC` is considered. 
range_end = Time.parse('2013-10-20T19:20:30+01:00') # Time | Only return results from before this timestamp.  **Note:** - This must be an RFC3339 timestamp string. - You can include a time component in your string, for example, `T23:59:59` to specify the end of the day. The time zone setting considered is `UTC`. If you do not include a time component, a default time value of `T00:00:00` (midnight) in `UTC` is considered. 
opts = {
  date_format: 'excel' # String | Determines the format of dates in the export document.
}

begin
  # Export card's ledger log
  result = api_instance.export_loyalty_card_ledger(loyalty_program_id, loyalty_card_id, range_start, range_end, opts)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->export_loyalty_card_ledger: #{e}"
end
```

#### Using the export_loyalty_card_ledger_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(String, Integer, Hash)> export_loyalty_card_ledger_with_http_info(loyalty_program_id, loyalty_card_id, range_start, range_end, opts)

```ruby
begin
  # Export card's ledger log
  data, status_code, headers = api_instance.export_loyalty_card_ledger_with_http_info(loyalty_program_id, loyalty_card_id, range_start, range_end, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => String
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->export_loyalty_card_ledger_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **loyalty_program_id** | **Integer** | Identifier of the card-based loyalty program containing the loyalty card. You can get the ID with the [List loyalty programs](https://docs.talon.one/management-api#tag/Loyalty/operation/getLoyaltyPrograms) endpoint.  |  |
| **loyalty_card_id** | **String** | Identifier of the loyalty card. You can get the identifier with the [List loyalty cards](https://docs.talon.one/management-api#tag/Loyalty-cards/operation/getLoyaltyCards) endpoint.  |  |
| **range_start** | **Time** | Only return results from after this timestamp.  **Note:** - This must be an RFC3339 timestamp string. - You can include a time component in your string, for example, &#x60;T23:59:59&#x60; to specify the end of the day. The time zone setting considered is &#x60;UTC&#x60;. If you do not include a time component, a default time value of &#x60;T00:00:00&#x60; (midnight) in &#x60;UTC&#x60; is considered.  |  |
| **range_end** | **Time** | Only return results from before this timestamp.  **Note:** - This must be an RFC3339 timestamp string. - You can include a time component in your string, for example, &#x60;T23:59:59&#x60; to specify the end of the day. The time zone setting considered is &#x60;UTC&#x60;. If you do not include a time component, a default time value of &#x60;T00:00:00&#x60; (midnight) in &#x60;UTC&#x60; is considered.  |  |
| **date_format** | **String** | Determines the format of dates in the export document. | [optional] |

### Return type

**String**

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/csv


## export_loyalty_cards

> String export_loyalty_cards(loyalty_program_id, opts)

Export loyalty cards

Download a CSV file containing the loyalty cards from a specified loyalty program.  **Tip:** If the exported CSV file is too large to view, you can [split it into multiple files](https://www.makeuseof.com/tag/how-to-split-a-huge-csv-excel-workbook-into-seperate-files/).  The CSV file contains the following columns: - `identifier`: The unique identifier of the loyalty card. - `created`: The date and time the loyalty card was created. - `status`: The status of the loyalty card. - `userpercardlimit`: The maximum number of customer profiles that can be linked to the card. - `customerprofileids`: Integration IDs of the customer profiles linked to the card. - `blockreason`: The reason for transferring and blocking the loyalty card. - `generated`: An indicator of whether the loyalty card was generated. - `batchid`: The ID of the batch the loyalty card is in. 

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
loyalty_program_id = 789 # Integer | Identifier of the card-based loyalty program containing the loyalty card. You can get the ID with the [List loyalty programs](https://docs.talon.one/management-api#tag/Loyalty/operation/getLoyaltyPrograms) endpoint. 
opts = {
  batch_id: 'batch_id_example', # String | Filter results by loyalty card batch ID.
  created_before: Time.parse('2013-10-20T19:20:30+01:00'), # Time | Only return loyalty cards created before this timestamp.  **Note:** - This must be an RFC3339 timestamp string. 
  created_after: Time.parse('2013-10-20T19:20:30+01:00'), # Time | Only return loyalty cards created after this timestamp.  **Note:** - This must be an RFC3339 timestamp string. 
  date_format: 'excel' # String | Determines the format of dates in the export document.
}

begin
  # Export loyalty cards
  result = api_instance.export_loyalty_cards(loyalty_program_id, opts)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->export_loyalty_cards: #{e}"
end
```

#### Using the export_loyalty_cards_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(String, Integer, Hash)> export_loyalty_cards_with_http_info(loyalty_program_id, opts)

```ruby
begin
  # Export loyalty cards
  data, status_code, headers = api_instance.export_loyalty_cards_with_http_info(loyalty_program_id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => String
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->export_loyalty_cards_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **loyalty_program_id** | **Integer** | Identifier of the card-based loyalty program containing the loyalty card. You can get the ID with the [List loyalty programs](https://docs.talon.one/management-api#tag/Loyalty/operation/getLoyaltyPrograms) endpoint.  |  |
| **batch_id** | **String** | Filter results by loyalty card batch ID. | [optional] |
| **created_before** | **Time** | Only return loyalty cards created before this timestamp.  **Note:** - This must be an RFC3339 timestamp string.  | [optional] |
| **created_after** | **Time** | Only return loyalty cards created after this timestamp.  **Note:** - This must be an RFC3339 timestamp string.  | [optional] |
| **date_format** | **String** | Determines the format of dates in the export document. | [optional] |

### Return type

**String**

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/csv


## export_loyalty_ledger

> String export_loyalty_ledger(range_start, range_end, loyalty_program_id, integration_id, opts)

Export customer's transaction logs

Download a CSV file containing a customer's transaction logs in the loyalty program.  **Tip:** If the exported CSV file is too large to view, you can [split it into multiple files](https://www.makeuseof.com/tag/how-to-split-a-huge-csv-excel-workbook-into-seperate-files/).  The generated file can contain the following columns:  - `customerprofileid`: The ID of the profile. - `customersessionid`: The ID of the customer session. - `rulesetid`: The ID of the rule set. - `rulename`: The name of the rule. - `programid`: The ID of the loyalty program. - `type`: The transaction type, such as `addition` or `subtraction`. - `name`: The reason for the transaction. - `subledgerid`: The ID of the subledger, when applicable. - `startdate`: The start date of the program. - `expirydate`: The expiration date of the program. - `id`: The ID of the transaction. - `created`: The timestamp of the creation of the loyalty program. - `amount`: The number of points in that transaction. - `archived`: Whether the session related to the transaction is archived. - `campaignid`: The ID of the campaign. - `flags`: The flags of the transaction, when applicable. The `createsNegativeBalance` flag indicates whether the transaction results in a negative balance. - `transactionUUID`: Unique identifier of the transaction in the UUID format. 

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
range_start = Time.parse('2013-10-20T19:20:30+01:00') # Time | Only return results from after this timestamp.  **Note:** - This must be an RFC3339 timestamp string. - You can include a time component in your string, for example, `T23:59:59` to specify the end of the day. The time zone setting considered is `UTC`. If you do not include a time component, a default time value of `T00:00:00` (midnight) in `UTC` is considered. 
range_end = Time.parse('2013-10-20T19:20:30+01:00') # Time | Only return results from before this timestamp.  **Note:** - This must be an RFC3339 timestamp string. - You can include a time component in your string, for example, `T23:59:59` to specify the end of the day. The time zone setting considered is `UTC`. If you do not include a time component, a default time value of `T00:00:00` (midnight) in `UTC` is considered. 
loyalty_program_id = 'loyalty_program_id_example' # String | The identifier for the loyalty program.
integration_id = 'integration_id_example' # String | The integration identifier for this customer profile. Must be: - Unique within the deployment. - Stable for the customer. Do not use an ID that the customer can update themselves. For example, you can use a database ID.  Once set, you cannot update this identifier. 
opts = {
  date_format: 'excel' # String | Determines the format of dates in the export document.
}

begin
  # Export customer's transaction logs
  result = api_instance.export_loyalty_ledger(range_start, range_end, loyalty_program_id, integration_id, opts)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->export_loyalty_ledger: #{e}"
end
```

#### Using the export_loyalty_ledger_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(String, Integer, Hash)> export_loyalty_ledger_with_http_info(range_start, range_end, loyalty_program_id, integration_id, opts)

```ruby
begin
  # Export customer's transaction logs
  data, status_code, headers = api_instance.export_loyalty_ledger_with_http_info(range_start, range_end, loyalty_program_id, integration_id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => String
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->export_loyalty_ledger_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **range_start** | **Time** | Only return results from after this timestamp.  **Note:** - This must be an RFC3339 timestamp string. - You can include a time component in your string, for example, &#x60;T23:59:59&#x60; to specify the end of the day. The time zone setting considered is &#x60;UTC&#x60;. If you do not include a time component, a default time value of &#x60;T00:00:00&#x60; (midnight) in &#x60;UTC&#x60; is considered.  |  |
| **range_end** | **Time** | Only return results from before this timestamp.  **Note:** - This must be an RFC3339 timestamp string. - You can include a time component in your string, for example, &#x60;T23:59:59&#x60; to specify the end of the day. The time zone setting considered is &#x60;UTC&#x60;. If you do not include a time component, a default time value of &#x60;T00:00:00&#x60; (midnight) in &#x60;UTC&#x60; is considered.  |  |
| **loyalty_program_id** | **String** | The identifier for the loyalty program. |  |
| **integration_id** | **String** | The integration identifier for this customer profile. Must be: - Unique within the deployment. - Stable for the customer. Do not use an ID that the customer can update themselves. For example, you can use a database ID.  Once set, you cannot update this identifier.  |  |
| **date_format** | **String** | Determines the format of dates in the export document. | [optional] |

### Return type

**String**

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/csv


## export_pool_giveaways

> String export_pool_giveaways(pool_id, opts)

Export giveaway codes of a giveaway pool

Download a CSV file containing the giveaway codes of a specific giveaway pool.  **Tip:** If the exported CSV file is too large to view, you can [split it into multiple files](https://www.makeuseof.com/tag/how-to-split-a-huge-csv-excel-workbook-into-seperate-files/).  The CSV file contains the following columns:  - `id`: The internal ID of the giveaway. - `poolid`: The internal ID of the giveaway pool. - `code`: The giveaway code. - `startdate`: The validity start date in RFC3339 of the giveaway (can be empty). - `enddate`: The validity end date in RFC3339 of the giveaway (can be empty). - `attributes`: Any custom attributes associated with the giveaway code (can be empty). - `used`: An indication of whether the giveaway is already awarded. - `importid`: The ID of the import which created the giveaway. - `created`: The creation time of the giveaway code. - `profileintegrationid`: The third-party integration ID of the customer profile that was awarded the giveaway. Can be empty if the giveaway was not awarded. - `profileid`: The internal ID of the customer profile that was awarded the giveaway. Can be empty if the giveaway was not awarded or an internal ID does not exist. 

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
pool_id = 789 # Integer | The ID of the pool. You can find it in the Campaign Manager, in the **Giveaways** section.
opts = {
  created_before: Time.parse('2013-10-20T19:20:30+01:00'), # Time | Timestamp that filters the results to only contain giveaways created before this date. Must be an RFC3339 timestamp string.
  created_after: Time.parse('2013-10-20T19:20:30+01:00') # Time | Timestamp that filters the results to only contain giveaways created after this date. Must be an RFC3339 timestamp string.
}

begin
  # Export giveaway codes of a giveaway pool
  result = api_instance.export_pool_giveaways(pool_id, opts)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->export_pool_giveaways: #{e}"
end
```

#### Using the export_pool_giveaways_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(String, Integer, Hash)> export_pool_giveaways_with_http_info(pool_id, opts)

```ruby
begin
  # Export giveaway codes of a giveaway pool
  data, status_code, headers = api_instance.export_pool_giveaways_with_http_info(pool_id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => String
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->export_pool_giveaways_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **pool_id** | **Integer** | The ID of the pool. You can find it in the Campaign Manager, in the **Giveaways** section. |  |
| **created_before** | **Time** | Timestamp that filters the results to only contain giveaways created before this date. Must be an RFC3339 timestamp string. | [optional] |
| **created_after** | **Time** | Timestamp that filters the results to only contain giveaways created after this date. Must be an RFC3339 timestamp string. | [optional] |

### Return type

**String**

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/csv


## export_referrals

> String export_referrals(application_id, opts)

Export referrals

Download a CSV file containing the referrals that match the given parameters.  **Tip:** If the exported CSV file is too large to view, you can [split it into multiple files](https://www.makeuseof.com/tag/how-to-split-a-huge-csv-excel-workbook-into-seperate-files/).  The CSV file contains the following columns:  - `code`: The referral code. - `advocateprofileintegrationid`: The profile ID of the advocate. - `startdate`: The start date in RFC3339 of the code redemption period. - `expirydate`: The end date in RFC3339 of the code redemption period. - `limitval`: The maximum number of redemptions of this code. Defaults to `1` when left blank. - `attributes`: A json object describing _custom_ referral attribute names and their values. 

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
application_id = 789 # Integer | The ID of the Application. It is displayed in your Talon.One deployment URL.
opts = {
  campaign_id: 8.14, # Float | Filter results by campaign ID.
  created_before: Time.parse('2013-10-20T19:20:30+01:00'), # Time | Filter results comparing the parameter value, expected to be an RFC3339 timestamp string, to the referral creation timestamp. You can use any time zone setting. Talon.One will convert to UTC internally.
  created_after: Time.parse('2013-10-20T19:20:30+01:00'), # Time | Filter results comparing the parameter value, expected to be an RFC3339 timestamp string, to the referral creation timestamp. You can use any time zone setting. Talon.One will convert to UTC internally.
  valid: 'expired', # String | - `expired`: Matches referrals in which the expiration date is set and in the past. - `validNow`: Matches referrals in which start date is null or in the past and expiration date is null or in the future. - `validFuture`: Matches referrals in which start date is set and in the future. 
  usable: 'true', # String | - `true`, only referrals where `usageCounter < usageLimit` will be returned. - `false`, only referrals where `usageCounter >= usageLimit` will be returned. 
  batch_id: 'batch_id_example', # String | Filter results by batches of referrals
  date_format: 'excel' # String | Determines the format of dates in the export document.
}

begin
  # Export referrals
  result = api_instance.export_referrals(application_id, opts)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->export_referrals: #{e}"
end
```

#### Using the export_referrals_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(String, Integer, Hash)> export_referrals_with_http_info(application_id, opts)

```ruby
begin
  # Export referrals
  data, status_code, headers = api_instance.export_referrals_with_http_info(application_id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => String
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->export_referrals_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **application_id** | **Integer** | The ID of the Application. It is displayed in your Talon.One deployment URL. |  |
| **campaign_id** | **Float** | Filter results by campaign ID. | [optional] |
| **created_before** | **Time** | Filter results comparing the parameter value, expected to be an RFC3339 timestamp string, to the referral creation timestamp. You can use any time zone setting. Talon.One will convert to UTC internally. | [optional] |
| **created_after** | **Time** | Filter results comparing the parameter value, expected to be an RFC3339 timestamp string, to the referral creation timestamp. You can use any time zone setting. Talon.One will convert to UTC internally. | [optional] |
| **valid** | **String** | - &#x60;expired&#x60;: Matches referrals in which the expiration date is set and in the past. - &#x60;validNow&#x60;: Matches referrals in which start date is null or in the past and expiration date is null or in the future. - &#x60;validFuture&#x60;: Matches referrals in which start date is set and in the future.  | [optional] |
| **usable** | **String** | - &#x60;true&#x60;, only referrals where &#x60;usageCounter &lt; usageLimit&#x60; will be returned. - &#x60;false&#x60;, only referrals where &#x60;usageCounter &gt;&#x3D; usageLimit&#x60; will be returned.  | [optional] |
| **batch_id** | **String** | Filter results by batches of referrals | [optional] |
| **date_format** | **String** | Determines the format of dates in the export document. | [optional] |

### Return type

**String**

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/csv


## generate_coupon_rejections

> <GenerateCouponRejections200Response> generate_coupon_rejections(session_integration_id, opts)

Summarize coupon redemption failures in session

Create a summary of the reasons for coupon redemption failures in a given customer session. 

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
session_integration_id = 'session_integration_id_example' # String | The integration ID of the session to summarize.
opts = {
  application_id: 8.14, # Float | Filter results by Application ID.
  language: 'language_example', # String | The [ISO-639](https://en.wikipedia.org/wiki/List_of_ISO_639_language_codes) code of the language in which the summary will be generated. 
  coupon_code: 'coupon_code_example' # String | The coupon code for which to get the rejection reason.
}

begin
  # Summarize coupon redemption failures in session
  result = api_instance.generate_coupon_rejections(session_integration_id, opts)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->generate_coupon_rejections: #{e}"
end
```

#### Using the generate_coupon_rejections_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<GenerateCouponRejections200Response>, Integer, Hash)> generate_coupon_rejections_with_http_info(session_integration_id, opts)

```ruby
begin
  # Summarize coupon redemption failures in session
  data, status_code, headers = api_instance.generate_coupon_rejections_with_http_info(session_integration_id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <GenerateCouponRejections200Response>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->generate_coupon_rejections_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **session_integration_id** | **String** | The integration ID of the session to summarize. |  |
| **application_id** | **Float** | Filter results by Application ID. | [optional] |
| **language** | **String** | The [ISO-639](https://en.wikipedia.org/wiki/List_of_ISO_639_language_codes) code of the language in which the summary will be generated.  | [optional] |
| **coupon_code** | **String** | The coupon code for which to get the rejection reason. | [optional] |

### Return type

[**GenerateCouponRejections200Response**](GenerateCouponRejections200Response.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_access_logs_without_total_count

> <GetAccessLogsWithoutTotalCount200Response> get_access_logs_without_total_count(application_id, range_start, range_end, opts)

Get access logs for Application

Retrieve the list of API calls sent to the specified Application. 

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
application_id = 789 # Integer | The ID of the Application. It is displayed in your Talon.One deployment URL.
range_start = Time.parse('2013-10-20T19:20:30+01:00') # Time | Only return results from after this timestamp.  **Note:** - This must be an RFC3339 timestamp string. - You can include a time component in your string, for example, `T23:59:59` to specify the end of the day. The time zone setting considered is `UTC`. If you do not include a time component, a default time value of `T00:00:00` (midnight) in `UTC` is considered. 
range_end = Time.parse('2013-10-20T19:20:30+01:00') # Time | Only return results from before this timestamp.  **Note:** - This must be an RFC3339 timestamp string. - You can include a time component in your string, for example, `T23:59:59` to specify the end of the day. The time zone setting considered is `UTC`. If you do not include a time component, a default time value of `T00:00:00` (midnight) in `UTC` is considered. 
opts = {
  path: 'path_example', # String | Only return results where the request path matches the given regular expression.
  method: 'get', # String | Only return results where the request method matches the given regular expression.
  status: 'success', # String | Filter results by HTTP status codes.
  page_size: 789, # Integer | The number of items in the response.
  skip: 789, # Integer | The number of items to skip when paging through large result sets.
  sort: 'sort_example' # String | The field by which results should be sorted. By default, results are sorted in ascending order. To sort them in descending order, prefix the field name with `-`.  **Note:** You may not be able to use all fields for sorting. This is due to performance limitations. 
}

begin
  # Get access logs for Application
  result = api_instance.get_access_logs_without_total_count(application_id, range_start, range_end, opts)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_access_logs_without_total_count: #{e}"
end
```

#### Using the get_access_logs_without_total_count_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<GetAccessLogsWithoutTotalCount200Response>, Integer, Hash)> get_access_logs_without_total_count_with_http_info(application_id, range_start, range_end, opts)

```ruby
begin
  # Get access logs for Application
  data, status_code, headers = api_instance.get_access_logs_without_total_count_with_http_info(application_id, range_start, range_end, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <GetAccessLogsWithoutTotalCount200Response>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_access_logs_without_total_count_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **application_id** | **Integer** | The ID of the Application. It is displayed in your Talon.One deployment URL. |  |
| **range_start** | **Time** | Only return results from after this timestamp.  **Note:** - This must be an RFC3339 timestamp string. - You can include a time component in your string, for example, &#x60;T23:59:59&#x60; to specify the end of the day. The time zone setting considered is &#x60;UTC&#x60;. If you do not include a time component, a default time value of &#x60;T00:00:00&#x60; (midnight) in &#x60;UTC&#x60; is considered.  |  |
| **range_end** | **Time** | Only return results from before this timestamp.  **Note:** - This must be an RFC3339 timestamp string. - You can include a time component in your string, for example, &#x60;T23:59:59&#x60; to specify the end of the day. The time zone setting considered is &#x60;UTC&#x60;. If you do not include a time component, a default time value of &#x60;T00:00:00&#x60; (midnight) in &#x60;UTC&#x60; is considered.  |  |
| **path** | **String** | Only return results where the request path matches the given regular expression. | [optional] |
| **method** | **String** | Only return results where the request method matches the given regular expression. | [optional] |
| **status** | **String** | Filter results by HTTP status codes. | [optional] |
| **page_size** | **Integer** | The number of items in the response. | [optional][default to 1000] |
| **skip** | **Integer** | The number of items to skip when paging through large result sets. | [optional] |
| **sort** | **String** | The field by which results should be sorted. By default, results are sorted in ascending order. To sort them in descending order, prefix the field name with &#x60;-&#x60;.  **Note:** You may not be able to use all fields for sorting. This is due to performance limitations.  | [optional] |

### Return type

[**GetAccessLogsWithoutTotalCount200Response**](GetAccessLogsWithoutTotalCount200Response.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_account

> <Account> get_account(account_id)

Get account details

Return the details of your companies Talon.One account. 

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
account_id = 789 # Integer | The identifier of the account. Retrieve it via the [List users in account](https://docs.talon.one/management-api#operation/getUsers) endpoint in the `accountId` property. 

begin
  # Get account details
  result = api_instance.get_account(account_id)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_account: #{e}"
end
```

#### Using the get_account_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<Account>, Integer, Hash)> get_account_with_http_info(account_id)

```ruby
begin
  # Get account details
  data, status_code, headers = api_instance.get_account_with_http_info(account_id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <Account>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_account_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **account_id** | **Integer** | The identifier of the account. Retrieve it via the [List users in account](https://docs.talon.one/management-api#operation/getUsers) endpoint in the &#x60;accountId&#x60; property.  |  |

### Return type

[**Account**](Account.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_account_analytics

> <AccountAnalytics> get_account_analytics(account_id)

Get account analytics

Return the analytics of your Talon.One account. 

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
account_id = 789 # Integer | The identifier of the account. Retrieve it via the [List users in account](https://docs.talon.one/management-api#operation/getUsers) endpoint in the `accountId` property. 

begin
  # Get account analytics
  result = api_instance.get_account_analytics(account_id)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_account_analytics: #{e}"
end
```

#### Using the get_account_analytics_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<AccountAnalytics>, Integer, Hash)> get_account_analytics_with_http_info(account_id)

```ruby
begin
  # Get account analytics
  data, status_code, headers = api_instance.get_account_analytics_with_http_info(account_id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <AccountAnalytics>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_account_analytics_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **account_id** | **Integer** | The identifier of the account. Retrieve it via the [List users in account](https://docs.talon.one/management-api#operation/getUsers) endpoint in the &#x60;accountId&#x60; property.  |  |

### Return type

[**AccountAnalytics**](AccountAnalytics.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_account_collection

> <Collection> get_account_collection(collection_id)

Get account-level collection

Retrieve a given account-level collection.

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
collection_id = 789 # Integer | The ID of the collection. You can get it with the [List collections in account](#operation/listAccountCollections) endpoint.

begin
  # Get account-level collection
  result = api_instance.get_account_collection(collection_id)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_account_collection: #{e}"
end
```

#### Using the get_account_collection_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<Collection>, Integer, Hash)> get_account_collection_with_http_info(collection_id)

```ruby
begin
  # Get account-level collection
  data, status_code, headers = api_instance.get_account_collection_with_http_info(collection_id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <Collection>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_account_collection_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **collection_id** | **Integer** | The ID of the collection. You can get it with the [List collections in account](#operation/listAccountCollections) endpoint. |  |

### Return type

[**Collection**](Collection.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_achievement

> <Achievement> get_achievement(application_id, campaign_id, achievement_id)

Get achievement

Get the details of a specific achievement.

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
application_id = 789 # Integer | The ID of the Application. It is displayed in your Talon.One deployment URL.
campaign_id = 789 # Integer | The ID of the campaign. It is displayed in your Talon.One deployment URL.
achievement_id = 789 # Integer | The ID of the achievement. You can get this ID with the [List achievement](https://docs.talon.one/management-api#tag/Achievements/operation/listAchievements) endpoint.

begin
  # Get achievement
  result = api_instance.get_achievement(application_id, campaign_id, achievement_id)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_achievement: #{e}"
end
```

#### Using the get_achievement_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<Achievement>, Integer, Hash)> get_achievement_with_http_info(application_id, campaign_id, achievement_id)

```ruby
begin
  # Get achievement
  data, status_code, headers = api_instance.get_achievement_with_http_info(application_id, campaign_id, achievement_id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <Achievement>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_achievement_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **application_id** | **Integer** | The ID of the Application. It is displayed in your Talon.One deployment URL. |  |
| **campaign_id** | **Integer** | The ID of the campaign. It is displayed in your Talon.One deployment URL. |  |
| **achievement_id** | **Integer** | The ID of the achievement. You can get this ID with the [List achievement](https://docs.talon.one/management-api#tag/Achievements/operation/listAchievements) endpoint. |  |

### Return type

[**Achievement**](Achievement.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_additional_cost

> <AccountAdditionalCost> get_additional_cost(additional_cost_id)

Get additional cost

Returns the additional cost. 

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
additional_cost_id = 789 # Integer | The ID of the additional cost. You can find the ID the the Campaign Manager's URL when you display the details of the cost in **Account** > **Tools** > **Additional costs**. 

begin
  # Get additional cost
  result = api_instance.get_additional_cost(additional_cost_id)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_additional_cost: #{e}"
end
```

#### Using the get_additional_cost_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<AccountAdditionalCost>, Integer, Hash)> get_additional_cost_with_http_info(additional_cost_id)

```ruby
begin
  # Get additional cost
  data, status_code, headers = api_instance.get_additional_cost_with_http_info(additional_cost_id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <AccountAdditionalCost>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_additional_cost_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **additional_cost_id** | **Integer** | The ID of the additional cost. You can find the ID the the Campaign Manager&#39;s URL when you display the details of the cost in **Account** &gt; **Tools** &gt; **Additional costs**.  |  |

### Return type

[**AccountAdditionalCost**](AccountAdditionalCost.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_additional_costs

> <GetAdditionalCosts200Response> get_additional_costs(opts)

List additional costs

Returns all the defined additional costs for the account. 

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
opts = {
  page_size: 789, # Integer | The number of items in the response.
  skip: 789, # Integer | The number of items to skip when paging through large result sets.
  sort: 'sort_example' # String | The field by which results should be sorted. By default, results are sorted in ascending order. To sort them in descending order, prefix the field name with `-`.  **Note:** You may not be able to use all fields for sorting. This is due to performance limitations. 
}

begin
  # List additional costs
  result = api_instance.get_additional_costs(opts)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_additional_costs: #{e}"
end
```

#### Using the get_additional_costs_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<GetAdditionalCosts200Response>, Integer, Hash)> get_additional_costs_with_http_info(opts)

```ruby
begin
  # List additional costs
  data, status_code, headers = api_instance.get_additional_costs_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <GetAdditionalCosts200Response>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_additional_costs_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **page_size** | **Integer** | The number of items in the response. | [optional][default to 1000] |
| **skip** | **Integer** | The number of items to skip when paging through large result sets. | [optional] |
| **sort** | **String** | The field by which results should be sorted. By default, results are sorted in ascending order. To sort them in descending order, prefix the field name with &#x60;-&#x60;.  **Note:** You may not be able to use all fields for sorting. This is due to performance limitations.  | [optional] |

### Return type

[**GetAdditionalCosts200Response**](GetAdditionalCosts200Response.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_application

> <Application> get_application(application_id)

Get Application

Get the application specified by the ID.

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
application_id = 789 # Integer | The ID of the Application. It is displayed in your Talon.One deployment URL.

begin
  # Get Application
  result = api_instance.get_application(application_id)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_application: #{e}"
end
```

#### Using the get_application_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<Application>, Integer, Hash)> get_application_with_http_info(application_id)

```ruby
begin
  # Get Application
  data, status_code, headers = api_instance.get_application_with_http_info(application_id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <Application>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_application_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **application_id** | **Integer** | The ID of the Application. It is displayed in your Talon.One deployment URL. |  |

### Return type

[**Application**](Application.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_application_api_health

> <ApplicationApiHealth> get_application_api_health(application_id)

Get Application health

Display the health of the Application and show the last time the Application was used.  You can also find this information in the Campaign Manager. In your Application, click **Settings** > **Integration API Keys**. See the [docs](https://docs.talon.one/docs/dev/tutorials/monitoring-integration-status). 

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
application_id = 789 # Integer | The ID of the Application. It is displayed in your Talon.One deployment URL.

begin
  # Get Application health
  result = api_instance.get_application_api_health(application_id)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_application_api_health: #{e}"
end
```

#### Using the get_application_api_health_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<ApplicationApiHealth>, Integer, Hash)> get_application_api_health_with_http_info(application_id)

```ruby
begin
  # Get Application health
  data, status_code, headers = api_instance.get_application_api_health_with_http_info(application_id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <ApplicationApiHealth>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_application_api_health_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **application_id** | **Integer** | The ID of the Application. It is displayed in your Talon.One deployment URL. |  |

### Return type

[**ApplicationApiHealth**](ApplicationApiHealth.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_application_customer

> <ApplicationCustomer> get_application_customer(application_id, customer_id)

Get application's customer

Retrieve the customers of the specified application. 

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
application_id = 789 # Integer | The ID of the Application. It is displayed in your Talon.One deployment URL.
customer_id = 789 # Integer | The value of the `id` property of a customer profile. Get it with the [List Application's customers](https://docs.talon.one/management-api#operation/getApplicationCustomers) endpoint. 

begin
  # Get application's customer
  result = api_instance.get_application_customer(application_id, customer_id)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_application_customer: #{e}"
end
```

#### Using the get_application_customer_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<ApplicationCustomer>, Integer, Hash)> get_application_customer_with_http_info(application_id, customer_id)

```ruby
begin
  # Get application's customer
  data, status_code, headers = api_instance.get_application_customer_with_http_info(application_id, customer_id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <ApplicationCustomer>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_application_customer_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **application_id** | **Integer** | The ID of the Application. It is displayed in your Talon.One deployment URL. |  |
| **customer_id** | **Integer** | The value of the &#x60;id&#x60; property of a customer profile. Get it with the [List Application&#39;s customers](https://docs.talon.one/management-api#operation/getApplicationCustomers) endpoint.  |  |

### Return type

[**ApplicationCustomer**](ApplicationCustomer.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_application_customer_friends

> <GetApplicationCustomerFriends200Response> get_application_customer_friends(application_id, integration_id, opts)

List friends referred by customer profile

List the friends referred by the specified customer profile in this Application. 

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
application_id = 789 # Integer | The ID of the Application. It is displayed in your Talon.One deployment URL.
integration_id = 'integration_id_example' # String | The Integration ID of the Advocate's Profile.
opts = {
  page_size: 789, # Integer | The number of items in the response.
  skip: 789, # Integer | The number of items to skip when paging through large result sets.
  sort: 'sort_example', # String | The field by which results should be sorted. By default, results are sorted in ascending order. To sort them in descending order, prefix the field name with `-`.  **Note:** You may not be able to use all fields for sorting. This is due to performance limitations. 
  with_total_result_size: true # Boolean | When this flag is set, the result includes the total size of the result, across all pages. This might decrease performance on large data sets.  - When `true`: `hasMore` is true when there is a next page. `totalResultSize` is always zero. - When `false`: `hasMore` is always false. `totalResultSize` contains the total number of results for this query. 
}

begin
  # List friends referred by customer profile
  result = api_instance.get_application_customer_friends(application_id, integration_id, opts)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_application_customer_friends: #{e}"
end
```

#### Using the get_application_customer_friends_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<GetApplicationCustomerFriends200Response>, Integer, Hash)> get_application_customer_friends_with_http_info(application_id, integration_id, opts)

```ruby
begin
  # List friends referred by customer profile
  data, status_code, headers = api_instance.get_application_customer_friends_with_http_info(application_id, integration_id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <GetApplicationCustomerFriends200Response>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_application_customer_friends_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **application_id** | **Integer** | The ID of the Application. It is displayed in your Talon.One deployment URL. |  |
| **integration_id** | **String** | The Integration ID of the Advocate&#39;s Profile. |  |
| **page_size** | **Integer** | The number of items in the response. | [optional][default to 1000] |
| **skip** | **Integer** | The number of items to skip when paging through large result sets. | [optional] |
| **sort** | **String** | The field by which results should be sorted. By default, results are sorted in ascending order. To sort them in descending order, prefix the field name with &#x60;-&#x60;.  **Note:** You may not be able to use all fields for sorting. This is due to performance limitations.  | [optional] |
| **with_total_result_size** | **Boolean** | When this flag is set, the result includes the total size of the result, across all pages. This might decrease performance on large data sets.  - When &#x60;true&#x60;: &#x60;hasMore&#x60; is true when there is a next page. &#x60;totalResultSize&#x60; is always zero. - When &#x60;false&#x60;: &#x60;hasMore&#x60; is always false. &#x60;totalResultSize&#x60; contains the total number of results for this query.  | [optional] |

### Return type

[**GetApplicationCustomerFriends200Response**](GetApplicationCustomerFriends200Response.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_application_customers

> <GetApplicationCustomers200Response> get_application_customers(application_id, opts)

List application's customers

List all the customers of the specified application.

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
application_id = 789 # Integer | The ID of the Application. It is displayed in your Talon.One deployment URL.
opts = {
  integration_id: 'integration_id_example', # String | Filter results performing an exact matching against the profile integration identifier.
  page_size: 789, # Integer | The number of items in the response.
  skip: 789, # Integer | The number of items to skip when paging through large result sets.
  with_total_result_size: true # Boolean | When this flag is set, the result includes the total size of the result, across all pages. This might decrease performance on large data sets.  - When `true`: `hasMore` is true when there is a next page. `totalResultSize` is always zero. - When `false`: `hasMore` is always false. `totalResultSize` contains the total number of results for this query. 
}

begin
  # List application's customers
  result = api_instance.get_application_customers(application_id, opts)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_application_customers: #{e}"
end
```

#### Using the get_application_customers_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<GetApplicationCustomers200Response>, Integer, Hash)> get_application_customers_with_http_info(application_id, opts)

```ruby
begin
  # List application's customers
  data, status_code, headers = api_instance.get_application_customers_with_http_info(application_id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <GetApplicationCustomers200Response>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_application_customers_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **application_id** | **Integer** | The ID of the Application. It is displayed in your Talon.One deployment URL. |  |
| **integration_id** | **String** | Filter results performing an exact matching against the profile integration identifier. | [optional] |
| **page_size** | **Integer** | The number of items in the response. | [optional][default to 1000] |
| **skip** | **Integer** | The number of items to skip when paging through large result sets. | [optional] |
| **with_total_result_size** | **Boolean** | When this flag is set, the result includes the total size of the result, across all pages. This might decrease performance on large data sets.  - When &#x60;true&#x60;: &#x60;hasMore&#x60; is true when there is a next page. &#x60;totalResultSize&#x60; is always zero. - When &#x60;false&#x60;: &#x60;hasMore&#x60; is always false. &#x60;totalResultSize&#x60; contains the total number of results for this query.  | [optional] |

### Return type

[**GetApplicationCustomers200Response**](GetApplicationCustomers200Response.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_application_customers_by_attributes

> <GetApplicationCustomersByAttributes200Response> get_application_customers_by_attributes(application_id, customer_profile_search_query, opts)

List application customers matching the given attributes

Get a list of the application customers matching the provided criteria.  The match is successful if all the attributes of the request are found in a profile, even if the profile has more attributes that are not present on the request. 

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
application_id = 789 # Integer | The ID of the Application. It is displayed in your Talon.One deployment URL.
customer_profile_search_query = TalonOne::CustomerProfileSearchQuery.new # CustomerProfileSearchQuery | body
opts = {
  page_size: 789, # Integer | The number of items in the response.
  skip: 789, # Integer | The number of items to skip when paging through large result sets.
  with_total_result_size: true # Boolean | When this flag is set, the result includes the total size of the result, across all pages. This might decrease performance on large data sets.  - When `true`: `hasMore` is true when there is a next page. `totalResultSize` is always zero. - When `false`: `hasMore` is always false. `totalResultSize` contains the total number of results for this query. 
}

begin
  # List application customers matching the given attributes
  result = api_instance.get_application_customers_by_attributes(application_id, customer_profile_search_query, opts)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_application_customers_by_attributes: #{e}"
end
```

#### Using the get_application_customers_by_attributes_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<GetApplicationCustomersByAttributes200Response>, Integer, Hash)> get_application_customers_by_attributes_with_http_info(application_id, customer_profile_search_query, opts)

```ruby
begin
  # List application customers matching the given attributes
  data, status_code, headers = api_instance.get_application_customers_by_attributes_with_http_info(application_id, customer_profile_search_query, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <GetApplicationCustomersByAttributes200Response>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_application_customers_by_attributes_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **application_id** | **Integer** | The ID of the Application. It is displayed in your Talon.One deployment URL. |  |
| **customer_profile_search_query** | [**CustomerProfileSearchQuery**](CustomerProfileSearchQuery.md) | body |  |
| **page_size** | **Integer** | The number of items in the response. | [optional][default to 1000] |
| **skip** | **Integer** | The number of items to skip when paging through large result sets. | [optional] |
| **with_total_result_size** | **Boolean** | When this flag is set, the result includes the total size of the result, across all pages. This might decrease performance on large data sets.  - When &#x60;true&#x60;: &#x60;hasMore&#x60; is true when there is a next page. &#x60;totalResultSize&#x60; is always zero. - When &#x60;false&#x60;: &#x60;hasMore&#x60; is always false. &#x60;totalResultSize&#x60; contains the total number of results for this query.  | [optional] |

### Return type

[**GetApplicationCustomersByAttributes200Response**](GetApplicationCustomersByAttributes200Response.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## get_application_event_types

> <GetApplicationEventTypes200Response> get_application_event_types(application_id, opts)

List Applications event types

Get all of the distinct values of the Event `type` property for events recorded in the application.  See also: [Track an event](https://docs.talon.one/integration-api#tag/Events/operation/trackEventV2) 

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
application_id = 789 # Integer | The ID of the Application. It is displayed in your Talon.One deployment URL.
opts = {
  page_size: 789, # Integer | The number of items in the response.
  skip: 789, # Integer | The number of items to skip when paging through large result sets.
  sort: 'sort_example' # String | The field by which results should be sorted. By default, results are sorted in ascending order. To sort them in descending order, prefix the field name with `-`.  **Note:** You may not be able to use all fields for sorting. This is due to performance limitations. 
}

begin
  # List Applications event types
  result = api_instance.get_application_event_types(application_id, opts)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_application_event_types: #{e}"
end
```

#### Using the get_application_event_types_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<GetApplicationEventTypes200Response>, Integer, Hash)> get_application_event_types_with_http_info(application_id, opts)

```ruby
begin
  # List Applications event types
  data, status_code, headers = api_instance.get_application_event_types_with_http_info(application_id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <GetApplicationEventTypes200Response>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_application_event_types_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **application_id** | **Integer** | The ID of the Application. It is displayed in your Talon.One deployment URL. |  |
| **page_size** | **Integer** | The number of items in the response. | [optional][default to 1000] |
| **skip** | **Integer** | The number of items to skip when paging through large result sets. | [optional] |
| **sort** | **String** | The field by which results should be sorted. By default, results are sorted in ascending order. To sort them in descending order, prefix the field name with &#x60;-&#x60;.  **Note:** You may not be able to use all fields for sorting. This is due to performance limitations.  | [optional] |

### Return type

[**GetApplicationEventTypes200Response**](GetApplicationEventTypes200Response.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_application_events_without_total_count

> <GetApplicationEventsWithoutTotalCount200Response> get_application_events_without_total_count(application_id, opts)

List Applications events

Lists all events recorded for an application. Instead of having the total number of results in the response, this endpoint only mentions whether there are more results. 

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
application_id = 789 # Integer | The ID of the Application. It is displayed in your Talon.One deployment URL.
opts = {
  page_size: 789, # Integer | The number of items in the response.
  skip: 789, # Integer | The number of items to skip when paging through large result sets.
  sort: 'sort_example', # String | The field by which results should be sorted. By default, results are sorted in ascending order. To sort them in descending order, prefix the field name with `-`.  **Note:** You may not be able to use all fields for sorting. This is due to performance limitations. 
  type: 'type_example', # String | Comma-separated list of types by which to filter events. Must be exact match(es).
  created_before: Time.parse('2013-10-20T19:20:30+01:00'), # Time | Only return events created before this date. You can use any time zone setting. Talon.One will convert to UTC internally.
  created_after: Time.parse('2013-10-20T19:20:30+01:00'), # Time | Only return events created after this date. You can use any time zone setting. Talon.One will convert to UTC internally.
  session: 'session_example', # String | Session integration ID filter for events. Must be exact match.
  profile: 'profile_example', # String | Profile integration ID filter for events. Must be exact match.
  customer_name: 'customer_name_example', # String | Customer name filter for events. Will match substrings case-insensitively.
  customer_email: 'customer_email_example', # String | Customer e-mail address filter for events. Will match substrings case-insensitively.
  coupon_code: 'coupon_code_example', # String | Coupon code
  referral_code: 'referral_code_example', # String | Referral code
  rule_query: 'rule_query_example', # String | Rule name filter for events
  campaign_query: 'campaign_query_example', # String | Campaign name filter for events
  effect_type: 'effect_type_example' # String | The type of effect that was triggered. See [API effects](https://docs.talon.one/docs/dev/integration-api/api-effects).
}

begin
  # List Applications events
  result = api_instance.get_application_events_without_total_count(application_id, opts)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_application_events_without_total_count: #{e}"
end
```

#### Using the get_application_events_without_total_count_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<GetApplicationEventsWithoutTotalCount200Response>, Integer, Hash)> get_application_events_without_total_count_with_http_info(application_id, opts)

```ruby
begin
  # List Applications events
  data, status_code, headers = api_instance.get_application_events_without_total_count_with_http_info(application_id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <GetApplicationEventsWithoutTotalCount200Response>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_application_events_without_total_count_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **application_id** | **Integer** | The ID of the Application. It is displayed in your Talon.One deployment URL. |  |
| **page_size** | **Integer** | The number of items in the response. | [optional][default to 1000] |
| **skip** | **Integer** | The number of items to skip when paging through large result sets. | [optional] |
| **sort** | **String** | The field by which results should be sorted. By default, results are sorted in ascending order. To sort them in descending order, prefix the field name with &#x60;-&#x60;.  **Note:** You may not be able to use all fields for sorting. This is due to performance limitations.  | [optional] |
| **type** | **String** | Comma-separated list of types by which to filter events. Must be exact match(es). | [optional] |
| **created_before** | **Time** | Only return events created before this date. You can use any time zone setting. Talon.One will convert to UTC internally. | [optional] |
| **created_after** | **Time** | Only return events created after this date. You can use any time zone setting. Talon.One will convert to UTC internally. | [optional] |
| **session** | **String** | Session integration ID filter for events. Must be exact match. | [optional] |
| **profile** | **String** | Profile integration ID filter for events. Must be exact match. | [optional] |
| **customer_name** | **String** | Customer name filter for events. Will match substrings case-insensitively. | [optional] |
| **customer_email** | **String** | Customer e-mail address filter for events. Will match substrings case-insensitively. | [optional] |
| **coupon_code** | **String** | Coupon code | [optional] |
| **referral_code** | **String** | Referral code | [optional] |
| **rule_query** | **String** | Rule name filter for events | [optional] |
| **campaign_query** | **String** | Campaign name filter for events | [optional] |
| **effect_type** | **String** | The type of effect that was triggered. See [API effects](https://docs.talon.one/docs/dev/integration-api/api-effects). | [optional] |

### Return type

[**GetApplicationEventsWithoutTotalCount200Response**](GetApplicationEventsWithoutTotalCount200Response.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_application_session

> <ApplicationSession> get_application_session(application_id, session_id)

Get Application session

Get the details of the given session. You can list the sessions with the [List Application sessions](https://docs.talon.one/management-api#tag/Customer-data/operation/getApplicationSessions) endpoint. 

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
application_id = 789 # Integer | The ID of the Application. It is displayed in your Talon.One deployment URL.
session_id = 789 # Integer | The **internal** ID of the session. You can get the ID with the [List Application sessions](https://docs.talon.one/management-api#tag/Customer-data/operation/getApplicationSessions) endpoint. 

begin
  # Get Application session
  result = api_instance.get_application_session(application_id, session_id)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_application_session: #{e}"
end
```

#### Using the get_application_session_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<ApplicationSession>, Integer, Hash)> get_application_session_with_http_info(application_id, session_id)

```ruby
begin
  # Get Application session
  data, status_code, headers = api_instance.get_application_session_with_http_info(application_id, session_id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <ApplicationSession>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_application_session_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **application_id** | **Integer** | The ID of the Application. It is displayed in your Talon.One deployment URL. |  |
| **session_id** | **Integer** | The **internal** ID of the session. You can get the ID with the [List Application sessions](https://docs.talon.one/management-api#tag/Customer-data/operation/getApplicationSessions) endpoint.  |  |

### Return type

[**ApplicationSession**](ApplicationSession.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_application_sessions

> <GetApplicationSessions200Response> get_application_sessions(application_id, opts)

List Application sessions

List all the sessions of the specified Application. 

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
application_id = 789 # Integer | The ID of the Application. It is displayed in your Talon.One deployment URL.
opts = {
  page_size: 789, # Integer | The number of items in the response.
  skip: 789, # Integer | The number of items to skip when paging through large result sets.
  sort: 'sort_example', # String | The field by which results should be sorted. By default, results are sorted in ascending order. To sort them in descending order, prefix the field name with `-`.  **Note:** You may not be able to use all fields for sorting. This is due to performance limitations. 
  profile: 'profile_example', # String | Profile integration ID filter for sessions. Must be exact match.
  state: 'open', # String | Filter by sessions with this state. Must be exact match.
  created_before: Time.parse('2013-10-20T19:20:30+01:00'), # Time | Only return events created before this date. You can use any time zone setting. Talon.One will convert to UTC internally.
  created_after: Time.parse('2013-10-20T19:20:30+01:00'), # Time | Only return events created after this date. You can use any time zone setting. Talon.One will convert to UTC internally.
  coupon: 'coupon_example', # String | Filter by sessions with this coupon. Must be exact match.
  referral: 'referral_example', # String | Filter by sessions with this referral. Must be exact match.
  integration_id: 'integration_id_example', # String | Filter by sessions with this integration ID. Must be exact match.
  store_integration_id: 'store_integration_id_example' # String | The integration ID of the store. You choose this ID when you create a store.
}

begin
  # List Application sessions
  result = api_instance.get_application_sessions(application_id, opts)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_application_sessions: #{e}"
end
```

#### Using the get_application_sessions_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<GetApplicationSessions200Response>, Integer, Hash)> get_application_sessions_with_http_info(application_id, opts)

```ruby
begin
  # List Application sessions
  data, status_code, headers = api_instance.get_application_sessions_with_http_info(application_id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <GetApplicationSessions200Response>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_application_sessions_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **application_id** | **Integer** | The ID of the Application. It is displayed in your Talon.One deployment URL. |  |
| **page_size** | **Integer** | The number of items in the response. | [optional][default to 1000] |
| **skip** | **Integer** | The number of items to skip when paging through large result sets. | [optional] |
| **sort** | **String** | The field by which results should be sorted. By default, results are sorted in ascending order. To sort them in descending order, prefix the field name with &#x60;-&#x60;.  **Note:** You may not be able to use all fields for sorting. This is due to performance limitations.  | [optional] |
| **profile** | **String** | Profile integration ID filter for sessions. Must be exact match. | [optional] |
| **state** | **String** | Filter by sessions with this state. Must be exact match. | [optional] |
| **created_before** | **Time** | Only return events created before this date. You can use any time zone setting. Talon.One will convert to UTC internally. | [optional] |
| **created_after** | **Time** | Only return events created after this date. You can use any time zone setting. Talon.One will convert to UTC internally. | [optional] |
| **coupon** | **String** | Filter by sessions with this coupon. Must be exact match. | [optional] |
| **referral** | **String** | Filter by sessions with this referral. Must be exact match. | [optional] |
| **integration_id** | **String** | Filter by sessions with this integration ID. Must be exact match. | [optional] |
| **store_integration_id** | **String** | The integration ID of the store. You choose this ID when you create a store. | [optional] |

### Return type

[**GetApplicationSessions200Response**](GetApplicationSessions200Response.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_applications

> <GetApplications200Response> get_applications(opts)

List Applications

List all applications in the current account.

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
opts = {
  page_size: 789, # Integer | The number of items in the response.
  skip: 789, # Integer | The number of items to skip when paging through large result sets.
  sort: 'sort_example' # String | The field by which results should be sorted. By default, results are sorted in ascending order. To sort them in descending order, prefix the field name with `-`.  **Note:** You may not be able to use all fields for sorting. This is due to performance limitations. 
}

begin
  # List Applications
  result = api_instance.get_applications(opts)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_applications: #{e}"
end
```

#### Using the get_applications_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<GetApplications200Response>, Integer, Hash)> get_applications_with_http_info(opts)

```ruby
begin
  # List Applications
  data, status_code, headers = api_instance.get_applications_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <GetApplications200Response>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_applications_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **page_size** | **Integer** | The number of items in the response. | [optional][default to 1000] |
| **skip** | **Integer** | The number of items to skip when paging through large result sets. | [optional] |
| **sort** | **String** | The field by which results should be sorted. By default, results are sorted in ascending order. To sort them in descending order, prefix the field name with &#x60;-&#x60;.  **Note:** You may not be able to use all fields for sorting. This is due to performance limitations.  | [optional] |

### Return type

[**GetApplications200Response**](GetApplications200Response.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_attribute

> <Attribute> get_attribute(attribute_id)

Get custom attribute

Retrieve the specified custom attribute. 

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
attribute_id = 789 # Integer | The ID of the attribute. You can find the ID in the Campaign Manager's URL when you display the details of an attribute in **Account** > **Tools** > **Attributes**.

begin
  # Get custom attribute
  result = api_instance.get_attribute(attribute_id)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_attribute: #{e}"
end
```

#### Using the get_attribute_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<Attribute>, Integer, Hash)> get_attribute_with_http_info(attribute_id)

```ruby
begin
  # Get custom attribute
  data, status_code, headers = api_instance.get_attribute_with_http_info(attribute_id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <Attribute>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_attribute_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **attribute_id** | **Integer** | The ID of the attribute. You can find the ID in the Campaign Manager&#39;s URL when you display the details of an attribute in **Account** &gt; **Tools** &gt; **Attributes**. |  |

### Return type

[**Attribute**](Attribute.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_attributes

> <GetAttributes200Response> get_attributes(opts)

List custom attributes

Return all the custom attributes for the account. 

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
opts = {
  page_size: 789, # Integer | The number of items in the response.
  skip: 789, # Integer | The number of items to skip when paging through large result sets.
  sort: 'sort_example', # String | The field by which results should be sorted. By default, results are sorted in ascending order. To sort them in descending order, prefix the field name with `-`.  **Note:** You may not be able to use all fields for sorting. This is due to performance limitations. 
  entity: 'entity_example', # String | Returned attributes will be filtered by supplied entity.
  application_ids: 'application_ids_example', # String | Returned attributes will be filtered by supplied application ids
  type: 'type_example', # String | Returned attributes will be filtered by supplied type
  kind: 'builtin', # String | Returned attributes will be filtered by supplied kind (builtin or custom)
  search: 'search_example' # String | Returned attributes will be filtered by searching case insensitive through Attribute name, description and type
}

begin
  # List custom attributes
  result = api_instance.get_attributes(opts)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_attributes: #{e}"
end
```

#### Using the get_attributes_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<GetAttributes200Response>, Integer, Hash)> get_attributes_with_http_info(opts)

```ruby
begin
  # List custom attributes
  data, status_code, headers = api_instance.get_attributes_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <GetAttributes200Response>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_attributes_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **page_size** | **Integer** | The number of items in the response. | [optional][default to 1000] |
| **skip** | **Integer** | The number of items to skip when paging through large result sets. | [optional] |
| **sort** | **String** | The field by which results should be sorted. By default, results are sorted in ascending order. To sort them in descending order, prefix the field name with &#x60;-&#x60;.  **Note:** You may not be able to use all fields for sorting. This is due to performance limitations.  | [optional] |
| **entity** | **String** | Returned attributes will be filtered by supplied entity. | [optional] |
| **application_ids** | **String** | Returned attributes will be filtered by supplied application ids | [optional] |
| **type** | **String** | Returned attributes will be filtered by supplied type | [optional] |
| **kind** | **String** | Returned attributes will be filtered by supplied kind (builtin or custom) | [optional] |
| **search** | **String** | Returned attributes will be filtered by searching case insensitive through Attribute name, description and type | [optional] |

### Return type

[**GetAttributes200Response**](GetAttributes200Response.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_audience_memberships

> <GetAudienceMemberships200Response> get_audience_memberships(audience_id, opts)

List audience members

Get a paginated list of the customer profiles in a given audience.  A maximum of 1000 customer profiles per page is allowed. 

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
audience_id = 789 # Integer | The ID of the audience.
opts = {
  page_size: 789, # Integer | The number of items in the response.
  skip: 789, # Integer | The number of items to skip when paging through large result sets.
  sort: 'sort_example', # String | The field by which results should be sorted. By default, results are sorted in ascending order. To sort them in descending order, prefix the field name with `-`.  **Note:** You may not be able to use all fields for sorting. This is due to performance limitations. 
  profile_query: 'profile_query_example' # String | The filter to select a profile.
}

begin
  # List audience members
  result = api_instance.get_audience_memberships(audience_id, opts)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_audience_memberships: #{e}"
end
```

#### Using the get_audience_memberships_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<GetAudienceMemberships200Response>, Integer, Hash)> get_audience_memberships_with_http_info(audience_id, opts)

```ruby
begin
  # List audience members
  data, status_code, headers = api_instance.get_audience_memberships_with_http_info(audience_id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <GetAudienceMemberships200Response>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_audience_memberships_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **audience_id** | **Integer** | The ID of the audience. |  |
| **page_size** | **Integer** | The number of items in the response. | [optional][default to 1000] |
| **skip** | **Integer** | The number of items to skip when paging through large result sets. | [optional] |
| **sort** | **String** | The field by which results should be sorted. By default, results are sorted in ascending order. To sort them in descending order, prefix the field name with &#x60;-&#x60;.  **Note:** You may not be able to use all fields for sorting. This is due to performance limitations.  | [optional] |
| **profile_query** | **String** | The filter to select a profile. | [optional] |

### Return type

[**GetAudienceMemberships200Response**](GetAudienceMemberships200Response.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_audiences

> <GetAudiences200Response> get_audiences(opts)

List audiences

Get all audiences created in the account. To create an audience, use [Create audience](https://docs.talon.one/integration-api#tag/Audiences/operation/createAudienceV2). 

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
opts = {
  page_size: 789, # Integer | The number of items in the response.
  skip: 789, # Integer | The number of items to skip when paging through large result sets.
  sort: 'sort_example', # String | The field by which results should be sorted. By default, results are sorted in ascending order. To sort them in descending order, prefix the field name with `-`.  **Note:** You may not be able to use all fields for sorting. This is due to performance limitations. 
  with_total_result_size: true # Boolean | When this flag is set, the result includes the total size of the result, across all pages. This might decrease performance on large data sets.  - When `true`: `hasMore` is true when there is a next page. `totalResultSize` is always zero. - When `false`: `hasMore` is always false. `totalResultSize` contains the total number of results for this query. 
}

begin
  # List audiences
  result = api_instance.get_audiences(opts)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_audiences: #{e}"
end
```

#### Using the get_audiences_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<GetAudiences200Response>, Integer, Hash)> get_audiences_with_http_info(opts)

```ruby
begin
  # List audiences
  data, status_code, headers = api_instance.get_audiences_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <GetAudiences200Response>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_audiences_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **page_size** | **Integer** | The number of items in the response. | [optional][default to 1000] |
| **skip** | **Integer** | The number of items to skip when paging through large result sets. | [optional] |
| **sort** | **String** | The field by which results should be sorted. By default, results are sorted in ascending order. To sort them in descending order, prefix the field name with &#x60;-&#x60;.  **Note:** You may not be able to use all fields for sorting. This is due to performance limitations.  | [optional] |
| **with_total_result_size** | **Boolean** | When this flag is set, the result includes the total size of the result, across all pages. This might decrease performance on large data sets.  - When &#x60;true&#x60;: &#x60;hasMore&#x60; is true when there is a next page. &#x60;totalResultSize&#x60; is always zero. - When &#x60;false&#x60;: &#x60;hasMore&#x60; is always false. &#x60;totalResultSize&#x60; contains the total number of results for this query.  | [optional] |

### Return type

[**GetAudiences200Response**](GetAudiences200Response.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_audiences_analytics

> <GetAudiencesAnalytics200Response> get_audiences_analytics(audience_ids, opts)

List audience analytics

Get a list of audience IDs and their member count. 

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
audience_ids = 'audience_ids_example' # String | The IDs of one or more audiences, separated by commas, by which to filter results.
opts = {
  sort: 'sort_example' # String | The field by which results should be sorted. By default, results are sorted in ascending order. To sort them in descending order, prefix the field name with `-`.  **Note:** You may not be able to use all fields for sorting. This is due to performance limitations. 
}

begin
  # List audience analytics
  result = api_instance.get_audiences_analytics(audience_ids, opts)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_audiences_analytics: #{e}"
end
```

#### Using the get_audiences_analytics_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<GetAudiencesAnalytics200Response>, Integer, Hash)> get_audiences_analytics_with_http_info(audience_ids, opts)

```ruby
begin
  # List audience analytics
  data, status_code, headers = api_instance.get_audiences_analytics_with_http_info(audience_ids, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <GetAudiencesAnalytics200Response>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_audiences_analytics_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **audience_ids** | **String** | The IDs of one or more audiences, separated by commas, by which to filter results. |  |
| **sort** | **String** | The field by which results should be sorted. By default, results are sorted in ascending order. To sort them in descending order, prefix the field name with &#x60;-&#x60;.  **Note:** You may not be able to use all fields for sorting. This is due to performance limitations.  | [optional] |

### Return type

[**GetAudiencesAnalytics200Response**](GetAudiencesAnalytics200Response.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_campaign

> <Campaign> get_campaign(application_id, campaign_id)

Get campaign

Retrieve the given campaign.

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
application_id = 789 # Integer | The ID of the Application. It is displayed in your Talon.One deployment URL.
campaign_id = 789 # Integer | The ID of the campaign. It is displayed in your Talon.One deployment URL.

begin
  # Get campaign
  result = api_instance.get_campaign(application_id, campaign_id)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_campaign: #{e}"
end
```

#### Using the get_campaign_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<Campaign>, Integer, Hash)> get_campaign_with_http_info(application_id, campaign_id)

```ruby
begin
  # Get campaign
  data, status_code, headers = api_instance.get_campaign_with_http_info(application_id, campaign_id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <Campaign>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_campaign_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **application_id** | **Integer** | The ID of the Application. It is displayed in your Talon.One deployment URL. |  |
| **campaign_id** | **Integer** | The ID of the campaign. It is displayed in your Talon.One deployment URL. |  |

### Return type

[**Campaign**](Campaign.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_campaign_analytics

> <GetCampaignAnalytics200Response> get_campaign_analytics(application_id, campaign_id, range_start, range_end, opts)

Get analytics of campaigns

Retrieve statistical data about the performance of the given campaign.

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
application_id = 789 # Integer | The ID of the Application. It is displayed in your Talon.One deployment URL.
campaign_id = 789 # Integer | The ID of the campaign. It is displayed in your Talon.One deployment URL.
range_start = Time.parse('2013-10-20T19:20:30+01:00') # Time | Only return results from after this timestamp.  **Note:** - This must be an RFC3339 timestamp string. - You can include a time component in your string, for example, `T23:59:59` to specify the end of the day. The time zone setting considered is `UTC`. If you do not include a time component, a default time value of `T00:00:00` (midnight) in `UTC` is considered. 
range_end = Time.parse('2013-10-20T19:20:30+01:00') # Time | Only return results from before this timestamp.  **Note:** - This must be an RFC3339 timestamp string. - You can include a time component in your string, for example, `T23:59:59` to specify the end of the day. The time zone setting considered is `UTC`. If you do not include a time component, a default time value of `T00:00:00` (midnight) in `UTC` is considered. 
opts = {
  granularity: '1 hour' # String | The time interval between the results in the returned time-series.
}

begin
  # Get analytics of campaigns
  result = api_instance.get_campaign_analytics(application_id, campaign_id, range_start, range_end, opts)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_campaign_analytics: #{e}"
end
```

#### Using the get_campaign_analytics_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<GetCampaignAnalytics200Response>, Integer, Hash)> get_campaign_analytics_with_http_info(application_id, campaign_id, range_start, range_end, opts)

```ruby
begin
  # Get analytics of campaigns
  data, status_code, headers = api_instance.get_campaign_analytics_with_http_info(application_id, campaign_id, range_start, range_end, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <GetCampaignAnalytics200Response>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_campaign_analytics_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **application_id** | **Integer** | The ID of the Application. It is displayed in your Talon.One deployment URL. |  |
| **campaign_id** | **Integer** | The ID of the campaign. It is displayed in your Talon.One deployment URL. |  |
| **range_start** | **Time** | Only return results from after this timestamp.  **Note:** - This must be an RFC3339 timestamp string. - You can include a time component in your string, for example, &#x60;T23:59:59&#x60; to specify the end of the day. The time zone setting considered is &#x60;UTC&#x60;. If you do not include a time component, a default time value of &#x60;T00:00:00&#x60; (midnight) in &#x60;UTC&#x60; is considered.  |  |
| **range_end** | **Time** | Only return results from before this timestamp.  **Note:** - This must be an RFC3339 timestamp string. - You can include a time component in your string, for example, &#x60;T23:59:59&#x60; to specify the end of the day. The time zone setting considered is &#x60;UTC&#x60;. If you do not include a time component, a default time value of &#x60;T00:00:00&#x60; (midnight) in &#x60;UTC&#x60; is considered.  |  |
| **granularity** | **String** | The time interval between the results in the returned time-series. | [optional] |

### Return type

[**GetCampaignAnalytics200Response**](GetCampaignAnalytics200Response.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_campaign_by_attributes

> <GetCampaigns200Response> get_campaign_by_attributes(application_id, campaign_search, opts)

List campaigns that match the given attributes

Get a list of all the campaigns that match a set of attributes. 

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
application_id = 789 # Integer | The ID of the Application. It is displayed in your Talon.One deployment URL.
campaign_search = TalonOne::CampaignSearch.new({attributes: 3.56}) # CampaignSearch | body
opts = {
  page_size: 789, # Integer | The number of items in the response.
  skip: 789, # Integer | The number of items to skip when paging through large result sets.
  sort: 'sort_example', # String | The field by which results should be sorted. By default, results are sorted in ascending order. To sort them in descending order, prefix the field name with `-`.  **Note:** You may not be able to use all fields for sorting. This is due to performance limitations. 
  campaign_state: 'enabled' # String | Filter results by the state of the campaign.  - `enabled`: Campaigns that are scheduled, running (activated), or expired. - `running`: Campaigns that are running (activated). - `disabled`: Campaigns that are disabled. - `expired`: Campaigns that are expired. - `archived`: Campaigns that are archived. 
}

begin
  # List campaigns that match the given attributes
  result = api_instance.get_campaign_by_attributes(application_id, campaign_search, opts)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_campaign_by_attributes: #{e}"
end
```

#### Using the get_campaign_by_attributes_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<GetCampaigns200Response>, Integer, Hash)> get_campaign_by_attributes_with_http_info(application_id, campaign_search, opts)

```ruby
begin
  # List campaigns that match the given attributes
  data, status_code, headers = api_instance.get_campaign_by_attributes_with_http_info(application_id, campaign_search, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <GetCampaigns200Response>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_campaign_by_attributes_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **application_id** | **Integer** | The ID of the Application. It is displayed in your Talon.One deployment URL. |  |
| **campaign_search** | [**CampaignSearch**](CampaignSearch.md) | body |  |
| **page_size** | **Integer** | The number of items in the response. | [optional][default to 1000] |
| **skip** | **Integer** | The number of items to skip when paging through large result sets. | [optional] |
| **sort** | **String** | The field by which results should be sorted. By default, results are sorted in ascending order. To sort them in descending order, prefix the field name with &#x60;-&#x60;.  **Note:** You may not be able to use all fields for sorting. This is due to performance limitations.  | [optional] |
| **campaign_state** | **String** | Filter results by the state of the campaign.  - &#x60;enabled&#x60;: Campaigns that are scheduled, running (activated), or expired. - &#x60;running&#x60;: Campaigns that are running (activated). - &#x60;disabled&#x60;: Campaigns that are disabled. - &#x60;expired&#x60;: Campaigns that are expired. - &#x60;archived&#x60;: Campaigns that are archived.  | [optional] |

### Return type

[**GetCampaigns200Response**](GetCampaigns200Response.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## get_campaign_group

> <CampaignGroup> get_campaign_group(campaign_group_id)

Get campaign access group

Get a campaign access group specified by its ID.

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
campaign_group_id = 789 # Integer | The ID of the campaign access group.

begin
  # Get campaign access group
  result = api_instance.get_campaign_group(campaign_group_id)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_campaign_group: #{e}"
end
```

#### Using the get_campaign_group_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<CampaignGroup>, Integer, Hash)> get_campaign_group_with_http_info(campaign_group_id)

```ruby
begin
  # Get campaign access group
  data, status_code, headers = api_instance.get_campaign_group_with_http_info(campaign_group_id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <CampaignGroup>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_campaign_group_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **campaign_group_id** | **Integer** | The ID of the campaign access group. |  |

### Return type

[**CampaignGroup**](CampaignGroup.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_campaign_groups

> <GetCampaignGroups200Response> get_campaign_groups(opts)

List campaign access groups

List the campaign access groups in the current account.

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
opts = {
  page_size: 789, # Integer | The number of items in the response.
  skip: 789, # Integer | The number of items to skip when paging through large result sets.
  sort: 'sort_example' # String | The field by which results should be sorted. By default, results are sorted in ascending order. To sort them in descending order, prefix the field name with `-`.  **Note:** You may not be able to use all fields for sorting. This is due to performance limitations. 
}

begin
  # List campaign access groups
  result = api_instance.get_campaign_groups(opts)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_campaign_groups: #{e}"
end
```

#### Using the get_campaign_groups_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<GetCampaignGroups200Response>, Integer, Hash)> get_campaign_groups_with_http_info(opts)

```ruby
begin
  # List campaign access groups
  data, status_code, headers = api_instance.get_campaign_groups_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <GetCampaignGroups200Response>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_campaign_groups_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **page_size** | **Integer** | The number of items in the response. | [optional][default to 1000] |
| **skip** | **Integer** | The number of items to skip when paging through large result sets. | [optional] |
| **sort** | **String** | The field by which results should be sorted. By default, results are sorted in ascending order. To sort them in descending order, prefix the field name with &#x60;-&#x60;.  **Note:** You may not be able to use all fields for sorting. This is due to performance limitations.  | [optional] |

### Return type

[**GetCampaignGroups200Response**](GetCampaignGroups200Response.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_campaign_templates

> <GetCampaignTemplates200Response> get_campaign_templates(opts)

List campaign templates

Retrieve a list of campaign templates.

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
opts = {
  page_size: 789, # Integer | The number of items in the response.
  skip: 789, # Integer | The number of items to skip when paging through large result sets.
  sort: 'sort_example', # String | The field by which results should be sorted. By default, results are sorted in ascending order. To sort them in descending order, prefix the field name with `-`.  **Note:** You may not be able to use all fields for sorting. This is due to performance limitations. 
  state: 'draft', # String | Filter results by the state of the campaign template.
  name: 'name_example', # String | Filter results performing case-insensitive matching against the name of the campaign template.
  tags: 'tags_example', # String | Filter results performing case-insensitive matching against the tags of the campaign template. When used in conjunction with the \"name\" query parameter, a logical OR will be performed to search both tags and name for the provided values. 
  user_id: 789 # Integer | Filter results by user ID.
}

begin
  # List campaign templates
  result = api_instance.get_campaign_templates(opts)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_campaign_templates: #{e}"
end
```

#### Using the get_campaign_templates_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<GetCampaignTemplates200Response>, Integer, Hash)> get_campaign_templates_with_http_info(opts)

```ruby
begin
  # List campaign templates
  data, status_code, headers = api_instance.get_campaign_templates_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <GetCampaignTemplates200Response>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_campaign_templates_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **page_size** | **Integer** | The number of items in the response. | [optional][default to 1000] |
| **skip** | **Integer** | The number of items to skip when paging through large result sets. | [optional] |
| **sort** | **String** | The field by which results should be sorted. By default, results are sorted in ascending order. To sort them in descending order, prefix the field name with &#x60;-&#x60;.  **Note:** You may not be able to use all fields for sorting. This is due to performance limitations.  | [optional] |
| **state** | **String** | Filter results by the state of the campaign template. | [optional] |
| **name** | **String** | Filter results performing case-insensitive matching against the name of the campaign template. | [optional] |
| **tags** | **String** | Filter results performing case-insensitive matching against the tags of the campaign template. When used in conjunction with the \&quot;name\&quot; query parameter, a logical OR will be performed to search both tags and name for the provided values.  | [optional] |
| **user_id** | **Integer** | Filter results by user ID. | [optional] |

### Return type

[**GetCampaignTemplates200Response**](GetCampaignTemplates200Response.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_campaigns

> <GetCampaigns200Response> get_campaigns(application_id, opts)

List campaigns

List the campaigns of the specified application that match your filter criteria. 

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
application_id = 789 # Integer | The ID of the Application. It is displayed in your Talon.One deployment URL.
opts = {
  page_size: 789, # Integer | The number of items in the response.
  skip: 789, # Integer | The number of items to skip when paging through large result sets.
  sort: 'sort_example', # String | The field by which results should be sorted. By default, results are sorted in ascending order. To sort them in descending order, prefix the field name with `-`.  **Note:** You may not be able to use all fields for sorting. This is due to performance limitations. 
  campaign_state: 'enabled', # String | Filter results by the state of the campaign.  - `enabled`: Campaigns that are scheduled, running (activated), or expired. - `running`: Campaigns that are running (activated). - `disabled`: Campaigns that are disabled. - `expired`: Campaigns that are expired. - `archived`: Campaigns that are archived. 
  name: 'name_example', # String | Filter results performing case-insensitive matching against the name of the campaign.
  tags: 'tags_example', # String | Filter results performing case-insensitive matching against the tags of the campaign. When used in conjunction with the \"name\" query parameter, a logical OR will be performed to search both tags and name for the provided values 
  created_before: Time.parse('2013-10-20T19:20:30+01:00'), # Time | Filter results comparing the parameter value, expected to be an RFC3339 timestamp string, to the campaign creation timestamp. You can use any time zone setting. Talon.One will convert to UTC internally.
  created_after: Time.parse('2013-10-20T19:20:30+01:00'), # Time | Filter results comparing the parameter value, expected to be an RFC3339 timestamp string, to the campaign creation timestamp. You can use any time zone setting. Talon.One will convert to UTC internally.
  start_before: Time.parse('2013-10-20T19:20:30+01:00'), # Time | Filter results comparing the parameter value, expected to be an RFC3339 timestamp string, to the campaign start time timestamp. You can use any time zone setting. Talon.One will convert to UTC internally.
  start_after: Time.parse('2013-10-20T19:20:30+01:00'), # Time | Filter results comparing the parameter value, expected to be an RFC3339 timestamp string, to the campaign start time timestamp. You can use any time zone setting. Talon.One will convert to UTC internally.
  end_before: Time.parse('2013-10-20T19:20:30+01:00'), # Time | Filter results comparing the parameter value, expected to be an RFC3339 timestamp string, to the campaign end time timestamp. You can use any time zone setting. Talon.One will convert to UTC internally.
  end_after: Time.parse('2013-10-20T19:20:30+01:00'), # Time | Filter results comparing the parameter value, expected to be an RFC3339 timestamp string, to the campaign end time timestamp. You can use any time zone setting. Talon.One will convert to UTC internally.
  campaign_group_id: 789, # Integer | Filter results to campaigns owned by the specified campaign access group ID.
  template_id: 789, # Integer | The ID of the campaign template this campaign was created from.
  store_id: 789 # Integer | Filter results to campaigns linked to the specified store ID.
}

begin
  # List campaigns
  result = api_instance.get_campaigns(application_id, opts)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_campaigns: #{e}"
end
```

#### Using the get_campaigns_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<GetCampaigns200Response>, Integer, Hash)> get_campaigns_with_http_info(application_id, opts)

```ruby
begin
  # List campaigns
  data, status_code, headers = api_instance.get_campaigns_with_http_info(application_id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <GetCampaigns200Response>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_campaigns_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **application_id** | **Integer** | The ID of the Application. It is displayed in your Talon.One deployment URL. |  |
| **page_size** | **Integer** | The number of items in the response. | [optional][default to 1000] |
| **skip** | **Integer** | The number of items to skip when paging through large result sets. | [optional] |
| **sort** | **String** | The field by which results should be sorted. By default, results are sorted in ascending order. To sort them in descending order, prefix the field name with &#x60;-&#x60;.  **Note:** You may not be able to use all fields for sorting. This is due to performance limitations.  | [optional] |
| **campaign_state** | **String** | Filter results by the state of the campaign.  - &#x60;enabled&#x60;: Campaigns that are scheduled, running (activated), or expired. - &#x60;running&#x60;: Campaigns that are running (activated). - &#x60;disabled&#x60;: Campaigns that are disabled. - &#x60;expired&#x60;: Campaigns that are expired. - &#x60;archived&#x60;: Campaigns that are archived.  | [optional] |
| **name** | **String** | Filter results performing case-insensitive matching against the name of the campaign. | [optional] |
| **tags** | **String** | Filter results performing case-insensitive matching against the tags of the campaign. When used in conjunction with the \&quot;name\&quot; query parameter, a logical OR will be performed to search both tags and name for the provided values  | [optional] |
| **created_before** | **Time** | Filter results comparing the parameter value, expected to be an RFC3339 timestamp string, to the campaign creation timestamp. You can use any time zone setting. Talon.One will convert to UTC internally. | [optional] |
| **created_after** | **Time** | Filter results comparing the parameter value, expected to be an RFC3339 timestamp string, to the campaign creation timestamp. You can use any time zone setting. Talon.One will convert to UTC internally. | [optional] |
| **start_before** | **Time** | Filter results comparing the parameter value, expected to be an RFC3339 timestamp string, to the campaign start time timestamp. You can use any time zone setting. Talon.One will convert to UTC internally. | [optional] |
| **start_after** | **Time** | Filter results comparing the parameter value, expected to be an RFC3339 timestamp string, to the campaign start time timestamp. You can use any time zone setting. Talon.One will convert to UTC internally. | [optional] |
| **end_before** | **Time** | Filter results comparing the parameter value, expected to be an RFC3339 timestamp string, to the campaign end time timestamp. You can use any time zone setting. Talon.One will convert to UTC internally. | [optional] |
| **end_after** | **Time** | Filter results comparing the parameter value, expected to be an RFC3339 timestamp string, to the campaign end time timestamp. You can use any time zone setting. Talon.One will convert to UTC internally. | [optional] |
| **campaign_group_id** | **Integer** | Filter results to campaigns owned by the specified campaign access group ID. | [optional] |
| **template_id** | **Integer** | The ID of the campaign template this campaign was created from. | [optional] |
| **store_id** | **Integer** | Filter results to campaigns linked to the specified store ID. | [optional] |

### Return type

[**GetCampaigns200Response**](GetCampaigns200Response.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_changes

> <GetChanges200Response> get_changes(opts)

Get audit logs for an account

Retrieve the audit logs displayed in **Accounts > Audit logs**. 

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
opts = {
  page_size: 789, # Integer | The number of items in the response.
  skip: 789, # Integer | The number of items to skip when paging through large result sets.
  sort: 'sort_example', # String | The field by which results should be sorted. By default, results are sorted in ascending order. To sort them in descending order, prefix the field name with `-`.  **Note:** You may not be able to use all fields for sorting. This is due to performance limitations. 
  application_id: 8.14, # Float | Filter results by Application ID.
  entity_path: 'entity_path_example', # String | Filter results on a case insensitive matching of the url path of the entity
  user_id: 789, # Integer | Filter results by user ID.
  created_before: Time.parse('2013-10-20T19:20:30+01:00'), # Time | Filter results comparing the parameter value, expected to be an RFC3339 timestamp string, to the change creation timestamp. You can use any time zone setting. Talon.One will convert to UTC internally.
  created_after: Time.parse('2013-10-20T19:20:30+01:00'), # Time | Filter results comparing the parameter value, expected to be an RFC3339 timestamp string, to the change creation timestamp. You can use any time zone setting. Talon.One will convert to UTC internally.
  with_total_result_size: true, # Boolean | When this flag is set, the result includes the total size of the result, across all pages. This might decrease performance on large data sets.  - When `true`: `hasMore` is true when there is a next page. `totalResultSize` is always zero. - When `false`: `hasMore` is always false. `totalResultSize` contains the total number of results for this query. 
  management_key_id: 789, # Integer | Filter results that match the given management key ID.
  include_old: true # Boolean | When this flag is set to false, the state without the change will not be returned. The default value is true.
}

begin
  # Get audit logs for an account
  result = api_instance.get_changes(opts)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_changes: #{e}"
end
```

#### Using the get_changes_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<GetChanges200Response>, Integer, Hash)> get_changes_with_http_info(opts)

```ruby
begin
  # Get audit logs for an account
  data, status_code, headers = api_instance.get_changes_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <GetChanges200Response>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_changes_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **page_size** | **Integer** | The number of items in the response. | [optional][default to 1000] |
| **skip** | **Integer** | The number of items to skip when paging through large result sets. | [optional] |
| **sort** | **String** | The field by which results should be sorted. By default, results are sorted in ascending order. To sort them in descending order, prefix the field name with &#x60;-&#x60;.  **Note:** You may not be able to use all fields for sorting. This is due to performance limitations.  | [optional] |
| **application_id** | **Float** | Filter results by Application ID. | [optional] |
| **entity_path** | **String** | Filter results on a case insensitive matching of the url path of the entity | [optional] |
| **user_id** | **Integer** | Filter results by user ID. | [optional] |
| **created_before** | **Time** | Filter results comparing the parameter value, expected to be an RFC3339 timestamp string, to the change creation timestamp. You can use any time zone setting. Talon.One will convert to UTC internally. | [optional] |
| **created_after** | **Time** | Filter results comparing the parameter value, expected to be an RFC3339 timestamp string, to the change creation timestamp. You can use any time zone setting. Talon.One will convert to UTC internally. | [optional] |
| **with_total_result_size** | **Boolean** | When this flag is set, the result includes the total size of the result, across all pages. This might decrease performance on large data sets.  - When &#x60;true&#x60;: &#x60;hasMore&#x60; is true when there is a next page. &#x60;totalResultSize&#x60; is always zero. - When &#x60;false&#x60;: &#x60;hasMore&#x60; is always false. &#x60;totalResultSize&#x60; contains the total number of results for this query.  | [optional] |
| **management_key_id** | **Integer** | Filter results that match the given management key ID. | [optional] |
| **include_old** | **Boolean** | When this flag is set to false, the state without the change will not be returned. The default value is true. | [optional] |

### Return type

[**GetChanges200Response**](GetChanges200Response.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_collection

> <Collection> get_collection(application_id, campaign_id, collection_id)

Get campaign-level collection

Retrieve a given campaign-level collection.

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
application_id = 789 # Integer | The ID of the Application. It is displayed in your Talon.One deployment URL.
campaign_id = 789 # Integer | The ID of the campaign. It is displayed in your Talon.One deployment URL.
collection_id = 789 # Integer | The ID of the collection. You can get it with the [List collections in Application](#operation/listCollectionsInApplication) endpoint.

begin
  # Get campaign-level collection
  result = api_instance.get_collection(application_id, campaign_id, collection_id)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_collection: #{e}"
end
```

#### Using the get_collection_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<Collection>, Integer, Hash)> get_collection_with_http_info(application_id, campaign_id, collection_id)

```ruby
begin
  # Get campaign-level collection
  data, status_code, headers = api_instance.get_collection_with_http_info(application_id, campaign_id, collection_id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <Collection>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_collection_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **application_id** | **Integer** | The ID of the Application. It is displayed in your Talon.One deployment URL. |  |
| **campaign_id** | **Integer** | The ID of the campaign. It is displayed in your Talon.One deployment URL. |  |
| **collection_id** | **Integer** | The ID of the collection. You can get it with the [List collections in Application](#operation/listCollectionsInApplication) endpoint. |  |

### Return type

[**Collection**](Collection.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_collection_items

> <GetCollectionItems200Response> get_collection_items(collection_id, opts)

Get collection items

Retrieve items from a given collection.  You can retrieve items from both account-level collections and campaign-level collections using this endpoint. 

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
collection_id = 789 # Integer | The ID of the collection. You can get it with the [List collections in account](#operation/listAccountCollections) endpoint.
opts = {
  page_size: 789, # Integer | The number of items in the response.
  skip: 789 # Integer | The number of items to skip when paging through large result sets.
}

begin
  # Get collection items
  result = api_instance.get_collection_items(collection_id, opts)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_collection_items: #{e}"
end
```

#### Using the get_collection_items_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<GetCollectionItems200Response>, Integer, Hash)> get_collection_items_with_http_info(collection_id, opts)

```ruby
begin
  # Get collection items
  data, status_code, headers = api_instance.get_collection_items_with_http_info(collection_id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <GetCollectionItems200Response>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_collection_items_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **collection_id** | **Integer** | The ID of the collection. You can get it with the [List collections in account](#operation/listAccountCollections) endpoint. |  |
| **page_size** | **Integer** | The number of items in the response. | [optional][default to 1000] |
| **skip** | **Integer** | The number of items to skip when paging through large result sets. | [optional] |

### Return type

[**GetCollectionItems200Response**](GetCollectionItems200Response.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_coupons_without_total_count

> <GetCouponsWithoutTotalCount200Response> get_coupons_without_total_count(application_id, campaign_id, opts)

List coupons

List all the coupons matching the specified criteria. 

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
application_id = 789 # Integer | The ID of the Application. It is displayed in your Talon.One deployment URL.
campaign_id = 789 # Integer | The ID of the campaign. It is displayed in your Talon.One deployment URL.
opts = {
  page_size: 789, # Integer | The number of items in the response.
  skip: 789, # Integer | The number of items to skip when paging through large result sets.
  sort: 'sort_example', # String | The field by which results should be sorted. By default, results are sorted in ascending order. To sort them in descending order, prefix the field name with `-`.  **Note:** You may not be able to use all fields for sorting. This is due to performance limitations. 
  value: 'value_example', # String | Filter results performing case-insensitive matching against the coupon code. Both the code and the query are folded to remove all non-alpha-numeric characters.
  created_before: Time.parse('2013-10-20T19:20:30+01:00'), # Time | Filter results comparing the parameter value, expected to be an RFC3339 timestamp string, to the coupon creation timestamp. You can use any time zone setting. Talon.One will convert to UTC internally.
  created_after: Time.parse('2013-10-20T19:20:30+01:00'), # Time | Filter results comparing the parameter value, expected to be an RFC3339 timestamp string, to the coupon creation timestamp. You can use any time zone setting. Talon.One will convert to UTC internally.
  valid: 'expired', # String | Either \"expired\", \"validNow\", or \"validFuture\". The first option matches coupons in which the expiration date is set and in the past. The second matches coupons in which start date is null or in the past and expiration date is null or in the future, the third matches coupons in which start date is set and in the future. 
  usable: 'true', # String | Either \"true\" or \"false\". If \"true\", only coupons where `usageCounter < usageLimit` will be returned, \"false\" will return only coupons where `usageCounter >= usageLimit`. 
  redeemed: 'true', # String | - `true`: only coupons where `usageCounter > 0` will be returned. - `false`: only coupons where `usageCounter = 0` will be returned. - This field cannot be used in conjunction with the `usable` query parameter. 
  referral_id: 789, # Integer | Filter the results by matching them with the ID of a referral. This filter shows the coupons created by redeeming a referral code.
  recipient_integration_id: 'recipient_integration_id_example', # String | Filter results by match with a profile ID specified in the coupon's RecipientIntegrationId field.
  batch_id: 'batch_id_example', # String | Filter results by batches of coupons
  exact_match: true, # Boolean | Filter results to an exact case-insensitive matching against the coupon code.
  expires_before: Time.parse('2013-10-20T19:20:30+01:00'), # Time | Filter results comparing the parameter value, expected to be an RFC3339 timestamp string, to the coupon expiration date timestamp. You can use any time zone setting. Talon.One will convert to UTC internally.
  expires_after: Time.parse('2013-10-20T19:20:30+01:00'), # Time | Filter results comparing the parameter value, expected to be an RFC3339 timestamp string, to the coupon expiration date timestamp. You can use any time zone setting. Talon.One will convert to UTC internally.
  starts_before: Time.parse('2013-10-20T19:20:30+01:00'), # Time | Filter results comparing the parameter value, expected to be an RFC3339 timestamp string, to the coupon start date timestamp. You can use any time zone setting. Talon.One will convert to UTC internally.
  starts_after: Time.parse('2013-10-20T19:20:30+01:00'), # Time | Filter results comparing the parameter value, expected to be an RFC3339 timestamp string, to the coupon start date timestamp. You can use any time zone setting. Talon.One will convert to UTC internally.
  values_only: true # Boolean | Filter results to only return the coupon codes (`value` column) without the associated coupon data.
}

begin
  # List coupons
  result = api_instance.get_coupons_without_total_count(application_id, campaign_id, opts)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_coupons_without_total_count: #{e}"
end
```

#### Using the get_coupons_without_total_count_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<GetCouponsWithoutTotalCount200Response>, Integer, Hash)> get_coupons_without_total_count_with_http_info(application_id, campaign_id, opts)

```ruby
begin
  # List coupons
  data, status_code, headers = api_instance.get_coupons_without_total_count_with_http_info(application_id, campaign_id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <GetCouponsWithoutTotalCount200Response>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_coupons_without_total_count_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **application_id** | **Integer** | The ID of the Application. It is displayed in your Talon.One deployment URL. |  |
| **campaign_id** | **Integer** | The ID of the campaign. It is displayed in your Talon.One deployment URL. |  |
| **page_size** | **Integer** | The number of items in the response. | [optional][default to 1000] |
| **skip** | **Integer** | The number of items to skip when paging through large result sets. | [optional] |
| **sort** | **String** | The field by which results should be sorted. By default, results are sorted in ascending order. To sort them in descending order, prefix the field name with &#x60;-&#x60;.  **Note:** You may not be able to use all fields for sorting. This is due to performance limitations.  | [optional] |
| **value** | **String** | Filter results performing case-insensitive matching against the coupon code. Both the code and the query are folded to remove all non-alpha-numeric characters. | [optional] |
| **created_before** | **Time** | Filter results comparing the parameter value, expected to be an RFC3339 timestamp string, to the coupon creation timestamp. You can use any time zone setting. Talon.One will convert to UTC internally. | [optional] |
| **created_after** | **Time** | Filter results comparing the parameter value, expected to be an RFC3339 timestamp string, to the coupon creation timestamp. You can use any time zone setting. Talon.One will convert to UTC internally. | [optional] |
| **valid** | **String** | Either \&quot;expired\&quot;, \&quot;validNow\&quot;, or \&quot;validFuture\&quot;. The first option matches coupons in which the expiration date is set and in the past. The second matches coupons in which start date is null or in the past and expiration date is null or in the future, the third matches coupons in which start date is set and in the future.  | [optional] |
| **usable** | **String** | Either \&quot;true\&quot; or \&quot;false\&quot;. If \&quot;true\&quot;, only coupons where &#x60;usageCounter &lt; usageLimit&#x60; will be returned, \&quot;false\&quot; will return only coupons where &#x60;usageCounter &gt;&#x3D; usageLimit&#x60;.  | [optional] |
| **redeemed** | **String** | - &#x60;true&#x60;: only coupons where &#x60;usageCounter &gt; 0&#x60; will be returned. - &#x60;false&#x60;: only coupons where &#x60;usageCounter &#x3D; 0&#x60; will be returned. - This field cannot be used in conjunction with the &#x60;usable&#x60; query parameter.  | [optional] |
| **referral_id** | **Integer** | Filter the results by matching them with the ID of a referral. This filter shows the coupons created by redeeming a referral code. | [optional] |
| **recipient_integration_id** | **String** | Filter results by match with a profile ID specified in the coupon&#39;s RecipientIntegrationId field. | [optional] |
| **batch_id** | **String** | Filter results by batches of coupons | [optional] |
| **exact_match** | **Boolean** | Filter results to an exact case-insensitive matching against the coupon code. | [optional][default to false] |
| **expires_before** | **Time** | Filter results comparing the parameter value, expected to be an RFC3339 timestamp string, to the coupon expiration date timestamp. You can use any time zone setting. Talon.One will convert to UTC internally. | [optional] |
| **expires_after** | **Time** | Filter results comparing the parameter value, expected to be an RFC3339 timestamp string, to the coupon expiration date timestamp. You can use any time zone setting. Talon.One will convert to UTC internally. | [optional] |
| **starts_before** | **Time** | Filter results comparing the parameter value, expected to be an RFC3339 timestamp string, to the coupon start date timestamp. You can use any time zone setting. Talon.One will convert to UTC internally. | [optional] |
| **starts_after** | **Time** | Filter results comparing the parameter value, expected to be an RFC3339 timestamp string, to the coupon start date timestamp. You can use any time zone setting. Talon.One will convert to UTC internally. | [optional] |
| **values_only** | **Boolean** | Filter results to only return the coupon codes (&#x60;value&#x60; column) without the associated coupon data. | [optional][default to false] |

### Return type

[**GetCouponsWithoutTotalCount200Response**](GetCouponsWithoutTotalCount200Response.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_customer_activity_report

> <CustomerActivityReport> get_customer_activity_report(range_start, range_end, application_id, customer_id, opts)

Get customer's activity report

Fetch the summary report of a given customer in the given application, in a time range.

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
range_start = Time.parse('2013-10-20T19:20:30+01:00') # Time | Only return results from after this timestamp.  **Note:** - This must be an RFC3339 timestamp string. - You can include a time component in your string, for example, `T23:59:59` to specify the end of the day. The time zone setting considered is `UTC`. If you do not include a time component, a default time value of `T00:00:00` (midnight) in `UTC` is considered. 
range_end = Time.parse('2013-10-20T19:20:30+01:00') # Time | Only return results from before this timestamp.  **Note:** - This must be an RFC3339 timestamp string. - You can include a time component in your string, for example, `T23:59:59` to specify the end of the day. The time zone setting considered is `UTC`. If you do not include a time component, a default time value of `T00:00:00` (midnight) in `UTC` is considered. 
application_id = 789 # Integer | The ID of the Application. It is displayed in your Talon.One deployment URL.
customer_id = 789 # Integer | The value of the `id` property of a customer profile. Get it with the [List Application's customers](https://docs.talon.one/management-api#operation/getApplicationCustomers) endpoint. 
opts = {
  page_size: 789, # Integer | The number of items in the response.
  skip: 789 # Integer | The number of items to skip when paging through large result sets.
}

begin
  # Get customer's activity report
  result = api_instance.get_customer_activity_report(range_start, range_end, application_id, customer_id, opts)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_customer_activity_report: #{e}"
end
```

#### Using the get_customer_activity_report_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<CustomerActivityReport>, Integer, Hash)> get_customer_activity_report_with_http_info(range_start, range_end, application_id, customer_id, opts)

```ruby
begin
  # Get customer's activity report
  data, status_code, headers = api_instance.get_customer_activity_report_with_http_info(range_start, range_end, application_id, customer_id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <CustomerActivityReport>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_customer_activity_report_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **range_start** | **Time** | Only return results from after this timestamp.  **Note:** - This must be an RFC3339 timestamp string. - You can include a time component in your string, for example, &#x60;T23:59:59&#x60; to specify the end of the day. The time zone setting considered is &#x60;UTC&#x60;. If you do not include a time component, a default time value of &#x60;T00:00:00&#x60; (midnight) in &#x60;UTC&#x60; is considered.  |  |
| **range_end** | **Time** | Only return results from before this timestamp.  **Note:** - This must be an RFC3339 timestamp string. - You can include a time component in your string, for example, &#x60;T23:59:59&#x60; to specify the end of the day. The time zone setting considered is &#x60;UTC&#x60;. If you do not include a time component, a default time value of &#x60;T00:00:00&#x60; (midnight) in &#x60;UTC&#x60; is considered.  |  |
| **application_id** | **Integer** | The ID of the Application. It is displayed in your Talon.One deployment URL. |  |
| **customer_id** | **Integer** | The value of the &#x60;id&#x60; property of a customer profile. Get it with the [List Application&#39;s customers](https://docs.talon.one/management-api#operation/getApplicationCustomers) endpoint.  |  |
| **page_size** | **Integer** | The number of items in the response. | [optional][default to 1000] |
| **skip** | **Integer** | The number of items to skip when paging through large result sets. | [optional] |

### Return type

[**CustomerActivityReport**](CustomerActivityReport.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_customer_activity_reports_without_total_count

> <GetCustomerActivityReportsWithoutTotalCount200Response> get_customer_activity_reports_without_total_count(range_start, range_end, application_id, opts)

Get Activity Reports for Application Customers

Fetch summary reports for all application customers based on a time range. Instead of having the total number of results in the response, this endpoint only mentions whether there are more results. 

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
range_start = Time.parse('2013-10-20T19:20:30+01:00') # Time | Only return results from after this timestamp.  **Note:** - This must be an RFC3339 timestamp string. - You can include a time component in your string, for example, `T23:59:59` to specify the end of the day. The time zone setting considered is `UTC`. If you do not include a time component, a default time value of `T00:00:00` (midnight) in `UTC` is considered. 
range_end = Time.parse('2013-10-20T19:20:30+01:00') # Time | Only return results from before this timestamp.  **Note:** - This must be an RFC3339 timestamp string. - You can include a time component in your string, for example, `T23:59:59` to specify the end of the day. The time zone setting considered is `UTC`. If you do not include a time component, a default time value of `T00:00:00` (midnight) in `UTC` is considered. 
application_id = 789 # Integer | The ID of the Application. It is displayed in your Talon.One deployment URL.
opts = {
  page_size: 789, # Integer | The number of items in the response.
  skip: 789, # Integer | The number of items to skip when paging through large result sets.
  sort: 'sort_example', # String | The field by which results should be sorted. By default, results are sorted in ascending order. To sort them in descending order, prefix the field name with `-`.  **Note:** You may not be able to use all fields for sorting. This is due to performance limitations. 
  name: 'name_example', # String | Only return reports matching the customer name.
  integration_id: 'integration_id_example', # String | Filter results performing an exact matching against the profile integration identifier.
  campaign_name: 'campaign_name_example', # String | Only return reports matching the campaign name.
  advocate_name: 'advocate_name_example' # String | Only return reports matching the current customer referrer name.
}

begin
  # Get Activity Reports for Application Customers
  result = api_instance.get_customer_activity_reports_without_total_count(range_start, range_end, application_id, opts)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_customer_activity_reports_without_total_count: #{e}"
end
```

#### Using the get_customer_activity_reports_without_total_count_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<GetCustomerActivityReportsWithoutTotalCount200Response>, Integer, Hash)> get_customer_activity_reports_without_total_count_with_http_info(range_start, range_end, application_id, opts)

```ruby
begin
  # Get Activity Reports for Application Customers
  data, status_code, headers = api_instance.get_customer_activity_reports_without_total_count_with_http_info(range_start, range_end, application_id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <GetCustomerActivityReportsWithoutTotalCount200Response>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_customer_activity_reports_without_total_count_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **range_start** | **Time** | Only return results from after this timestamp.  **Note:** - This must be an RFC3339 timestamp string. - You can include a time component in your string, for example, &#x60;T23:59:59&#x60; to specify the end of the day. The time zone setting considered is &#x60;UTC&#x60;. If you do not include a time component, a default time value of &#x60;T00:00:00&#x60; (midnight) in &#x60;UTC&#x60; is considered.  |  |
| **range_end** | **Time** | Only return results from before this timestamp.  **Note:** - This must be an RFC3339 timestamp string. - You can include a time component in your string, for example, &#x60;T23:59:59&#x60; to specify the end of the day. The time zone setting considered is &#x60;UTC&#x60;. If you do not include a time component, a default time value of &#x60;T00:00:00&#x60; (midnight) in &#x60;UTC&#x60; is considered.  |  |
| **application_id** | **Integer** | The ID of the Application. It is displayed in your Talon.One deployment URL. |  |
| **page_size** | **Integer** | The number of items in the response. | [optional][default to 1000] |
| **skip** | **Integer** | The number of items to skip when paging through large result sets. | [optional] |
| **sort** | **String** | The field by which results should be sorted. By default, results are sorted in ascending order. To sort them in descending order, prefix the field name with &#x60;-&#x60;.  **Note:** You may not be able to use all fields for sorting. This is due to performance limitations.  | [optional] |
| **name** | **String** | Only return reports matching the customer name. | [optional] |
| **integration_id** | **String** | Filter results performing an exact matching against the profile integration identifier. | [optional] |
| **campaign_name** | **String** | Only return reports matching the campaign name. | [optional] |
| **advocate_name** | **String** | Only return reports matching the current customer referrer name. | [optional] |

### Return type

[**GetCustomerActivityReportsWithoutTotalCount200Response**](GetCustomerActivityReportsWithoutTotalCount200Response.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_customer_analytics

> <CustomerAnalytics> get_customer_analytics(application_id, customer_id, opts)

Get customer's analytics report

Fetch analytics for a given customer in the given application.

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
application_id = 789 # Integer | The ID of the Application. It is displayed in your Talon.One deployment URL.
customer_id = 789 # Integer | The value of the `id` property of a customer profile. Get it with the [List Application's customers](https://docs.talon.one/management-api#operation/getApplicationCustomers) endpoint. 
opts = {
  page_size: 789, # Integer | The number of items in the response.
  skip: 789, # Integer | The number of items to skip when paging through large result sets.
  sort: 'sort_example' # String | The field by which results should be sorted. By default, results are sorted in ascending order. To sort them in descending order, prefix the field name with `-`.  **Note:** You may not be able to use all fields for sorting. This is due to performance limitations. 
}

begin
  # Get customer's analytics report
  result = api_instance.get_customer_analytics(application_id, customer_id, opts)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_customer_analytics: #{e}"
end
```

#### Using the get_customer_analytics_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<CustomerAnalytics>, Integer, Hash)> get_customer_analytics_with_http_info(application_id, customer_id, opts)

```ruby
begin
  # Get customer's analytics report
  data, status_code, headers = api_instance.get_customer_analytics_with_http_info(application_id, customer_id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <CustomerAnalytics>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_customer_analytics_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **application_id** | **Integer** | The ID of the Application. It is displayed in your Talon.One deployment URL. |  |
| **customer_id** | **Integer** | The value of the &#x60;id&#x60; property of a customer profile. Get it with the [List Application&#39;s customers](https://docs.talon.one/management-api#operation/getApplicationCustomers) endpoint.  |  |
| **page_size** | **Integer** | The number of items in the response. | [optional][default to 1000] |
| **skip** | **Integer** | The number of items to skip when paging through large result sets. | [optional] |
| **sort** | **String** | The field by which results should be sorted. By default, results are sorted in ascending order. To sort them in descending order, prefix the field name with &#x60;-&#x60;.  **Note:** You may not be able to use all fields for sorting. This is due to performance limitations.  | [optional] |

### Return type

[**CustomerAnalytics**](CustomerAnalytics.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_customer_profile

> <CustomerProfile> get_customer_profile(customer_id)

Get customer profile

Return the details of the specified customer profile.  <div class=\"redoc-section\">   <p class=\"title\">Performance tips</p>    You can retrieve the same information via the Integration API, which can save you extra API requests. consider these options:    - Request the customer profile to be part of the response content using     [Update Customer Session](https://docs.talon.one/integration-api#tag/Customer-sessions/operation/updateCustomerSessionV2).   - Send an empty update with the [Update Customer Profile](https://docs.talon.one/integration-api#tag/Customer-profiles/operation/updateCustomerProfileV2) endpoint with `runRuleEngine=false`. </div> 

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
customer_id = 789 # Integer | The value of the `id` property of a customer profile. Get it with the [List Application's customers](https://docs.talon.one/management-api#operation/getApplicationCustomers) endpoint. 

begin
  # Get customer profile
  result = api_instance.get_customer_profile(customer_id)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_customer_profile: #{e}"
end
```

#### Using the get_customer_profile_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<CustomerProfile>, Integer, Hash)> get_customer_profile_with_http_info(customer_id)

```ruby
begin
  # Get customer profile
  data, status_code, headers = api_instance.get_customer_profile_with_http_info(customer_id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <CustomerProfile>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_customer_profile_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **customer_id** | **Integer** | The value of the &#x60;id&#x60; property of a customer profile. Get it with the [List Application&#39;s customers](https://docs.talon.one/management-api#operation/getApplicationCustomers) endpoint.  |  |

### Return type

[**CustomerProfile**](CustomerProfile.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_customer_profile_achievement_progress

> <GetCustomerProfileAchievementProgress200Response> get_customer_profile_achievement_progress(application_id, integration_id, opts)

List customer achievements

For the given customer profile, list all the achievements that match your filter criteria. 

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
application_id = 789 # Integer | The ID of the Application. It is displayed in your Talon.One deployment URL.
integration_id = 'integration_id_example' # String | The integration identifier for this customer profile. Must be: - Unique within the deployment. - Stable for the customer. Do not use an ID that the customer can update themselves. For example, you can use a database ID.  Once set, you cannot update this identifier. 
opts = {
  page_size: 789, # Integer | The number of items in the response.
  skip: 789, # Integer | The number of items to skip when paging through large result sets.
  achievement_id: 789, # Integer | The ID of the achievement. You can get this ID with the [List achievement](https://docs.talon.one/management-api#tag/Achievements/operation/listAchievements) endpoint.
  title: 'title_example' # String | Filter results by the `title` of an achievement.
}

begin
  # List customer achievements
  result = api_instance.get_customer_profile_achievement_progress(application_id, integration_id, opts)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_customer_profile_achievement_progress: #{e}"
end
```

#### Using the get_customer_profile_achievement_progress_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<GetCustomerProfileAchievementProgress200Response>, Integer, Hash)> get_customer_profile_achievement_progress_with_http_info(application_id, integration_id, opts)

```ruby
begin
  # List customer achievements
  data, status_code, headers = api_instance.get_customer_profile_achievement_progress_with_http_info(application_id, integration_id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <GetCustomerProfileAchievementProgress200Response>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_customer_profile_achievement_progress_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **application_id** | **Integer** | The ID of the Application. It is displayed in your Talon.One deployment URL. |  |
| **integration_id** | **String** | The integration identifier for this customer profile. Must be: - Unique within the deployment. - Stable for the customer. Do not use an ID that the customer can update themselves. For example, you can use a database ID.  Once set, you cannot update this identifier.  |  |
| **page_size** | **Integer** | The number of items in the response. | [optional][default to 50] |
| **skip** | **Integer** | The number of items to skip when paging through large result sets. | [optional] |
| **achievement_id** | **Integer** | The ID of the achievement. You can get this ID with the [List achievement](https://docs.talon.one/management-api#tag/Achievements/operation/listAchievements) endpoint. | [optional] |
| **title** | **String** | Filter results by the &#x60;title&#x60; of an achievement. | [optional] |

### Return type

[**GetCustomerProfileAchievementProgress200Response**](GetCustomerProfileAchievementProgress200Response.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_customer_profiles

> <GetCustomerProfiles200Response> get_customer_profiles(opts)

List customer profiles

List all customer profiles.

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
opts = {
  page_size: 789, # Integer | The number of items in the response.
  skip: 789, # Integer | The number of items to skip when paging through large result sets.
  sandbox: true # Boolean | Indicates whether you are pointing to a sandbox or live customer.
}

begin
  # List customer profiles
  result = api_instance.get_customer_profiles(opts)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_customer_profiles: #{e}"
end
```

#### Using the get_customer_profiles_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<GetCustomerProfiles200Response>, Integer, Hash)> get_customer_profiles_with_http_info(opts)

```ruby
begin
  # List customer profiles
  data, status_code, headers = api_instance.get_customer_profiles_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <GetCustomerProfiles200Response>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_customer_profiles_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **page_size** | **Integer** | The number of items in the response. | [optional][default to 1000] |
| **skip** | **Integer** | The number of items to skip when paging through large result sets. | [optional] |
| **sandbox** | **Boolean** | Indicates whether you are pointing to a sandbox or live customer. | [optional][default to false] |

### Return type

[**GetCustomerProfiles200Response**](GetCustomerProfiles200Response.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_customers_by_attributes

> <GetCustomersByAttributes200Response> get_customers_by_attributes(customer_profile_search_query, opts)

List customer profiles matching the given attributes

Get a list of the customer profiles matching the provided criteria.  The match is successful if all the attributes of the request are found in a profile, even if the profile has more attributes that are not present on the request. 

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
customer_profile_search_query = TalonOne::CustomerProfileSearchQuery.new # CustomerProfileSearchQuery | body
opts = {
  page_size: 789, # Integer | The number of items in the response.
  skip: 789, # Integer | The number of items to skip when paging through large result sets.
  sandbox: true # Boolean | Indicates whether you are pointing to a sandbox or live customer.
}

begin
  # List customer profiles matching the given attributes
  result = api_instance.get_customers_by_attributes(customer_profile_search_query, opts)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_customers_by_attributes: #{e}"
end
```

#### Using the get_customers_by_attributes_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<GetCustomersByAttributes200Response>, Integer, Hash)> get_customers_by_attributes_with_http_info(customer_profile_search_query, opts)

```ruby
begin
  # List customer profiles matching the given attributes
  data, status_code, headers = api_instance.get_customers_by_attributes_with_http_info(customer_profile_search_query, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <GetCustomersByAttributes200Response>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_customers_by_attributes_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **customer_profile_search_query** | [**CustomerProfileSearchQuery**](CustomerProfileSearchQuery.md) | body |  |
| **page_size** | **Integer** | The number of items in the response. | [optional][default to 1000] |
| **skip** | **Integer** | The number of items to skip when paging through large result sets. | [optional] |
| **sandbox** | **Boolean** | Indicates whether you are pointing to a sandbox or live customer. | [optional][default to false] |

### Return type

[**GetCustomersByAttributes200Response**](GetCustomersByAttributes200Response.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## get_dashboard_statistics

> <GetDashboardStatistics200Response> get_dashboard_statistics(loyalty_program_id, range_start, range_end, opts)

Get statistics for loyalty dashboard

Retrieve the statistics displayed on the specified loyalty program's dashboard, such as the total active points, pending points, spent points, and expired points.  **Important:** The returned data does not include the current day. All statistics are updated daily at 11:59 PM in the loyalty program time zone. 

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
loyalty_program_id = 789 # Integer | Identifier of the loyalty program. You can get the ID with the [List loyalty programs](https://docs.talon.one/management-api#tag/Loyalty/operation/getLoyaltyPrograms) endpoint. 
range_start = Time.parse('2013-10-20T19:20:30+01:00') # Time | Only return results from after this timestamp.  **Note:** - This must be an RFC3339 timestamp string. - You can include a time component in your string, for example, `T23:59:59` to specify the end of the day. The time zone setting considered is `UTC`. If you do not include a time component, a default time value of `T00:00:00` (midnight) in `UTC` is considered. 
range_end = Time.parse('2013-10-20T19:20:30+01:00') # Time | Only return results from before this timestamp.  **Note:** - This must be an RFC3339 timestamp string. - You can include a time component in your string, for example, `T23:59:59` to specify the end of the day. The time zone setting considered is `UTC`. If you do not include a time component, a default time value of `T00:00:00` (midnight) in `UTC` is considered. 
opts = {
  subledger_id: 'subledger_id_example' # String | The ID of the subledger by which we filter the data.
}

begin
  # Get statistics for loyalty dashboard
  result = api_instance.get_dashboard_statistics(loyalty_program_id, range_start, range_end, opts)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_dashboard_statistics: #{e}"
end
```

#### Using the get_dashboard_statistics_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<GetDashboardStatistics200Response>, Integer, Hash)> get_dashboard_statistics_with_http_info(loyalty_program_id, range_start, range_end, opts)

```ruby
begin
  # Get statistics for loyalty dashboard
  data, status_code, headers = api_instance.get_dashboard_statistics_with_http_info(loyalty_program_id, range_start, range_end, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <GetDashboardStatistics200Response>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_dashboard_statistics_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **loyalty_program_id** | **Integer** | Identifier of the loyalty program. You can get the ID with the [List loyalty programs](https://docs.talon.one/management-api#tag/Loyalty/operation/getLoyaltyPrograms) endpoint.  |  |
| **range_start** | **Time** | Only return results from after this timestamp.  **Note:** - This must be an RFC3339 timestamp string. - You can include a time component in your string, for example, &#x60;T23:59:59&#x60; to specify the end of the day. The time zone setting considered is &#x60;UTC&#x60;. If you do not include a time component, a default time value of &#x60;T00:00:00&#x60; (midnight) in &#x60;UTC&#x60; is considered.  |  |
| **range_end** | **Time** | Only return results from before this timestamp.  **Note:** - This must be an RFC3339 timestamp string. - You can include a time component in your string, for example, &#x60;T23:59:59&#x60; to specify the end of the day. The time zone setting considered is &#x60;UTC&#x60;. If you do not include a time component, a default time value of &#x60;T00:00:00&#x60; (midnight) in &#x60;UTC&#x60; is considered.  |  |
| **subledger_id** | **String** | The ID of the subledger by which we filter the data. | [optional] |

### Return type

[**GetDashboardStatistics200Response**](GetDashboardStatistics200Response.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_event_types

> <GetEventTypes200Response> get_event_types(opts)

List event types

Fetch all event type definitions for your account. 

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
opts = {
  name: 'name_example', # String | Filter results to event types with the given name. This parameter implies `includeOldVersions`.
  include_old_versions: true, # Boolean | Include all versions of every event type.
  page_size: 789, # Integer | The number of items in the response.
  skip: 789, # Integer | The number of items to skip when paging through large result sets.
  sort: 'sort_example' # String | The field by which results should be sorted. By default, results are sorted in ascending order. To sort them in descending order, prefix the field name with `-`.  **Note:** You may not be able to use all fields for sorting. This is due to performance limitations. 
}

begin
  # List event types
  result = api_instance.get_event_types(opts)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_event_types: #{e}"
end
```

#### Using the get_event_types_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<GetEventTypes200Response>, Integer, Hash)> get_event_types_with_http_info(opts)

```ruby
begin
  # List event types
  data, status_code, headers = api_instance.get_event_types_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <GetEventTypes200Response>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_event_types_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **name** | **String** | Filter results to event types with the given name. This parameter implies &#x60;includeOldVersions&#x60;. | [optional] |
| **include_old_versions** | **Boolean** | Include all versions of every event type. | [optional][default to false] |
| **page_size** | **Integer** | The number of items in the response. | [optional][default to 1000] |
| **skip** | **Integer** | The number of items to skip when paging through large result sets. | [optional] |
| **sort** | **String** | The field by which results should be sorted. By default, results are sorted in ascending order. To sort them in descending order, prefix the field name with &#x60;-&#x60;.  **Note:** You may not be able to use all fields for sorting. This is due to performance limitations.  | [optional] |

### Return type

[**GetEventTypes200Response**](GetEventTypes200Response.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_exports

> <GetExports200Response> get_exports(opts)

Get exports

List all past exports 

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
opts = {
  page_size: 789, # Integer | The number of items in the response.
  skip: 789, # Integer | The number of items to skip when paging through large result sets.
  application_id: 8.14, # Float | Filter results by Application ID.
  campaign_id: 789, # Integer | Filter by the campaign ID on which the limit counters are used.
  entity: 'Coupon' # String | The name of the entity type that was exported.
}

begin
  # Get exports
  result = api_instance.get_exports(opts)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_exports: #{e}"
end
```

#### Using the get_exports_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<GetExports200Response>, Integer, Hash)> get_exports_with_http_info(opts)

```ruby
begin
  # Get exports
  data, status_code, headers = api_instance.get_exports_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <GetExports200Response>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_exports_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **page_size** | **Integer** | The number of items in the response. | [optional][default to 1000] |
| **skip** | **Integer** | The number of items to skip when paging through large result sets. | [optional] |
| **application_id** | **Float** | Filter results by Application ID. | [optional] |
| **campaign_id** | **Integer** | Filter by the campaign ID on which the limit counters are used. | [optional] |
| **entity** | **String** | The name of the entity type that was exported. | [optional] |

### Return type

[**GetExports200Response**](GetExports200Response.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_loyalty_card

> <LoyaltyCard> get_loyalty_card(loyalty_program_id, loyalty_card_id)

Get loyalty card

Get the given loyalty card.

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
loyalty_program_id = 789 # Integer | Identifier of the card-based loyalty program containing the loyalty card. You can get the ID with the [List loyalty programs](https://docs.talon.one/management-api#tag/Loyalty/operation/getLoyaltyPrograms) endpoint. 
loyalty_card_id = 'loyalty_card_id_example' # String | Identifier of the loyalty card. You can get the identifier with the [List loyalty cards](https://docs.talon.one/management-api#tag/Loyalty-cards/operation/getLoyaltyCards) endpoint. 

begin
  # Get loyalty card
  result = api_instance.get_loyalty_card(loyalty_program_id, loyalty_card_id)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_loyalty_card: #{e}"
end
```

#### Using the get_loyalty_card_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<LoyaltyCard>, Integer, Hash)> get_loyalty_card_with_http_info(loyalty_program_id, loyalty_card_id)

```ruby
begin
  # Get loyalty card
  data, status_code, headers = api_instance.get_loyalty_card_with_http_info(loyalty_program_id, loyalty_card_id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <LoyaltyCard>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_loyalty_card_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **loyalty_program_id** | **Integer** | Identifier of the card-based loyalty program containing the loyalty card. You can get the ID with the [List loyalty programs](https://docs.talon.one/management-api#tag/Loyalty/operation/getLoyaltyPrograms) endpoint.  |  |
| **loyalty_card_id** | **String** | Identifier of the loyalty card. You can get the identifier with the [List loyalty cards](https://docs.talon.one/management-api#tag/Loyalty-cards/operation/getLoyaltyCards) endpoint.  |  |

### Return type

[**LoyaltyCard**](LoyaltyCard.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_loyalty_card_transaction_logs

> <GetLoyaltyCardTransactionLogs200Response> get_loyalty_card_transaction_logs(loyalty_program_id, loyalty_card_id, opts)

List card's transactions

Retrieve the transaction logs for the given [loyalty card](https://docs.talon.one/docs/product/loyalty-programs/card-based/card-based-overview) within the specified [card-based loyalty program](https://docs.talon.one/docs/product/loyalty-programs/overview#loyalty-program-types) with filtering options applied. If no filtering options are applied, the last 50 loyalty transactions for the given loyalty card are returned. 

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
loyalty_program_id = 789 # Integer | Identifier of the card-based loyalty program containing the loyalty card. You can get the ID with the [List loyalty programs](https://docs.talon.one/management-api#tag/Loyalty/operation/getLoyaltyPrograms) endpoint. 
loyalty_card_id = 'loyalty_card_id_example' # String | Identifier of the loyalty card. You can get the identifier with the [List loyalty cards](https://docs.talon.one/management-api#tag/Loyalty-cards/operation/getLoyaltyCards) endpoint. 
opts = {
  start_date: Time.parse('2013-10-20T19:20:30+01:00'), # Time | Date and time from which results are returned. Results are filtered by transaction creation date.  **Note:**  - It must be an RFC3339 timestamp string. - You can include a time component in your string, for example, `T23:59:59` to specify the end of the day. The time zone setting considered is `UTC`. If you do not include a time component, a default time value of `T00:00:00` (midnight) in `UTC` is considered. 
  end_date: Time.parse('2013-10-20T19:20:30+01:00'), # Time | Date and time by which results are returned. Results are filtered by transaction creation date.  **Note:**  - It must be an RFC3339 timestamp string. - You can include a time component in your string, for example, `T23:59:59` to specify the end of the day. The time zone setting considered is `UTC`. If you do not include a time component, a default time value of `T00:00:00` (midnight) in `UTC` is considered. 
  page_size: 789, # Integer | The number of items in the response.
  skip: 789, # Integer | The number of items to skip when paging through large result sets.
  subledger_id: 'subledger_id_example', # String | The ID of the subledger by which we filter the data.
  customer_session_ids: ['inner_example'], # Array<String> | Filter the results by a list of customer session IDs.   To include multiple IDs, repeat the parameter for each one, for example,  `?customerSessionIDs=id1&customerSessionIDs=id2`.  The response contains only data associated with the specified sessions. 
  transaction_uuids: ['inner_example'] # Array<String> | Filter the results by a list of transaction UUIDs.  To include multiple IDs, repeat the parameter for each one, for example,  `?transactionUUIDs=uuid1&transactionUUIDs=uuid2`.  The response contains only data associated with the specified transactions. 
}

begin
  # List card's transactions
  result = api_instance.get_loyalty_card_transaction_logs(loyalty_program_id, loyalty_card_id, opts)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_loyalty_card_transaction_logs: #{e}"
end
```

#### Using the get_loyalty_card_transaction_logs_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<GetLoyaltyCardTransactionLogs200Response>, Integer, Hash)> get_loyalty_card_transaction_logs_with_http_info(loyalty_program_id, loyalty_card_id, opts)

```ruby
begin
  # List card's transactions
  data, status_code, headers = api_instance.get_loyalty_card_transaction_logs_with_http_info(loyalty_program_id, loyalty_card_id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <GetLoyaltyCardTransactionLogs200Response>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_loyalty_card_transaction_logs_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **loyalty_program_id** | **Integer** | Identifier of the card-based loyalty program containing the loyalty card. You can get the ID with the [List loyalty programs](https://docs.talon.one/management-api#tag/Loyalty/operation/getLoyaltyPrograms) endpoint.  |  |
| **loyalty_card_id** | **String** | Identifier of the loyalty card. You can get the identifier with the [List loyalty cards](https://docs.talon.one/management-api#tag/Loyalty-cards/operation/getLoyaltyCards) endpoint.  |  |
| **start_date** | **Time** | Date and time from which results are returned. Results are filtered by transaction creation date.  **Note:**  - It must be an RFC3339 timestamp string. - You can include a time component in your string, for example, &#x60;T23:59:59&#x60; to specify the end of the day. The time zone setting considered is &#x60;UTC&#x60;. If you do not include a time component, a default time value of &#x60;T00:00:00&#x60; (midnight) in &#x60;UTC&#x60; is considered.  | [optional] |
| **end_date** | **Time** | Date and time by which results are returned. Results are filtered by transaction creation date.  **Note:**  - It must be an RFC3339 timestamp string. - You can include a time component in your string, for example, &#x60;T23:59:59&#x60; to specify the end of the day. The time zone setting considered is &#x60;UTC&#x60;. If you do not include a time component, a default time value of &#x60;T00:00:00&#x60; (midnight) in &#x60;UTC&#x60; is considered.  | [optional] |
| **page_size** | **Integer** | The number of items in the response. | [optional][default to 1000] |
| **skip** | **Integer** | The number of items to skip when paging through large result sets. | [optional] |
| **subledger_id** | **String** | The ID of the subledger by which we filter the data. | [optional] |
| **customer_session_ids** | [**Array&lt;String&gt;**](String.md) | Filter the results by a list of customer session IDs.   To include multiple IDs, repeat the parameter for each one, for example,  &#x60;?customerSessionIDs&#x3D;id1&amp;customerSessionIDs&#x3D;id2&#x60;.  The response contains only data associated with the specified sessions.  | [optional] |
| **transaction_uuids** | [**Array&lt;String&gt;**](String.md) | Filter the results by a list of transaction UUIDs.  To include multiple IDs, repeat the parameter for each one, for example,  &#x60;?transactionUUIDs&#x3D;uuid1&amp;transactionUUIDs&#x3D;uuid2&#x60;.  The response contains only data associated with the specified transactions.  | [optional] |

### Return type

[**GetLoyaltyCardTransactionLogs200Response**](GetLoyaltyCardTransactionLogs200Response.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_loyalty_cards

> <GetLoyaltyCards200Response> get_loyalty_cards(loyalty_program_id, opts)

List loyalty cards

For the given card-based loyalty program, list the loyalty cards that match your filter criteria. 

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
loyalty_program_id = 789 # Integer | Identifier of the card-based loyalty program containing the loyalty card. You can get the ID with the [List loyalty programs](https://docs.talon.one/management-api#tag/Loyalty/operation/getLoyaltyPrograms) endpoint. 
opts = {
  page_size: 789, # Integer | The number of items in the response.
  skip: 789, # Integer | The number of items to skip when paging through large result sets.
  sort: 'sort_example', # String | The field by which results should be sorted. By default, results are sorted in ascending order. To sort them in descending order, prefix the field name with `-`.  **Note:** You may not be able to use all fields for sorting. This is due to performance limitations. 
  identifier: 'identifier_example', # String | The card code by which to filter loyalty cards in the response.
  profile_id: 789, # Integer | Filter results by customer profile ID.
  batch_id: 'batch_id_example' # String | Filter results by loyalty card batch ID.
}

begin
  # List loyalty cards
  result = api_instance.get_loyalty_cards(loyalty_program_id, opts)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_loyalty_cards: #{e}"
end
```

#### Using the get_loyalty_cards_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<GetLoyaltyCards200Response>, Integer, Hash)> get_loyalty_cards_with_http_info(loyalty_program_id, opts)

```ruby
begin
  # List loyalty cards
  data, status_code, headers = api_instance.get_loyalty_cards_with_http_info(loyalty_program_id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <GetLoyaltyCards200Response>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_loyalty_cards_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **loyalty_program_id** | **Integer** | Identifier of the card-based loyalty program containing the loyalty card. You can get the ID with the [List loyalty programs](https://docs.talon.one/management-api#tag/Loyalty/operation/getLoyaltyPrograms) endpoint.  |  |
| **page_size** | **Integer** | The number of items in the response. | [optional][default to 1000] |
| **skip** | **Integer** | The number of items to skip when paging through large result sets. | [optional] |
| **sort** | **String** | The field by which results should be sorted. By default, results are sorted in ascending order. To sort them in descending order, prefix the field name with &#x60;-&#x60;.  **Note:** You may not be able to use all fields for sorting. This is due to performance limitations.  | [optional] |
| **identifier** | **String** | The card code by which to filter loyalty cards in the response. | [optional] |
| **profile_id** | **Integer** | Filter results by customer profile ID. | [optional] |
| **batch_id** | **String** | Filter results by loyalty card batch ID. | [optional] |

### Return type

[**GetLoyaltyCards200Response**](GetLoyaltyCards200Response.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_loyalty_ledger_balances

> <LoyaltyBalancesWithTiers> get_loyalty_ledger_balances(loyalty_program_id, integration_id, opts)

Get customer's loyalty balances

Retrieve loyalty ledger balances for the given Integration ID in the specified loyalty program. You can filter balances by date and subledger ID, and include tier-related information in the response.  **Note**: If no filtering options are applied, you retrieve all loyalty balances on the current date for the given integration ID.  Loyalty balances are calculated when Talon.One receives your request using the points stored in our database, so retrieving a large number of balances at once can impact performance.  For more information, see: - [Managing card-based loyalty program data](https://docs.talon.one/docs/product/loyalty-programs/card-based/managing-loyalty-cards) - [Managing profile-based loyalty program data](https://docs.talon.one/docs/product/loyalty-programs/profile-based/managing-pb-lp-data) 

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
loyalty_program_id = 789 # Integer | Identifier of the profile-based loyalty program. You can get the ID with the [List loyalty programs](https://docs.talon.one/management-api#tag/Loyalty/operation/getLoyaltyPrograms) endpoint. 
integration_id = 'integration_id_example' # String | The integration identifier for this customer profile. Must be: - Unique within the deployment. - Stable for the customer. Do not use an ID that the customer can update themselves. For example, you can use a database ID.  Once set, you cannot update this identifier. 
opts = {
  end_date: Time.parse('2013-10-20T19:20:30+01:00'), # Time | Used to return expired, active, and pending loyalty balances before this timestamp. You can enter any past, present, or future timestamp value.  **Note:**  - It must be an RFC3339 timestamp string. - You can include a time component in your string, for example, `T23:59:59` to specify the end of the day. The time zone setting considered is `UTC`. If you do not include a time component, a default time value of `T00:00:00` (midnight) in `UTC` is considered. 
  subledger_id: 'subledger_id_example', # String | The ID of the subledger used to filter the data. Leave this value empty (\"\") to query the main ledger.
  include_tiers: true, # Boolean | Indicates whether tier information is included in the response.  When set to `true`, the response includes information about the current tier and the number of points required to move to next tier. 
  include_projected_tier: true # Boolean | Indicates whether the customer's projected tier information is included in the response.  When set to `true`, the response includes information about the customer's active points and the name of the projected tier.  **Note** We recommend filtering by `subledgerId` for better performance. 
}

begin
  # Get customer's loyalty balances
  result = api_instance.get_loyalty_ledger_balances(loyalty_program_id, integration_id, opts)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_loyalty_ledger_balances: #{e}"
end
```

#### Using the get_loyalty_ledger_balances_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<LoyaltyBalancesWithTiers>, Integer, Hash)> get_loyalty_ledger_balances_with_http_info(loyalty_program_id, integration_id, opts)

```ruby
begin
  # Get customer's loyalty balances
  data, status_code, headers = api_instance.get_loyalty_ledger_balances_with_http_info(loyalty_program_id, integration_id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <LoyaltyBalancesWithTiers>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_loyalty_ledger_balances_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **loyalty_program_id** | **Integer** | Identifier of the profile-based loyalty program. You can get the ID with the [List loyalty programs](https://docs.talon.one/management-api#tag/Loyalty/operation/getLoyaltyPrograms) endpoint.  |  |
| **integration_id** | **String** | The integration identifier for this customer profile. Must be: - Unique within the deployment. - Stable for the customer. Do not use an ID that the customer can update themselves. For example, you can use a database ID.  Once set, you cannot update this identifier.  |  |
| **end_date** | **Time** | Used to return expired, active, and pending loyalty balances before this timestamp. You can enter any past, present, or future timestamp value.  **Note:**  - It must be an RFC3339 timestamp string. - You can include a time component in your string, for example, &#x60;T23:59:59&#x60; to specify the end of the day. The time zone setting considered is &#x60;UTC&#x60;. If you do not include a time component, a default time value of &#x60;T00:00:00&#x60; (midnight) in &#x60;UTC&#x60; is considered.  | [optional] |
| **subledger_id** | **String** | The ID of the subledger used to filter the data. Leave this value empty (\&quot;\&quot;) to query the main ledger. | [optional] |
| **include_tiers** | **Boolean** | Indicates whether tier information is included in the response.  When set to &#x60;true&#x60;, the response includes information about the current tier and the number of points required to move to next tier.  | [optional][default to false] |
| **include_projected_tier** | **Boolean** | Indicates whether the customer&#39;s projected tier information is included in the response.  When set to &#x60;true&#x60;, the response includes information about the customer&#39;s active points and the name of the projected tier.  **Note** We recommend filtering by &#x60;subledgerId&#x60; for better performance.  | [optional][default to false] |

### Return type

[**LoyaltyBalancesWithTiers**](LoyaltyBalancesWithTiers.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_loyalty_points

> <LoyaltyLedger> get_loyalty_points(loyalty_program_id, integration_id)

Get customer's full loyalty ledger

Get the loyalty ledger for this profile integration ID.  To get the `integrationId` of the profile from a `sessionId`, use the [Update customer session](https://docs.talon.one/integration-api#operation/updateCustomerSessionV2) endpoint.  **Important:** To get loyalty transaction logs for a given Integration ID in a loyalty program, we recommend using the Integration API's [Get customer's loyalty logs](https://docs.talon.one/integration-api#tag/Loyalty/operation/getLoyaltyProgramProfileTransactions). 

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
loyalty_program_id = 'loyalty_program_id_example' # String | The identifier for the loyalty program.
integration_id = 'integration_id_example' # String | The integration identifier for this customer profile. Must be: - Unique within the deployment. - Stable for the customer. Do not use an ID that the customer can update themselves. For example, you can use a database ID.  Once set, you cannot update this identifier. 

begin
  # Get customer's full loyalty ledger
  result = api_instance.get_loyalty_points(loyalty_program_id, integration_id)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_loyalty_points: #{e}"
end
```

#### Using the get_loyalty_points_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<LoyaltyLedger>, Integer, Hash)> get_loyalty_points_with_http_info(loyalty_program_id, integration_id)

```ruby
begin
  # Get customer's full loyalty ledger
  data, status_code, headers = api_instance.get_loyalty_points_with_http_info(loyalty_program_id, integration_id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <LoyaltyLedger>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_loyalty_points_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **loyalty_program_id** | **String** | The identifier for the loyalty program. |  |
| **integration_id** | **String** | The integration identifier for this customer profile. Must be: - Unique within the deployment. - Stable for the customer. Do not use an ID that the customer can update themselves. For example, you can use a database ID.  Once set, you cannot update this identifier.  |  |

### Return type

[**LoyaltyLedger**](LoyaltyLedger.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_loyalty_program

> <LoyaltyProgram> get_loyalty_program(loyalty_program_id)

Get loyalty program

Get the specified [loyalty program](https://docs.talon.one/docs/product/loyalty-programs/overview). To list all loyalty programs in your Application, use [List loyalty programs](#operation/getLoyaltyPrograms).  To list the loyalty programs that a customer profile is part of, use the [List customer data](https://docs.talon.one/integration-api#tag/Customer-profiles/operation/getCustomerInventory) 

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
loyalty_program_id = 789 # Integer | Identifier of the loyalty program. You can get the ID with the [List loyalty programs](https://docs.talon.one/management-api#tag/Loyalty/operation/getLoyaltyPrograms) endpoint. 

begin
  # Get loyalty program
  result = api_instance.get_loyalty_program(loyalty_program_id)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_loyalty_program: #{e}"
end
```

#### Using the get_loyalty_program_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<LoyaltyProgram>, Integer, Hash)> get_loyalty_program_with_http_info(loyalty_program_id)

```ruby
begin
  # Get loyalty program
  data, status_code, headers = api_instance.get_loyalty_program_with_http_info(loyalty_program_id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <LoyaltyProgram>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_loyalty_program_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **loyalty_program_id** | **Integer** | Identifier of the loyalty program. You can get the ID with the [List loyalty programs](https://docs.talon.one/management-api#tag/Loyalty/operation/getLoyaltyPrograms) endpoint.  |  |

### Return type

[**LoyaltyProgram**](LoyaltyProgram.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_loyalty_program_profile_ledger_transactions

> <GetLoyaltyProgramProfileTransactions200Response> get_loyalty_program_profile_ledger_transactions(loyalty_program_id, integration_id, opts)

List customer's loyalty transactions

Retrieve paginated results of loyalty transaction logs for the given Integration ID in the specified loyalty program.  You can filter transactions by date or by ledger (subledger or main ledger). If no filters are applied, the last 50 loyalty transactions for the given integration ID are returned.  **Note:** To retrieve all loyalty program transaction logs in a given loyalty program, use the [List loyalty program transactions](https://docs.talon.one/management-api#tag/Loyalty/operation/getLoyaltyProgramTransactions) endpoint. 

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
loyalty_program_id = 789 # Integer | Identifier of the profile-based loyalty program. You can get the ID with the [List loyalty programs](https://docs.talon.one/management-api#tag/Loyalty/operation/getLoyaltyPrograms) endpoint. 
integration_id = 'integration_id_example' # String | The integration identifier for this customer profile. Must be: - Unique within the deployment. - Stable for the customer. Do not use an ID that the customer can update themselves. For example, you can use a database ID.  Once set, you cannot update this identifier. 
opts = {
  customer_session_ids: ['inner_example'], # Array<String> | Filter the results by a list of customer session IDs.   To include multiple IDs, repeat the parameter for each one, for example,  `?customerSessionIDs=id1&customerSessionIDs=id2`.  The response contains only data associated with the specified sessions. 
  transaction_uuids: ['inner_example'], # Array<String> | Filter the results by a list of transaction UUIDs.  To include multiple IDs, repeat the parameter for each one, for example,  `?transactionUUIDs=uuid1&transactionUUIDs=uuid2`.  The response contains only data associated with the specified transactions. 
  subledger_id: 'subledger_id_example', # String | The ID of the subledger used to filter the data. Leave this value empty (\"\") to query the main ledger.
  loyalty_transaction_type: 'manual', # String | Filter results by loyalty transaction type: - `manual`: Loyalty transaction that was done manually. - `session`: Loyalty transaction that resulted from a customer session. - `import`: Loyalty transaction that was imported from a CSV file. 
  start_date: Time.parse('2013-10-20T19:20:30+01:00'), # Time | Date and time from which results are returned. Results are filtered by transaction creation date.  **Note:**  - It must be an RFC3339 timestamp string. - You can include a time component in your string, for example, `T23:59:59` to specify the end of the day. The time zone setting considered is `UTC`. If you do not include a time component, a default time value of `T00:00:00` (midnight) in `UTC` is considered. 
  end_date: Time.parse('2013-10-20T19:20:30+01:00'), # Time | Date and time by which results are returned. Results are filtered by transaction creation date.  **Note:**  - It must be an RFC3339 timestamp string. - You can include a time component in your string, for example, `T23:59:59` to specify the end of the day. The time zone setting considered is `UTC`. If you do not include a time component, a default time value of `T00:00:00` (midnight) in `UTC` is considered. 
  page_size: 789, # Integer | The number of items in the response.
  skip: 789, # Integer | The number of items to skip when paging through large result sets.
  awaits_activation: true # Boolean | If `true`: Filters results to include only point transactions that have action-based activation and have not expired.  If `false`: Returns a `400` response. 
}

begin
  # List customer's loyalty transactions
  result = api_instance.get_loyalty_program_profile_ledger_transactions(loyalty_program_id, integration_id, opts)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_loyalty_program_profile_ledger_transactions: #{e}"
end
```

#### Using the get_loyalty_program_profile_ledger_transactions_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<GetLoyaltyProgramProfileTransactions200Response>, Integer, Hash)> get_loyalty_program_profile_ledger_transactions_with_http_info(loyalty_program_id, integration_id, opts)

```ruby
begin
  # List customer's loyalty transactions
  data, status_code, headers = api_instance.get_loyalty_program_profile_ledger_transactions_with_http_info(loyalty_program_id, integration_id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <GetLoyaltyProgramProfileTransactions200Response>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_loyalty_program_profile_ledger_transactions_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **loyalty_program_id** | **Integer** | Identifier of the profile-based loyalty program. You can get the ID with the [List loyalty programs](https://docs.talon.one/management-api#tag/Loyalty/operation/getLoyaltyPrograms) endpoint.  |  |
| **integration_id** | **String** | The integration identifier for this customer profile. Must be: - Unique within the deployment. - Stable for the customer. Do not use an ID that the customer can update themselves. For example, you can use a database ID.  Once set, you cannot update this identifier.  |  |
| **customer_session_ids** | [**Array&lt;String&gt;**](String.md) | Filter the results by a list of customer session IDs.   To include multiple IDs, repeat the parameter for each one, for example,  &#x60;?customerSessionIDs&#x3D;id1&amp;customerSessionIDs&#x3D;id2&#x60;.  The response contains only data associated with the specified sessions.  | [optional] |
| **transaction_uuids** | [**Array&lt;String&gt;**](String.md) | Filter the results by a list of transaction UUIDs.  To include multiple IDs, repeat the parameter for each one, for example,  &#x60;?transactionUUIDs&#x3D;uuid1&amp;transactionUUIDs&#x3D;uuid2&#x60;.  The response contains only data associated with the specified transactions.  | [optional] |
| **subledger_id** | **String** | The ID of the subledger used to filter the data. Leave this value empty (\&quot;\&quot;) to query the main ledger. | [optional] |
| **loyalty_transaction_type** | **String** | Filter results by loyalty transaction type: - &#x60;manual&#x60;: Loyalty transaction that was done manually. - &#x60;session&#x60;: Loyalty transaction that resulted from a customer session. - &#x60;import&#x60;: Loyalty transaction that was imported from a CSV file.  | [optional] |
| **start_date** | **Time** | Date and time from which results are returned. Results are filtered by transaction creation date.  **Note:**  - It must be an RFC3339 timestamp string. - You can include a time component in your string, for example, &#x60;T23:59:59&#x60; to specify the end of the day. The time zone setting considered is &#x60;UTC&#x60;. If you do not include a time component, a default time value of &#x60;T00:00:00&#x60; (midnight) in &#x60;UTC&#x60; is considered.  | [optional] |
| **end_date** | **Time** | Date and time by which results are returned. Results are filtered by transaction creation date.  **Note:**  - It must be an RFC3339 timestamp string. - You can include a time component in your string, for example, &#x60;T23:59:59&#x60; to specify the end of the day. The time zone setting considered is &#x60;UTC&#x60;. If you do not include a time component, a default time value of &#x60;T00:00:00&#x60; (midnight) in &#x60;UTC&#x60; is considered.  | [optional] |
| **page_size** | **Integer** | The number of items in the response. | [optional][default to 50] |
| **skip** | **Integer** | The number of items to skip when paging through large result sets. | [optional] |
| **awaits_activation** | **Boolean** | If &#x60;true&#x60;: Filters results to include only point transactions that have action-based activation and have not expired.  If &#x60;false&#x60;: Returns a &#x60;400&#x60; response.  | [optional] |

### Return type

[**GetLoyaltyProgramProfileTransactions200Response**](GetLoyaltyProgramProfileTransactions200Response.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_loyalty_program_transactions

> <GetLoyaltyProgramTransactions200Response> get_loyalty_program_transactions(loyalty_program_id, opts)

List loyalty program transactions

Retrieve loyalty program transaction logs in a given loyalty program with filtering options applied. Manual and imported transactions are also included. **Note:** If no filters are applied, the last 50 loyalty transactions for the given loyalty program are returned.  **Important:** To get loyalty transaction logs for a given Integration ID in a loyalty program, we recommend using the Integration API's [Get customer's loyalty logs](https://docs.talon.one/integration-api#tag/Loyalty/operation/getLoyaltyProgramProfileTransactions). 

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
loyalty_program_id = 789 # Integer | Identifier of the loyalty program. You can get the ID with the [List loyalty programs](https://docs.talon.one/management-api#tag/Loyalty/operation/getLoyaltyPrograms) endpoint. 
opts = {
  loyalty_transaction_type: 'manual', # String | Filter results by loyalty transaction type: - `manual`: Loyalty transaction that was done manually. - `session`: Loyalty transaction that resulted from a customer session. - `import`: Loyalty transaction that was imported from a CSV file. 
  subledger_id: 'subledger_id_example', # String | The ID of the subledger by which we filter the data.
  customer_session_ids: ['inner_example'], # Array<String> | Filter the results by a list of customer session IDs.   To include multiple IDs, repeat the parameter for each one, for example,  `?customerSessionIDs=id1&customerSessionIDs=id2`.  The response contains only data associated with the specified sessions. 
  transaction_uuids: ['inner_example'], # Array<String> | Filter the results by a list of transaction UUIDs.  To include multiple IDs, repeat the parameter for each one, for example,  `?transactionUUIDs=uuid1&transactionUUIDs=uuid2`.  The response contains only data associated with the specified transactions. 
  start_date: Time.parse('2013-10-20T19:20:30+01:00'), # Time | Date and time from which results are returned. Results are filtered by transaction creation date.  **Note:**  - It must be an RFC3339 timestamp string. - You can include a time component in your string, for example, `T23:59:59` to specify the end of the day. The time zone setting considered is `UTC`. If you do not include a time component, a default time value of `T00:00:00` (midnight) in `UTC` is considered. 
  end_date: Time.parse('2013-10-20T19:20:30+01:00'), # Time | Date and time by which results are returned. Results are filtered by transaction creation date.  **Note:**  - It must be an RFC3339 timestamp string. - You can include a time component in your string, for example, `T23:59:59` to specify the end of the day. The time zone setting considered is `UTC`. If you do not include a time component, a default time value of `T00:00:00` (midnight) in `UTC` is considered. 
  page_size: 789, # Integer | The number of items in the response.
  skip: 789, # Integer | The number of items to skip when paging through large result sets.
  awaits_activation: true # Boolean | If `true`: Filters results to include only point transactions that have action-based activation and have not expired.  If `false`: Returns a `400` response. 
}

begin
  # List loyalty program transactions
  result = api_instance.get_loyalty_program_transactions(loyalty_program_id, opts)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_loyalty_program_transactions: #{e}"
end
```

#### Using the get_loyalty_program_transactions_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<GetLoyaltyProgramTransactions200Response>, Integer, Hash)> get_loyalty_program_transactions_with_http_info(loyalty_program_id, opts)

```ruby
begin
  # List loyalty program transactions
  data, status_code, headers = api_instance.get_loyalty_program_transactions_with_http_info(loyalty_program_id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <GetLoyaltyProgramTransactions200Response>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_loyalty_program_transactions_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **loyalty_program_id** | **Integer** | Identifier of the loyalty program. You can get the ID with the [List loyalty programs](https://docs.talon.one/management-api#tag/Loyalty/operation/getLoyaltyPrograms) endpoint.  |  |
| **loyalty_transaction_type** | **String** | Filter results by loyalty transaction type: - &#x60;manual&#x60;: Loyalty transaction that was done manually. - &#x60;session&#x60;: Loyalty transaction that resulted from a customer session. - &#x60;import&#x60;: Loyalty transaction that was imported from a CSV file.  | [optional] |
| **subledger_id** | **String** | The ID of the subledger by which we filter the data. | [optional] |
| **customer_session_ids** | [**Array&lt;String&gt;**](String.md) | Filter the results by a list of customer session IDs.   To include multiple IDs, repeat the parameter for each one, for example,  &#x60;?customerSessionIDs&#x3D;id1&amp;customerSessionIDs&#x3D;id2&#x60;.  The response contains only data associated with the specified sessions.  | [optional] |
| **transaction_uuids** | [**Array&lt;String&gt;**](String.md) | Filter the results by a list of transaction UUIDs.  To include multiple IDs, repeat the parameter for each one, for example,  &#x60;?transactionUUIDs&#x3D;uuid1&amp;transactionUUIDs&#x3D;uuid2&#x60;.  The response contains only data associated with the specified transactions.  | [optional] |
| **start_date** | **Time** | Date and time from which results are returned. Results are filtered by transaction creation date.  **Note:**  - It must be an RFC3339 timestamp string. - You can include a time component in your string, for example, &#x60;T23:59:59&#x60; to specify the end of the day. The time zone setting considered is &#x60;UTC&#x60;. If you do not include a time component, a default time value of &#x60;T00:00:00&#x60; (midnight) in &#x60;UTC&#x60; is considered.  | [optional] |
| **end_date** | **Time** | Date and time by which results are returned. Results are filtered by transaction creation date.  **Note:**  - It must be an RFC3339 timestamp string. - You can include a time component in your string, for example, &#x60;T23:59:59&#x60; to specify the end of the day. The time zone setting considered is &#x60;UTC&#x60;. If you do not include a time component, a default time value of &#x60;T00:00:00&#x60; (midnight) in &#x60;UTC&#x60; is considered.  | [optional] |
| **page_size** | **Integer** | The number of items in the response. | [optional][default to 50] |
| **skip** | **Integer** | The number of items to skip when paging through large result sets. | [optional] |
| **awaits_activation** | **Boolean** | If &#x60;true&#x60;: Filters results to include only point transactions that have action-based activation and have not expired.  If &#x60;false&#x60;: Returns a &#x60;400&#x60; response.  | [optional] |

### Return type

[**GetLoyaltyProgramTransactions200Response**](GetLoyaltyProgramTransactions200Response.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_loyalty_programs

> <GetLoyaltyPrograms200Response> get_loyalty_programs

List loyalty programs

List the loyalty programs of the account.

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

begin
  # List loyalty programs
  result = api_instance.get_loyalty_programs
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_loyalty_programs: #{e}"
end
```

#### Using the get_loyalty_programs_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<GetLoyaltyPrograms200Response>, Integer, Hash)> get_loyalty_programs_with_http_info

```ruby
begin
  # List loyalty programs
  data, status_code, headers = api_instance.get_loyalty_programs_with_http_info
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <GetLoyaltyPrograms200Response>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_loyalty_programs_with_http_info: #{e}"
end
```

### Parameters

This endpoint does not need any parameter.

### Return type

[**GetLoyaltyPrograms200Response**](GetLoyaltyPrograms200Response.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_loyalty_statistics

> <LoyaltyDashboardData> get_loyalty_statistics(loyalty_program_id)

Get loyalty program statistics

⚠️ Deprecation notice: Support for requests to this endpoint will end soon. To retrieve statistics for a loyalty program, use the [Get statistics for loyalty dashboard](/management-api#tag/Loyalty/operation/getDashboardStatistics) endpoint.  Retrieve the statistics of the specified loyalty program, such as the total active points, pending points, spent points, and expired points. 

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
loyalty_program_id = 789 # Integer | Identifier of the loyalty program. You can get the ID with the [List loyalty programs](https://docs.talon.one/management-api#tag/Loyalty/operation/getLoyaltyPrograms) endpoint. 

begin
  # Get loyalty program statistics
  result = api_instance.get_loyalty_statistics(loyalty_program_id)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_loyalty_statistics: #{e}"
end
```

#### Using the get_loyalty_statistics_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<LoyaltyDashboardData>, Integer, Hash)> get_loyalty_statistics_with_http_info(loyalty_program_id)

```ruby
begin
  # Get loyalty program statistics
  data, status_code, headers = api_instance.get_loyalty_statistics_with_http_info(loyalty_program_id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <LoyaltyDashboardData>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_loyalty_statistics_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **loyalty_program_id** | **Integer** | Identifier of the loyalty program. You can get the ID with the [List loyalty programs](https://docs.talon.one/management-api#tag/Loyalty/operation/getLoyaltyPrograms) endpoint.  |  |

### Return type

[**LoyaltyDashboardData**](LoyaltyDashboardData.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_message_logs

> <MessageLogEntries> get_message_logs(entity_type, opts)

List message log entries

Retrieve all message log entries.

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
entity_type = 'application' # String | The entity type the log is related to. 
opts = {
  message_id: 'message_id_example', # String | Filter results by message ID.
  change_type: 'CampaignEvaluationTreeChanged', # String | Filter results by change type.
  notification_ids: 'notification_ids_example', # String | Filter results by notification ID (include up to 30 values, separated by a comma).
  created_before: Time.parse('2013-10-20T19:20:30+01:00'), # Time | Filter results where request and response times to return entries before parameter value, expected to be an RFC3339 timestamp string. Use UTC time.
  created_after: Time.parse('2013-10-20T19:20:30+01:00'), # Time | Filter results where request and response times to return entries after parameter value, expected to be an RFC3339 timestamp string. Use UTC time.
  cursor: BYTE_ARRAY_DATA_HERE, # String | A specific unique value in the database. If this value is not given, the server fetches results starting with the first record. 
  period: '15m', # String | Filter results by time period. Choose between the available relative time frames. 
  is_successful: true, # Boolean | Indicates whether to return log entries with either successful or unsuccessful HTTP response codes. When set to`true`, only log entries with `2xx` response codes are returned. When set to `false`, only log entries with `4xx` and `5xx` response codes are returned. 
  application_id: 8.14, # Float | Filter results by Application ID.
  campaign_id: 8.14, # Float | Filter results by campaign ID.
  loyalty_program_id: 789, # Integer | Identifier of the loyalty program.
  response_code: 789, # Integer | Filter results by response status code.
  webhook_ids: 'webhook_ids_example' # String | Filter results by webhook ID (include up to 30 values, separated by a comma).
}

begin
  # List message log entries
  result = api_instance.get_message_logs(entity_type, opts)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_message_logs: #{e}"
end
```

#### Using the get_message_logs_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<MessageLogEntries>, Integer, Hash)> get_message_logs_with_http_info(entity_type, opts)

```ruby
begin
  # List message log entries
  data, status_code, headers = api_instance.get_message_logs_with_http_info(entity_type, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <MessageLogEntries>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_message_logs_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **entity_type** | **String** | The entity type the log is related to.  |  |
| **message_id** | **String** | Filter results by message ID. | [optional] |
| **change_type** | **String** | Filter results by change type. | [optional] |
| **notification_ids** | **String** | Filter results by notification ID (include up to 30 values, separated by a comma). | [optional] |
| **created_before** | **Time** | Filter results where request and response times to return entries before parameter value, expected to be an RFC3339 timestamp string. Use UTC time. | [optional] |
| **created_after** | **Time** | Filter results where request and response times to return entries after parameter value, expected to be an RFC3339 timestamp string. Use UTC time. | [optional] |
| **cursor** | **String** | A specific unique value in the database. If this value is not given, the server fetches results starting with the first record.  | [optional] |
| **period** | **String** | Filter results by time period. Choose between the available relative time frames.  | [optional] |
| **is_successful** | **Boolean** | Indicates whether to return log entries with either successful or unsuccessful HTTP response codes. When set to&#x60;true&#x60;, only log entries with &#x60;2xx&#x60; response codes are returned. When set to &#x60;false&#x60;, only log entries with &#x60;4xx&#x60; and &#x60;5xx&#x60; response codes are returned.  | [optional] |
| **application_id** | **Float** | Filter results by Application ID. | [optional] |
| **campaign_id** | **Float** | Filter results by campaign ID. | [optional] |
| **loyalty_program_id** | **Integer** | Identifier of the loyalty program. | [optional] |
| **response_code** | **Integer** | Filter results by response status code. | [optional] |
| **webhook_ids** | **String** | Filter results by webhook ID (include up to 30 values, separated by a comma). | [optional] |

### Return type

[**MessageLogEntries**](MessageLogEntries.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_referrals_without_total_count

> <GetReferralsWithoutTotalCount200Response> get_referrals_without_total_count(application_id, campaign_id, opts)

List referrals

List all referrals of the specified campaign.

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
application_id = 789 # Integer | The ID of the Application. It is displayed in your Talon.One deployment URL.
campaign_id = 789 # Integer | The ID of the campaign. It is displayed in your Talon.One deployment URL.
opts = {
  page_size: 789, # Integer | The number of items in the response.
  skip: 789, # Integer | The number of items to skip when paging through large result sets.
  sort: 'sort_example', # String | The field by which results should be sorted. By default, results are sorted in ascending order. To sort them in descending order, prefix the field name with `-`.  **Note:** You may not be able to use all fields for sorting. This is due to performance limitations. 
  code: 'code_example', # String | Filter results performing case-insensitive matching against the referral code. Both the code and the query are folded to remove all non-alpha-numeric characters.
  created_before: Time.parse('2013-10-20T19:20:30+01:00'), # Time | Filter results comparing the parameter value, expected to be an RFC3339 timestamp string, to the referral creation timestamp. You can use any time zone setting. Talon.One will convert to UTC internally.
  created_after: Time.parse('2013-10-20T19:20:30+01:00'), # Time | Filter results comparing the parameter value, expected to be an RFC3339 timestamp string, to the referral creation timestamp. You can use any time zone setting. Talon.One will convert to UTC internally.
  valid: 'expired', # String | Either \"expired\", \"validNow\", or \"validFuture\". The first option matches referrals in which the expiration date is set and in the past. The second matches referrals in which start date is null or in the past and expiration date is null or in the future, the third matches referrals in which start date is set and in the future. 
  usable: 'true', # String | Either \"true\" or \"false\". If \"true\", only referrals where `usageCounter < usageLimit` will be returned, \"false\" will return only referrals where `usageCounter >= usageLimit`. 
  advocate: 'advocate_example' # String | Filter results by match with a profile ID specified in the referral's AdvocateProfileIntegrationId field.
}

begin
  # List referrals
  result = api_instance.get_referrals_without_total_count(application_id, campaign_id, opts)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_referrals_without_total_count: #{e}"
end
```

#### Using the get_referrals_without_total_count_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<GetReferralsWithoutTotalCount200Response>, Integer, Hash)> get_referrals_without_total_count_with_http_info(application_id, campaign_id, opts)

```ruby
begin
  # List referrals
  data, status_code, headers = api_instance.get_referrals_without_total_count_with_http_info(application_id, campaign_id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <GetReferralsWithoutTotalCount200Response>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_referrals_without_total_count_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **application_id** | **Integer** | The ID of the Application. It is displayed in your Talon.One deployment URL. |  |
| **campaign_id** | **Integer** | The ID of the campaign. It is displayed in your Talon.One deployment URL. |  |
| **page_size** | **Integer** | The number of items in the response. | [optional][default to 1000] |
| **skip** | **Integer** | The number of items to skip when paging through large result sets. | [optional] |
| **sort** | **String** | The field by which results should be sorted. By default, results are sorted in ascending order. To sort them in descending order, prefix the field name with &#x60;-&#x60;.  **Note:** You may not be able to use all fields for sorting. This is due to performance limitations.  | [optional] |
| **code** | **String** | Filter results performing case-insensitive matching against the referral code. Both the code and the query are folded to remove all non-alpha-numeric characters. | [optional] |
| **created_before** | **Time** | Filter results comparing the parameter value, expected to be an RFC3339 timestamp string, to the referral creation timestamp. You can use any time zone setting. Talon.One will convert to UTC internally. | [optional] |
| **created_after** | **Time** | Filter results comparing the parameter value, expected to be an RFC3339 timestamp string, to the referral creation timestamp. You can use any time zone setting. Talon.One will convert to UTC internally. | [optional] |
| **valid** | **String** | Either \&quot;expired\&quot;, \&quot;validNow\&quot;, or \&quot;validFuture\&quot;. The first option matches referrals in which the expiration date is set and in the past. The second matches referrals in which start date is null or in the past and expiration date is null or in the future, the third matches referrals in which start date is set and in the future.  | [optional] |
| **usable** | **String** | Either \&quot;true\&quot; or \&quot;false\&quot;. If \&quot;true\&quot;, only referrals where &#x60;usageCounter &lt; usageLimit&#x60; will be returned, \&quot;false\&quot; will return only referrals where &#x60;usageCounter &gt;&#x3D; usageLimit&#x60;.  | [optional] |
| **advocate** | **String** | Filter results by match with a profile ID specified in the referral&#39;s AdvocateProfileIntegrationId field. | [optional] |

### Return type

[**GetReferralsWithoutTotalCount200Response**](GetReferralsWithoutTotalCount200Response.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_role_v2

> <RoleV2> get_role_v2(role_id)

Get role

Get the details of a specific role. To see all the roles, use the [List roles](/management-api#tag/Roles/operation/listAllRolesV2) endpoint. 

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
role_id = 789 # Integer | The ID of role.  **Note**: To find the ID of a role, use the [List roles](/management-api#tag/Roles/operation/listAllRolesV2) endpoint. 

begin
  # Get role
  result = api_instance.get_role_v2(role_id)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_role_v2: #{e}"
end
```

#### Using the get_role_v2_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<RoleV2>, Integer, Hash)> get_role_v2_with_http_info(role_id)

```ruby
begin
  # Get role
  data, status_code, headers = api_instance.get_role_v2_with_http_info(role_id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <RoleV2>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_role_v2_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **role_id** | **Integer** | The ID of role.  **Note**: To find the ID of a role, use the [List roles](/management-api#tag/Roles/operation/listAllRolesV2) endpoint.  |  |

### Return type

[**RoleV2**](RoleV2.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_ruleset

> <Ruleset> get_ruleset(application_id, campaign_id, ruleset_id)

Get ruleset

Retrieve the specified ruleset.

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
application_id = 789 # Integer | The ID of the Application. It is displayed in your Talon.One deployment URL.
campaign_id = 789 # Integer | The ID of the campaign. It is displayed in your Talon.One deployment URL.
ruleset_id = 789 # Integer | The ID of the ruleset.

begin
  # Get ruleset
  result = api_instance.get_ruleset(application_id, campaign_id, ruleset_id)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_ruleset: #{e}"
end
```

#### Using the get_ruleset_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<Ruleset>, Integer, Hash)> get_ruleset_with_http_info(application_id, campaign_id, ruleset_id)

```ruby
begin
  # Get ruleset
  data, status_code, headers = api_instance.get_ruleset_with_http_info(application_id, campaign_id, ruleset_id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <Ruleset>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_ruleset_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **application_id** | **Integer** | The ID of the Application. It is displayed in your Talon.One deployment URL. |  |
| **campaign_id** | **Integer** | The ID of the campaign. It is displayed in your Talon.One deployment URL. |  |
| **ruleset_id** | **Integer** | The ID of the ruleset. |  |

### Return type

[**Ruleset**](Ruleset.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_rulesets

> <GetRulesets200Response> get_rulesets(application_id, campaign_id, opts)

List campaign rulesets

List all rulesets of this campaign. A ruleset is a revision of the rules of a campaign. **Important:** The response also includes deleted rules. You should only consider the latest revision of the returned rulesets. 

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
application_id = 789 # Integer | The ID of the Application. It is displayed in your Talon.One deployment URL.
campaign_id = 789 # Integer | The ID of the campaign. It is displayed in your Talon.One deployment URL.
opts = {
  page_size: 789, # Integer | The number of items in the response.
  skip: 789, # Integer | The number of items to skip when paging through large result sets.
  sort: 'sort_example' # String | The field by which results should be sorted. By default, results are sorted in ascending order. To sort them in descending order, prefix the field name with `-`.  **Note:** You may not be able to use all fields for sorting. This is due to performance limitations. 
}

begin
  # List campaign rulesets
  result = api_instance.get_rulesets(application_id, campaign_id, opts)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_rulesets: #{e}"
end
```

#### Using the get_rulesets_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<GetRulesets200Response>, Integer, Hash)> get_rulesets_with_http_info(application_id, campaign_id, opts)

```ruby
begin
  # List campaign rulesets
  data, status_code, headers = api_instance.get_rulesets_with_http_info(application_id, campaign_id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <GetRulesets200Response>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_rulesets_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **application_id** | **Integer** | The ID of the Application. It is displayed in your Talon.One deployment URL. |  |
| **campaign_id** | **Integer** | The ID of the campaign. It is displayed in your Talon.One deployment URL. |  |
| **page_size** | **Integer** | The number of items in the response. | [optional][default to 1000] |
| **skip** | **Integer** | The number of items to skip when paging through large result sets. | [optional] |
| **sort** | **String** | The field by which results should be sorted. By default, results are sorted in ascending order. To sort them in descending order, prefix the field name with &#x60;-&#x60;.  **Note:** You may not be able to use all fields for sorting. This is due to performance limitations.  | [optional] |

### Return type

[**GetRulesets200Response**](GetRulesets200Response.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_store

> <Store> get_store(application_id, store_id)

Get store

Get store details for a specific store ID.

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
application_id = 789 # Integer | The ID of the Application. It is displayed in your Talon.One deployment URL.
store_id = 'store_id_example' # String | The ID of the store. You can get this ID with the [List stores](#tag/Stores/operation/listStores) endpoint. 

begin
  # Get store
  result = api_instance.get_store(application_id, store_id)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_store: #{e}"
end
```

#### Using the get_store_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<Store>, Integer, Hash)> get_store_with_http_info(application_id, store_id)

```ruby
begin
  # Get store
  data, status_code, headers = api_instance.get_store_with_http_info(application_id, store_id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <Store>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_store_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **application_id** | **Integer** | The ID of the Application. It is displayed in your Talon.One deployment URL. |  |
| **store_id** | **String** | The ID of the store. You can get this ID with the [List stores](#tag/Stores/operation/listStores) endpoint.  |  |

### Return type

[**Store**](Store.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_user

> <User> get_user(user_id)

Get user

Retrieve the data (including an invitation code) for a user. Non-admin users can only get their own profile. 

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
user_id = 789 # Integer | The ID of the user.

begin
  # Get user
  result = api_instance.get_user(user_id)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_user: #{e}"
end
```

#### Using the get_user_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<User>, Integer, Hash)> get_user_with_http_info(user_id)

```ruby
begin
  # Get user
  data, status_code, headers = api_instance.get_user_with_http_info(user_id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <User>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_user_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **user_id** | **Integer** | The ID of the user. |  |

### Return type

[**User**](User.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_users

> <GetUsers200Response> get_users(opts)

List users in account

Retrieve all users in your account. 

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
opts = {
  page_size: 789, # Integer | The number of items in the response.
  skip: 789, # Integer | The number of items to skip when paging through large result sets.
  sort: 'sort_example' # String | The field by which results should be sorted. By default, results are sorted in ascending order. To sort them in descending order, prefix the field name with `-`.  **Note:** You may not be able to use all fields for sorting. This is due to performance limitations. 
}

begin
  # List users in account
  result = api_instance.get_users(opts)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_users: #{e}"
end
```

#### Using the get_users_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<GetUsers200Response>, Integer, Hash)> get_users_with_http_info(opts)

```ruby
begin
  # List users in account
  data, status_code, headers = api_instance.get_users_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <GetUsers200Response>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_users_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **page_size** | **Integer** | The number of items in the response. | [optional][default to 1000] |
| **skip** | **Integer** | The number of items to skip when paging through large result sets. | [optional] |
| **sort** | **String** | The field by which results should be sorted. By default, results are sorted in ascending order. To sort them in descending order, prefix the field name with &#x60;-&#x60;.  **Note:** You may not be able to use all fields for sorting. This is due to performance limitations.  | [optional] |

### Return type

[**GetUsers200Response**](GetUsers200Response.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_webhook

> <Webhook> get_webhook(webhook_id)

Get webhook

Returns a webhook by its id.

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
webhook_id = 789 # Integer | The ID of the webhook. You can find the ID in the Campaign Manager's URL when you display the details of the webhook in **Account** > **Webhooks**. 

begin
  # Get webhook
  result = api_instance.get_webhook(webhook_id)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_webhook: #{e}"
end
```

#### Using the get_webhook_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<Webhook>, Integer, Hash)> get_webhook_with_http_info(webhook_id)

```ruby
begin
  # Get webhook
  data, status_code, headers = api_instance.get_webhook_with_http_info(webhook_id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <Webhook>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_webhook_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **webhook_id** | **Integer** | The ID of the webhook. You can find the ID in the Campaign Manager&#39;s URL when you display the details of the webhook in **Account** &gt; **Webhooks**.  |  |

### Return type

[**Webhook**](Webhook.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## get_webhooks

> <GetWebhooks200Response> get_webhooks(opts)

List webhooks

List all webhooks.

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
opts = {
  application_ids: 'application_ids_example', # String | Checks if the given catalog or its attributes are referenced in the specified Application ID.  **Note**: If no Application ID is provided, we check for all connected Applications. 
  sort: 'sort_example', # String | The field by which results should be sorted. By default, results are sorted in ascending order. To sort them in descending order, prefix the field name with `-`.  **Note:** You may not be able to use all fields for sorting. This is due to performance limitations. 
  page_size: 789, # Integer | The number of items in the response.
  skip: 789, # Integer | The number of items to skip when paging through large result sets.
  creation_type: 'templateWebhooks', # String | Filter results by creation type.
  visibility: 'visible', # String | Filter results by visibility.
  outgoing_integrations_type_id: 789, # Integer | Filter results by outgoing integration type ID.
  title: 'title_example' # String | Filter results performing case-insensitive matching against the webhook title.
}

begin
  # List webhooks
  result = api_instance.get_webhooks(opts)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_webhooks: #{e}"
end
```

#### Using the get_webhooks_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<GetWebhooks200Response>, Integer, Hash)> get_webhooks_with_http_info(opts)

```ruby
begin
  # List webhooks
  data, status_code, headers = api_instance.get_webhooks_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <GetWebhooks200Response>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->get_webhooks_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **application_ids** | **String** | Checks if the given catalog or its attributes are referenced in the specified Application ID.  **Note**: If no Application ID is provided, we check for all connected Applications.  | [optional] |
| **sort** | **String** | The field by which results should be sorted. By default, results are sorted in ascending order. To sort them in descending order, prefix the field name with &#x60;-&#x60;.  **Note:** You may not be able to use all fields for sorting. This is due to performance limitations.  | [optional] |
| **page_size** | **Integer** | The number of items in the response. | [optional][default to 1000] |
| **skip** | **Integer** | The number of items to skip when paging through large result sets. | [optional] |
| **creation_type** | **String** | Filter results by creation type. | [optional] |
| **visibility** | **String** | Filter results by visibility. | [optional] |
| **outgoing_integrations_type_id** | **Integer** | Filter results by outgoing integration type ID. | [optional] |
| **title** | **String** | Filter results performing case-insensitive matching against the webhook title. | [optional] |

### Return type

[**GetWebhooks200Response**](GetWebhooks200Response.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## import_account_collection

> <Import> import_account_collection(collection_id, opts)

Import data into existing account-level collection

Upload a CSV file containing the collection of string values that should be attached as payload for collection. The file should be sent as multipart data.  The import **replaces** the initial content of the collection.  The CSV file **must** only contain the following column:  - `item`: the values in your collection.  A collection is limited to 500,000 items.  Example:  ``` item Addidas Nike Asics ```  **Note:** Before sending a request to this endpoint, ensure the data in the CSV to import is different from the data currently stored in the collection. 

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
collection_id = 789 # Integer | The ID of the collection. You can get it with the [List collections in account](#operation/listAccountCollections) endpoint.
opts = {
  up_file: 'up_file_example' # String | The file containing the data that is being imported.
}

begin
  # Import data into existing account-level collection
  result = api_instance.import_account_collection(collection_id, opts)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->import_account_collection: #{e}"
end
```

#### Using the import_account_collection_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<Import>, Integer, Hash)> import_account_collection_with_http_info(collection_id, opts)

```ruby
begin
  # Import data into existing account-level collection
  data, status_code, headers = api_instance.import_account_collection_with_http_info(collection_id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <Import>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->import_account_collection_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **collection_id** | **Integer** | The ID of the collection. You can get it with the [List collections in account](#operation/listAccountCollections) endpoint. |  |
| **up_file** | **String** | The file containing the data that is being imported. | [optional] |

### Return type

[**Import**](Import.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: multipart/form-data
- **Accept**: application/json


## import_allowed_list

> <Import> import_allowed_list(attribute_id, opts)

Import allowed values for attribute

Upload a CSV file containing a list of [picklist values](https://docs.talon.one/docs/product/account/dev-tools/managing-attributes#picklist-values) for the specified attribute.  The file should be sent as multipart data.  The import **replaces** the previous list of allowed values for this attribute, if any.  The CSV file **must** only contain the following column: - `item` (required): the values in your allowed list, for example a list of SKU's.  An allowed list is limited to 500,000 items.  Example:  ```text item CS-VG-04032021-UP-50D-10 CS-DV-04042021-UP-49D-12 CS-DG-02082021-UP-50G-07 ``` 

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
attribute_id = 789 # Integer | The ID of the attribute. You can find the ID in the Campaign Manager's URL when you display the details of an attribute in **Account** > **Tools** > **Attributes**.
opts = {
  up_file: 'up_file_example' # String | The file containing the data that is being imported.
}

begin
  # Import allowed values for attribute
  result = api_instance.import_allowed_list(attribute_id, opts)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->import_allowed_list: #{e}"
end
```

#### Using the import_allowed_list_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<Import>, Integer, Hash)> import_allowed_list_with_http_info(attribute_id, opts)

```ruby
begin
  # Import allowed values for attribute
  data, status_code, headers = api_instance.import_allowed_list_with_http_info(attribute_id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <Import>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->import_allowed_list_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **attribute_id** | **Integer** | The ID of the attribute. You can find the ID in the Campaign Manager&#39;s URL when you display the details of an attribute in **Account** &gt; **Tools** &gt; **Attributes**. |  |
| **up_file** | **String** | The file containing the data that is being imported. | [optional] |

### Return type

[**Import**](Import.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: multipart/form-data
- **Accept**: application/json


## import_audiences_memberships

> <Import> import_audiences_memberships(audience_id, opts)

Import audience members

Upload a CSV file containing the integration IDs of the members you want to add to an audience.  The file should be sent as multipart data and should contain only the following column (required): - `profileintegrationid`: The integration ID of the customer profile.  The import **replaces** the previous list of audience members.  **Note:** We recommend limiting your file size to 500MB.  Example:  ```text profileintegrationid charles alexa ``` 

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
audience_id = 789 # Integer | The ID of the audience.
opts = {
  up_file: 'up_file_example' # String | The file containing the data that is being imported.
}

begin
  # Import audience members
  result = api_instance.import_audiences_memberships(audience_id, opts)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->import_audiences_memberships: #{e}"
end
```

#### Using the import_audiences_memberships_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<Import>, Integer, Hash)> import_audiences_memberships_with_http_info(audience_id, opts)

```ruby
begin
  # Import audience members
  data, status_code, headers = api_instance.import_audiences_memberships_with_http_info(audience_id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <Import>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->import_audiences_memberships_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **audience_id** | **Integer** | The ID of the audience. |  |
| **up_file** | **String** | The file containing the data that is being imported. | [optional] |

### Return type

[**Import**](Import.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: multipart/form-data
- **Accept**: application/json


## import_campaign_store_budget

> <Import> import_campaign_store_budget(application_id, campaign_id, opts)

Import campaign store budgets

Upload a CSV file containing store budgets for a given campaign.  Send the file as multipart data.  The CSV file **must** only contain the following columns: - `store_integration_id`: The identifier of the store. - `limit`: The budget limit for the store.  The import **replaces** the previous list of store budgets. 

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
application_id = 789 # Integer | The ID of the Application. It is displayed in your Talon.One deployment URL.
campaign_id = 789 # Integer | The ID of the campaign. It is displayed in your Talon.One deployment URL.
opts = {
  action: 'setDiscount', # String | The action that this budget is limiting.
  period: 'overall', # String | The period to which the limit applies.  **Note**: For budgets with no period, set this to `overall`. 
  up_file: 'up_file_example' # String | The file containing the data that is being imported.
}

begin
  # Import campaign store budgets
  result = api_instance.import_campaign_store_budget(application_id, campaign_id, opts)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->import_campaign_store_budget: #{e}"
end
```

#### Using the import_campaign_store_budget_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<Import>, Integer, Hash)> import_campaign_store_budget_with_http_info(application_id, campaign_id, opts)

```ruby
begin
  # Import campaign store budgets
  data, status_code, headers = api_instance.import_campaign_store_budget_with_http_info(application_id, campaign_id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <Import>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->import_campaign_store_budget_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **application_id** | **Integer** | The ID of the Application. It is displayed in your Talon.One deployment URL. |  |
| **campaign_id** | **Integer** | The ID of the campaign. It is displayed in your Talon.One deployment URL. |  |
| **action** | **String** | The action that this budget is limiting. | [optional] |
| **period** | **String** | The period to which the limit applies.  **Note**: For budgets with no period, set this to &#x60;overall&#x60;.  | [optional] |
| **up_file** | **String** | The file containing the data that is being imported. | [optional] |

### Return type

[**Import**](Import.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: multipart/form-data
- **Accept**: application/json


## import_campaign_stores

> <Import> import_campaign_stores(application_id, campaign_id, opts)

Import stores

Upload a CSV file containing the stores you want to link to a specific campaign.  Send the file as multipart data.  The CSV file **must** only contain the following column: - `store_integration_id`: The identifier of the store.  The import **replaces** the previous list of stores linked to the campaign. 

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
application_id = 789 # Integer | The ID of the Application. It is displayed in your Talon.One deployment URL.
campaign_id = 789 # Integer | The ID of the campaign. It is displayed in your Talon.One deployment URL.
opts = {
  up_file: 'up_file_example' # String | The file containing the data that is being imported.
}

begin
  # Import stores
  result = api_instance.import_campaign_stores(application_id, campaign_id, opts)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->import_campaign_stores: #{e}"
end
```

#### Using the import_campaign_stores_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<Import>, Integer, Hash)> import_campaign_stores_with_http_info(application_id, campaign_id, opts)

```ruby
begin
  # Import stores
  data, status_code, headers = api_instance.import_campaign_stores_with_http_info(application_id, campaign_id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <Import>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->import_campaign_stores_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **application_id** | **Integer** | The ID of the Application. It is displayed in your Talon.One deployment URL. |  |
| **campaign_id** | **Integer** | The ID of the campaign. It is displayed in your Talon.One deployment URL. |  |
| **up_file** | **String** | The file containing the data that is being imported. | [optional] |

### Return type

[**Import**](Import.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: multipart/form-data
- **Accept**: application/json


## import_collection

> <Import> import_collection(application_id, campaign_id, collection_id, opts)

Import data into existing campaign-level collection

Upload a CSV file containing the collection of string values that should be attached as payload for collection. The file should be sent as multipart data.  The import **replaces** the initial content of the collection.  The CSV file **must** only contain the following column:  - `item`: the values in your collection.  A collection is limited to 500,000 items.  Example:  ``` item Addidas Nike Asics ```  **Note:** Before sending a request to this endpoint, ensure the data in the CSV to import is different from the data currently stored in the collection. 

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
application_id = 789 # Integer | The ID of the Application. It is displayed in your Talon.One deployment URL.
campaign_id = 789 # Integer | The ID of the campaign. It is displayed in your Talon.One deployment URL.
collection_id = 789 # Integer | The ID of the collection. You can get it with the [List collections in Application](#operation/listCollectionsInApplication) endpoint.
opts = {
  up_file: 'up_file_example' # String | The file containing the data that is being imported.
}

begin
  # Import data into existing campaign-level collection
  result = api_instance.import_collection(application_id, campaign_id, collection_id, opts)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->import_collection: #{e}"
end
```

#### Using the import_collection_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<Import>, Integer, Hash)> import_collection_with_http_info(application_id, campaign_id, collection_id, opts)

```ruby
begin
  # Import data into existing campaign-level collection
  data, status_code, headers = api_instance.import_collection_with_http_info(application_id, campaign_id, collection_id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <Import>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->import_collection_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **application_id** | **Integer** | The ID of the Application. It is displayed in your Talon.One deployment URL. |  |
| **campaign_id** | **Integer** | The ID of the campaign. It is displayed in your Talon.One deployment URL. |  |
| **collection_id** | **Integer** | The ID of the collection. You can get it with the [List collections in Application](#operation/listCollectionsInApplication) endpoint. |  |
| **up_file** | **String** | The file containing the data that is being imported. | [optional] |

### Return type

[**Import**](Import.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: multipart/form-data
- **Accept**: application/json


## import_coupons

> <Import> import_coupons(application_id, campaign_id, opts)

Import coupons

Upload a CSV file containing the coupons that should be created. The file should be sent as multipart data.  The CSV file contains the following columns:  - `value` (required): The coupon code. - `expirydate`: The end date in RFC3339 of the code redemption period. - `startdate`: The start date in RFC3339 of the code redemption period. - `recipientintegrationid`: The integration ID of the recipient of the coupon.   Only the customer with this integration ID can redeem this code. Available only for personal codes. - `limitval`: The maximum number of redemptions of this code. For unlimited redemptions, use `0`. Defaults to `1` when not provided. - `discountlimit`: The total discount value that the code can give. This is typically used to represent a gift card value. - `attributes`: A JSON object describing _custom_ coupon attribute names and their values, enclosed with double quotation marks.    For example, if you created a [custom attribute](https://docs.talon.one/docs/dev/concepts/attributes#custom-attributes)   called `category` associated with the coupon entity, the object in the CSV file, when opened in a text editor, must be: `\"{\"category\": \"10_off\"}\"`.  You can use the time zone of your choice. It is converted to UTC internally by Talon.One.  **Note:** We recommend limiting your file size to 500MB.  **Example:**  ```text \"value\",\"expirydate\",\"startdate\",\"recipientintegrationid\",\"limitval\",\"attributes\",\"discountlimit\" COUP1,2018-07-01T04:00:00Z,2018-05-01T04:00:00Z,cust123,1,\"{\"\"Category\"\": \"\"10_off\"\"}\",2.4 ```  Once imported, you can find the `batchId` in the Campaign Manager or by using [List coupons](#tag/Coupons/operation/getCouponsWithoutTotalCount). 

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
application_id = 789 # Integer | The ID of the Application. It is displayed in your Talon.One deployment URL.
campaign_id = 789 # Integer | The ID of the campaign. It is displayed in your Talon.One deployment URL.
opts = {
  skip_duplicates: true, # Boolean | An indicator of whether to skip duplicate coupon values instead of causing an error. Duplicate values are ignored when `skipDuplicates=true`. 
  up_file: 'up_file_example' # String | The file containing the data that is being imported.
}

begin
  # Import coupons
  result = api_instance.import_coupons(application_id, campaign_id, opts)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->import_coupons: #{e}"
end
```

#### Using the import_coupons_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<Import>, Integer, Hash)> import_coupons_with_http_info(application_id, campaign_id, opts)

```ruby
begin
  # Import coupons
  data, status_code, headers = api_instance.import_coupons_with_http_info(application_id, campaign_id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <Import>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->import_coupons_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **application_id** | **Integer** | The ID of the Application. It is displayed in your Talon.One deployment URL. |  |
| **campaign_id** | **Integer** | The ID of the campaign. It is displayed in your Talon.One deployment URL. |  |
| **skip_duplicates** | **Boolean** | An indicator of whether to skip duplicate coupon values instead of causing an error. Duplicate values are ignored when &#x60;skipDuplicates&#x3D;true&#x60;.  | [optional] |
| **up_file** | **String** | The file containing the data that is being imported. | [optional] |

### Return type

[**Import**](Import.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: multipart/form-data
- **Accept**: application/json


## import_loyalty_cards

> <Import> import_loyalty_cards(loyalty_program_id, opts)

Import loyalty cards

Upload a CSV file containing the loyalty cards that you want to use in your card-based loyalty program. Send the file as multipart data.  It contains the following columns for each card:  - `identifier` (required): The alphanumeric identifier of the loyalty card. - `state` (required): The state of the loyalty card. It can be `active` or `inactive`. - `customerprofileids` (optional): An array of strings representing the identifiers of the customer profiles linked to the loyalty card. The identifiers should be separated with a semicolon (;).  **Note:** We recommend limiting your file size to 500MB.  **Example:**  ```csv identifier,state,customerprofileids 123-456-789AT,active,Alexa001;UserA ``` 

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
loyalty_program_id = 789 # Integer | Identifier of the card-based loyalty program containing the loyalty card. You can get the ID with the [List loyalty programs](https://docs.talon.one/management-api#tag/Loyalty/operation/getLoyaltyPrograms) endpoint. 
opts = {
  up_file: 'up_file_example' # String | The file containing the data that is being imported.
}

begin
  # Import loyalty cards
  result = api_instance.import_loyalty_cards(loyalty_program_id, opts)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->import_loyalty_cards: #{e}"
end
```

#### Using the import_loyalty_cards_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<Import>, Integer, Hash)> import_loyalty_cards_with_http_info(loyalty_program_id, opts)

```ruby
begin
  # Import loyalty cards
  data, status_code, headers = api_instance.import_loyalty_cards_with_http_info(loyalty_program_id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <Import>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->import_loyalty_cards_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **loyalty_program_id** | **Integer** | Identifier of the card-based loyalty program containing the loyalty card. You can get the ID with the [List loyalty programs](https://docs.talon.one/management-api#tag/Loyalty/operation/getLoyaltyPrograms) endpoint.  |  |
| **up_file** | **String** | The file containing the data that is being imported. | [optional] |

### Return type

[**Import**](Import.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: multipart/form-data
- **Accept**: application/json


## import_loyalty_customers_tiers

> <Import> import_loyalty_customers_tiers(loyalty_program_id, opts)

Import customers into loyalty tiers

Upload a CSV file containing existing customers to be assigned to existing tiers. Send the file as multipart data.  **Important:** This endpoint only works with loyalty programs with advanced tiers (with expiration and downgrade policy) feature enabled.  The CSV file should contain the following columns: - `subledgerid` (optional): The ID of the subledger. If this field is empty, the main ledger will be used. - `customerprofileid`: The integration ID of the customer profile to whom the tier should be assigned. - `tiername`: The name of an existing tier to assign to the customer. - `expirydate`: The expiration date of the tier when the tier is reevaluated. It should be a future date.  About customer assignment to a tier: - If the customer isn't already in a tier, the customer is assigned to the specified tier during the tier import. - If the customer is already in the tier that's specified in the CSV file, only the expiration date is updated.  **Note:** We recommend not using this endpoint to update the tier of a customer. To update a customer's tier, you can [add](/management-api#tag/Loyalty/operation/addLoyaltyPoints) or [deduct](/management-api#tag/Loyalty/operation/removeLoyaltyPoints) their loyalty points.  You can use the time zone of your choice. It is converted to UTC internally by Talon.One.  **Note:** We recommend limiting your file size to 500MB.  **Example:** ```csv subledgerid,customerprofileid,tiername,expirydate SUB1,alexa,Gold,2024-03-21T07:32:14Z ,george,Silver,2025-04-16T21:12:37Z SUB2,avocado,Bronze,2026-05-03T11:47:01Z ``` 

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
loyalty_program_id = 789 # Integer | Identifier of the loyalty program. You can get the ID with the [List loyalty programs](https://docs.talon.one/management-api#tag/Loyalty/operation/getLoyaltyPrograms) endpoint. 
opts = {
  up_file: 'up_file_example' # String | The file containing the data that is being imported.
}

begin
  # Import customers into loyalty tiers
  result = api_instance.import_loyalty_customers_tiers(loyalty_program_id, opts)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->import_loyalty_customers_tiers: #{e}"
end
```

#### Using the import_loyalty_customers_tiers_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<Import>, Integer, Hash)> import_loyalty_customers_tiers_with_http_info(loyalty_program_id, opts)

```ruby
begin
  # Import customers into loyalty tiers
  data, status_code, headers = api_instance.import_loyalty_customers_tiers_with_http_info(loyalty_program_id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <Import>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->import_loyalty_customers_tiers_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **loyalty_program_id** | **Integer** | Identifier of the loyalty program. You can get the ID with the [List loyalty programs](https://docs.talon.one/management-api#tag/Loyalty/operation/getLoyaltyPrograms) endpoint.  |  |
| **up_file** | **String** | The file containing the data that is being imported. | [optional] |

### Return type

[**Import**](Import.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: multipart/form-data
- **Accept**: application/json


## import_loyalty_points

> <Import> import_loyalty_points(loyalty_program_id, opts)

Import loyalty points

Upload a CSV file containing the loyalty points you want to import into a given loyalty program. Send the file as multipart data.  Depending on the type of loyalty program, you can import points into a given customer profile or loyalty card.  The CSV file contains the following columns:  - `customerprofileid` (optional): For profile-based loyalty programs, the integration ID of the customer profile where the loyalty points are imported.    **Note**: If the customer profile does not exist, it will be created. The profile will not be visible in any Application   until a session or profile update is received for that profile. - `identifier` (optional): For card-based loyalty programs, the identifier of the loyalty card where the loyalty points are imported. - `amount`: The amount of points to award to the customer profile. - `startdate` (optional): The earliest date when the points can be redeemed. The points are `active` from this date until the expiration date.    This parameter accepts one of the following values:   - A timestamp string in RFC3339 format.   - `immediate`   - `on_action`      **Note**:   Empty or missing values default to `immediate`. - `expirydate` (optional): The latest date when the points can be redeemed. The points are `expired` after this date.    **Note**: It must be an RFC3339 timestamp string or string `unlimited`. Empty or missing values are considered `unlimited`.      If passed, `validityDuration` should be omitted. - `validityDuration` (optional): The duration for which the points remain active, relative to the    activation date.    The time format is an **integer** followed by one letter indicating the time unit.     Examples: `30s`, `40m`, `1h`, `5D`, `7W`, `10M`, `15Y`.     Available units:     - `s`: seconds   - `m`: minutes   - `h`: hours   - `D`: days   - `W`: weeks   - `M`: months   - `Y`: years     You can round certain units up or down:    - `_D` for rounding down days only. Signifies the start of the day.   - `_U` for rounding up days, weeks, months and years. Signifies the end of   the day, week, month or year.    If passed, `expirydate` should be omitted. - `subledgerid` (optional): The ID of the subledger that should received the points. - `reason` (optional): The reason why these points are awarded.  You can use the time zone of your choice. It is converted to UTC internally by Talon.One.  **Note:** For existing customer profiles and loyalty cards, the imported points are added to any previous active or pending points, depending on the value provided for `startdate`. If `startdate` matches the current date, the imported points are _active_. If it is later, the points are _pending_ until the date provided for `startdate` is reached.  **Note:** We recommend limiting your file size to 500MB.  **Example for profile-based programs:**  ```text customerprofileid,amount,startdate,expirydate,subledgerid,reason URNGV8294NV,100,2009-11-10T23:00:00Z,2009-11-11T23:00:00Z,subledger1,appeasement ```  **Example for card-based programs:**  ```text identifier,amount,startdate,expirydate,subledgerid,reason summer-loyalty-card-0543,100,2009-11-10T23:00:00Z,2009-11-11T23:00:00Z,subledger1,appeasement ``` 

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
loyalty_program_id = 789 # Integer | Identifier of the loyalty program. You can get the ID with the [List loyalty programs](https://docs.talon.one/management-api#tag/Loyalty/operation/getLoyaltyPrograms) endpoint. 
opts = {
  notifications_enabled: true, # Boolean | Indicates whether the points import triggers notifications about its effects. For example, a notification is sent if the import upgrades a customer's tier or offsets their negative points balance.  This parameter is optional and defaults to `true`. 
  up_file: 'up_file_example' # String | The file containing the data that is being imported.
}

begin
  # Import loyalty points
  result = api_instance.import_loyalty_points(loyalty_program_id, opts)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->import_loyalty_points: #{e}"
end
```

#### Using the import_loyalty_points_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<Import>, Integer, Hash)> import_loyalty_points_with_http_info(loyalty_program_id, opts)

```ruby
begin
  # Import loyalty points
  data, status_code, headers = api_instance.import_loyalty_points_with_http_info(loyalty_program_id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <Import>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->import_loyalty_points_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **loyalty_program_id** | **Integer** | Identifier of the loyalty program. You can get the ID with the [List loyalty programs](https://docs.talon.one/management-api#tag/Loyalty/operation/getLoyaltyPrograms) endpoint.  |  |
| **notifications_enabled** | **Boolean** | Indicates whether the points import triggers notifications about its effects. For example, a notification is sent if the import upgrades a customer&#39;s tier or offsets their negative points balance.  This parameter is optional and defaults to &#x60;true&#x60;.  | [optional] |
| **up_file** | **String** | The file containing the data that is being imported. | [optional] |

### Return type

[**Import**](Import.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: multipart/form-data
- **Accept**: application/json


## import_pool_giveaways

> <Import> import_pool_giveaways(pool_id, opts)

Import giveaway codes into a giveaway pool

Upload a CSV file containing the giveaway codes that should be created. Send the file as multipart data.  The CSV file contains the following columns: - `code` (required): The code of your giveaway, for instance, a gift card redemption code. - `startdate`:  The start date in RFC3339 of the code redemption period. - `enddate`: The last date in RFC3339 of the code redemption period. - `attributes`: A JSON object describing _custom_ giveaway attribute names and their values, enclosed with double quotation marks.    For example, if you created a [custom attribute](https://docs.talon.one/docs/dev/concepts/attributes#custom-attributes)   called `provider` associated with the giveaway entity, the object in the CSV file, when opened in a text editor, must be: `\"{\"provider\": \"myPartnerCompany\"}\"`.  The `startdate` and `enddate` have nothing to do with the _validity_ of the codes. They are only used by the Rule Engine to award the codes or not. You can use the time zone setting of your choice. The values are converted to UTC internally by Talon.One.  **Note:**  - We recommend limiting your file size to 500MB. - You can import the same code multiple times. Duplicate codes are treated and distributed to customers as unique codes.  **Example:**  ```text code,startdate,enddate,attributes GIVEAWAY1,2020-11-10T23:00:00Z,2022-11-11T23:00:00Z,\"{\"\"provider\"\": \"\"Amazon\"\"}\" GIVEAWAY2,2020-11-10T23:00:00Z,2022-11-11T23:00:00Z,\"{\"\"provider\"\": \"\"Amazon\"\"}\" GIVEAWAY3,2021-01-10T23:00:00Z,2022-11-11T23:00:00Z,\"{\"\"provider\"\": \"\"Aliexpress\"\"}\" ``` 

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
pool_id = 789 # Integer | The ID of the pool. You can find it in the Campaign Manager, in the **Giveaways** section.
opts = {
  up_file: 'up_file_example' # String | The file containing the data that is being imported.
}

begin
  # Import giveaway codes into a giveaway pool
  result = api_instance.import_pool_giveaways(pool_id, opts)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->import_pool_giveaways: #{e}"
end
```

#### Using the import_pool_giveaways_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<Import>, Integer, Hash)> import_pool_giveaways_with_http_info(pool_id, opts)

```ruby
begin
  # Import giveaway codes into a giveaway pool
  data, status_code, headers = api_instance.import_pool_giveaways_with_http_info(pool_id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <Import>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->import_pool_giveaways_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **pool_id** | **Integer** | The ID of the pool. You can find it in the Campaign Manager, in the **Giveaways** section. |  |
| **up_file** | **String** | The file containing the data that is being imported. | [optional] |

### Return type

[**Import**](Import.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: multipart/form-data
- **Accept**: application/json


## import_referrals

> <Import> import_referrals(application_id, campaign_id, opts)

Import referrals

Upload a CSV file containing the referrals that should be created. The file should be sent as multipart data.  The CSV file contains the following columns:  - `code` (required): The referral code. - `advocateprofileintegrationid` (required): The profile ID of the advocate. - `startdate`: The start date in RFC3339 of the code redemption period. - `expirydate`: The end date in RFC3339 of the code redemption period. - `limitval`: The maximum number of redemptions of this code. Defaults to `1` when left blank. - `attributes`: A JSON object describing _custom_ referral attribute names and their values, enclosed with double quotation marks.    For example, if you created a [custom attribute](https://docs.talon.one/docs/dev/concepts/attributes#custom-attributes)   called `category` associated with the referral entity, the object in the CSV file, when opened in a text editor, must be: `\"{\"category\": \"10_off\"}\"`.  You can use the time zone of your choice. It is converted to UTC internally by Talon.One.  **Important:** When you import a CSV file with referrals, a [customer profile](https://docs.talon.one/docs/dev/concepts/entities/customer-profiles) is **not** automatically created for each `advocateprofileintegrationid` column value. Use the [Update customer profile](https://docs.talon.one/integration-api#tag/Customer-profiles/operation/updateCustomerProfileV2) endpoint or the [Update multiple customer profiles](https://docs.talon.one/integration-api#tag/Customer-profiles/operation/updateCustomerProfilesV2) endpoint to create the customer profiles.  **Note:** We recommend limiting your file size to 500MB.  **Example:**  ```text code,startdate,expirydate,advocateprofileintegrationid,limitval,attributes REFERRAL_CODE1,2020-11-10T23:00:00Z,2021-11-11T23:00:00Z,integid_4,1,\"{\"\"my_attribute\"\": \"\"10_off\"\"}\" REFERRAL_CODE2,2020-11-10T23:00:00Z,2021-11-11T23:00:00Z,integid1,1,\"{\"\"my_attribute\"\": \"\"20_off\"\"}\" ``` 

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
application_id = 789 # Integer | The ID of the Application. It is displayed in your Talon.One deployment URL.
campaign_id = 789 # Integer | The ID of the campaign. It is displayed in your Talon.One deployment URL.
opts = {
  up_file: 'up_file_example' # String | The file containing the data that is being imported.
}

begin
  # Import referrals
  result = api_instance.import_referrals(application_id, campaign_id, opts)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->import_referrals: #{e}"
end
```

#### Using the import_referrals_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<Import>, Integer, Hash)> import_referrals_with_http_info(application_id, campaign_id, opts)

```ruby
begin
  # Import referrals
  data, status_code, headers = api_instance.import_referrals_with_http_info(application_id, campaign_id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <Import>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->import_referrals_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **application_id** | **Integer** | The ID of the Application. It is displayed in your Talon.One deployment URL. |  |
| **campaign_id** | **Integer** | The ID of the campaign. It is displayed in your Talon.One deployment URL. |  |
| **up_file** | **String** | The file containing the data that is being imported. | [optional] |

### Return type

[**Import**](Import.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: multipart/form-data
- **Accept**: application/json


## invite_user_external

> invite_user_external(new_external_invitation)

Invite user from identity provider

[Invite a user](https://docs.talon.one/docs/product/account/account-settings/managing-users#inviting-a-user) from an external identity provider to Talon.One by sending an invitation to their email address. 

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
new_external_invitation = TalonOne::NewExternalInvitation.new({email: 'john.doe@example.com'}) # NewExternalInvitation | body

begin
  # Invite user from identity provider
  api_instance.invite_user_external(new_external_invitation)
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->invite_user_external: #{e}"
end
```

#### Using the invite_user_external_with_http_info variant

This returns an Array which contains the response data (`nil` in this case), status code and headers.

> <Array(nil, Integer, Hash)> invite_user_external_with_http_info(new_external_invitation)

```ruby
begin
  # Invite user from identity provider
  data, status_code, headers = api_instance.invite_user_external_with_http_info(new_external_invitation)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => nil
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->invite_user_external_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **new_external_invitation** | [**NewExternalInvitation**](NewExternalInvitation.md) | body |  |

### Return type

nil (empty response body)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined


## list_account_collections

> <ListAccountCollections200Response> list_account_collections(opts)

List collections in account

List account-level collections in the account.

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
opts = {
  page_size: 789, # Integer | The number of items in the response.
  skip: 789, # Integer | The number of items to skip when paging through large result sets.
  sort: 'sort_example', # String | The field by which results should be sorted. By default, results are sorted in ascending order. To sort them in descending order, prefix the field name with `-`.  **Note:** You may not be able to use all fields for sorting. This is due to performance limitations. 
  with_total_result_size: true, # Boolean | When this flag is set, the result includes the total size of the result, across all pages. This might decrease performance on large data sets.  - When `true`: `hasMore` is true when there is a next page. `totalResultSize` is always zero. - When `false`: `hasMore` is always false. `totalResultSize` contains the total number of results for this query. 
  name: 'name_example' # String | Filter by collection name.
}

begin
  # List collections in account
  result = api_instance.list_account_collections(opts)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->list_account_collections: #{e}"
end
```

#### Using the list_account_collections_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<ListAccountCollections200Response>, Integer, Hash)> list_account_collections_with_http_info(opts)

```ruby
begin
  # List collections in account
  data, status_code, headers = api_instance.list_account_collections_with_http_info(opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <ListAccountCollections200Response>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->list_account_collections_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **page_size** | **Integer** | The number of items in the response. | [optional][default to 1000] |
| **skip** | **Integer** | The number of items to skip when paging through large result sets. | [optional] |
| **sort** | **String** | The field by which results should be sorted. By default, results are sorted in ascending order. To sort them in descending order, prefix the field name with &#x60;-&#x60;.  **Note:** You may not be able to use all fields for sorting. This is due to performance limitations.  | [optional] |
| **with_total_result_size** | **Boolean** | When this flag is set, the result includes the total size of the result, across all pages. This might decrease performance on large data sets.  - When &#x60;true&#x60;: &#x60;hasMore&#x60; is true when there is a next page. &#x60;totalResultSize&#x60; is always zero. - When &#x60;false&#x60;: &#x60;hasMore&#x60; is always false. &#x60;totalResultSize&#x60; contains the total number of results for this query.  | [optional] |
| **name** | **String** | Filter by collection name. | [optional] |

### Return type

[**ListAccountCollections200Response**](ListAccountCollections200Response.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## list_achievements

> <ListAchievements200Response> list_achievements(application_id, campaign_id, opts)

List achievements

List all the achievements for a specific campaign.

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
application_id = 789 # Integer | The ID of the Application. It is displayed in your Talon.One deployment URL.
campaign_id = 789 # Integer | The ID of the campaign. It is displayed in your Talon.One deployment URL.
opts = {
  page_size: 789, # Integer | The number of items in the response.
  skip: 789, # Integer | The number of items to skip when paging through large result sets.
  title: 'title_example' # String | Filter by the display name for the achievement in the campaign manager.  **Note**: If no `title` is provided, all the achievements from the campaign are returned. 
}

begin
  # List achievements
  result = api_instance.list_achievements(application_id, campaign_id, opts)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->list_achievements: #{e}"
end
```

#### Using the list_achievements_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<ListAchievements200Response>, Integer, Hash)> list_achievements_with_http_info(application_id, campaign_id, opts)

```ruby
begin
  # List achievements
  data, status_code, headers = api_instance.list_achievements_with_http_info(application_id, campaign_id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <ListAchievements200Response>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->list_achievements_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **application_id** | **Integer** | The ID of the Application. It is displayed in your Talon.One deployment URL. |  |
| **campaign_id** | **Integer** | The ID of the campaign. It is displayed in your Talon.One deployment URL. |  |
| **page_size** | **Integer** | The number of items in the response. | [optional][default to 50] |
| **skip** | **Integer** | The number of items to skip when paging through large result sets. | [optional] |
| **title** | **String** | Filter by the display name for the achievement in the campaign manager.  **Note**: If no &#x60;title&#x60; is provided, all the achievements from the campaign are returned.  | [optional] |

### Return type

[**ListAchievements200Response**](ListAchievements200Response.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## list_all_roles_v2

> <ListAllRolesV2200Response> list_all_roles_v2

List roles

List all roles.

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

begin
  # List roles
  result = api_instance.list_all_roles_v2
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->list_all_roles_v2: #{e}"
end
```

#### Using the list_all_roles_v2_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<ListAllRolesV2200Response>, Integer, Hash)> list_all_roles_v2_with_http_info

```ruby
begin
  # List roles
  data, status_code, headers = api_instance.list_all_roles_v2_with_http_info
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <ListAllRolesV2200Response>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->list_all_roles_v2_with_http_info: #{e}"
end
```

### Parameters

This endpoint does not need any parameter.

### Return type

[**ListAllRolesV2200Response**](ListAllRolesV2200Response.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## list_campaign_store_budget_limits

> <ListCampaignStoreBudgetLimits200Response> list_campaign_store_budget_limits(application_id, campaign_id, opts)

List campaign store budget limits

Return the store budget limits for a given campaign.

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
application_id = 789 # Integer | The ID of the Application. It is displayed in your Talon.One deployment URL.
campaign_id = 789 # Integer | The ID of the campaign. It is displayed in your Talon.One deployment URL.
opts = {
  action: 'setDiscount', # String | The action that this budget is limiting.
  period: 'overall' # String | The period to which the limit applies.  **Note**: For budgets with no period, set this to `overall`. 
}

begin
  # List campaign store budget limits
  result = api_instance.list_campaign_store_budget_limits(application_id, campaign_id, opts)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->list_campaign_store_budget_limits: #{e}"
end
```

#### Using the list_campaign_store_budget_limits_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<ListCampaignStoreBudgetLimits200Response>, Integer, Hash)> list_campaign_store_budget_limits_with_http_info(application_id, campaign_id, opts)

```ruby
begin
  # List campaign store budget limits
  data, status_code, headers = api_instance.list_campaign_store_budget_limits_with_http_info(application_id, campaign_id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <ListCampaignStoreBudgetLimits200Response>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->list_campaign_store_budget_limits_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **application_id** | **Integer** | The ID of the Application. It is displayed in your Talon.One deployment URL. |  |
| **campaign_id** | **Integer** | The ID of the campaign. It is displayed in your Talon.One deployment URL. |  |
| **action** | **String** | The action that this budget is limiting. | [optional] |
| **period** | **String** | The period to which the limit applies.  **Note**: For budgets with no period, set this to &#x60;overall&#x60;.  | [optional] |

### Return type

[**ListCampaignStoreBudgetLimits200Response**](ListCampaignStoreBudgetLimits200Response.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## list_catalog_items

> <ListCatalogItems200Response> list_catalog_items(catalog_id, opts)

List items in a catalog

Return a paginated list of cart items in the given catalog. 

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
catalog_id = 789 # Integer | The ID of the catalog. You can find the ID in the Campaign Manager in **Account** > **Tools** > **Cart item catalogs**.
opts = {
  page_size: 789, # Integer | The number of items in the response.
  skip: 789, # Integer | The number of items to skip when paging through large result sets.
  with_total_result_size: true, # Boolean | When this flag is set, the result includes the total size of the result, across all pages. This might decrease performance on large data sets.  - When `true`: `hasMore` is true when there is a next page. `totalResultSize` is always zero. - When `false`: `hasMore` is always false. `totalResultSize` contains the total number of results for this query. 
  sku: ['inner_example'], # Array<String> | Filter results by one or more SKUs. Must be exact match.
  product_names: ['inner_example'] # Array<String> | Filter results by one or more product names. Must be exact match.
}

begin
  # List items in a catalog
  result = api_instance.list_catalog_items(catalog_id, opts)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->list_catalog_items: #{e}"
end
```

#### Using the list_catalog_items_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<ListCatalogItems200Response>, Integer, Hash)> list_catalog_items_with_http_info(catalog_id, opts)

```ruby
begin
  # List items in a catalog
  data, status_code, headers = api_instance.list_catalog_items_with_http_info(catalog_id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <ListCatalogItems200Response>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->list_catalog_items_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **catalog_id** | **Integer** | The ID of the catalog. You can find the ID in the Campaign Manager in **Account** &gt; **Tools** &gt; **Cart item catalogs**. |  |
| **page_size** | **Integer** | The number of items in the response. | [optional][default to 1000] |
| **skip** | **Integer** | The number of items to skip when paging through large result sets. | [optional] |
| **with_total_result_size** | **Boolean** | When this flag is set, the result includes the total size of the result, across all pages. This might decrease performance on large data sets.  - When &#x60;true&#x60;: &#x60;hasMore&#x60; is true when there is a next page. &#x60;totalResultSize&#x60; is always zero. - When &#x60;false&#x60;: &#x60;hasMore&#x60; is always false. &#x60;totalResultSize&#x60; contains the total number of results for this query.  | [optional] |
| **sku** | [**Array&lt;String&gt;**](String.md) | Filter results by one or more SKUs. Must be exact match. | [optional] |
| **product_names** | [**Array&lt;String&gt;**](String.md) | Filter results by one or more product names. Must be exact match. | [optional] |

### Return type

[**ListCatalogItems200Response**](ListCatalogItems200Response.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## list_collections

> <ListAccountCollections200Response> list_collections(application_id, campaign_id, opts)

List collections in campaign

List collections in a given campaign.

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
application_id = 789 # Integer | The ID of the Application. It is displayed in your Talon.One deployment URL.
campaign_id = 789 # Integer | The ID of the campaign. It is displayed in your Talon.One deployment URL.
opts = {
  page_size: 789, # Integer | The number of items in the response.
  skip: 789, # Integer | The number of items to skip when paging through large result sets.
  sort: 'sort_example', # String | The field by which results should be sorted. By default, results are sorted in ascending order. To sort them in descending order, prefix the field name with `-`.  **Note:** You may not be able to use all fields for sorting. This is due to performance limitations. 
  with_total_result_size: true, # Boolean | When this flag is set, the result includes the total size of the result, across all pages. This might decrease performance on large data sets.  - When `true`: `hasMore` is true when there is a next page. `totalResultSize` is always zero. - When `false`: `hasMore` is always false. `totalResultSize` contains the total number of results for this query. 
  name: 'name_example' # String | Filter by collection name.
}

begin
  # List collections in campaign
  result = api_instance.list_collections(application_id, campaign_id, opts)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->list_collections: #{e}"
end
```

#### Using the list_collections_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<ListAccountCollections200Response>, Integer, Hash)> list_collections_with_http_info(application_id, campaign_id, opts)

```ruby
begin
  # List collections in campaign
  data, status_code, headers = api_instance.list_collections_with_http_info(application_id, campaign_id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <ListAccountCollections200Response>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->list_collections_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **application_id** | **Integer** | The ID of the Application. It is displayed in your Talon.One deployment URL. |  |
| **campaign_id** | **Integer** | The ID of the campaign. It is displayed in your Talon.One deployment URL. |  |
| **page_size** | **Integer** | The number of items in the response. | [optional][default to 1000] |
| **skip** | **Integer** | The number of items to skip when paging through large result sets. | [optional] |
| **sort** | **String** | The field by which results should be sorted. By default, results are sorted in ascending order. To sort them in descending order, prefix the field name with &#x60;-&#x60;.  **Note:** You may not be able to use all fields for sorting. This is due to performance limitations.  | [optional] |
| **with_total_result_size** | **Boolean** | When this flag is set, the result includes the total size of the result, across all pages. This might decrease performance on large data sets.  - When &#x60;true&#x60;: &#x60;hasMore&#x60; is true when there is a next page. &#x60;totalResultSize&#x60; is always zero. - When &#x60;false&#x60;: &#x60;hasMore&#x60; is always false. &#x60;totalResultSize&#x60; contains the total number of results for this query.  | [optional] |
| **name** | **String** | Filter by collection name. | [optional] |

### Return type

[**ListAccountCollections200Response**](ListAccountCollections200Response.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## list_collections_in_application

> <ListAccountCollections200Response> list_collections_in_application(application_id, opts)

List collections in Application

List campaign-level collections from all campaigns in a given Application.

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
application_id = 789 # Integer | The ID of the Application. It is displayed in your Talon.One deployment URL.
opts = {
  page_size: 789, # Integer | The number of items in the response.
  skip: 789, # Integer | The number of items to skip when paging through large result sets.
  sort: 'sort_example', # String | The field by which results should be sorted. By default, results are sorted in ascending order. To sort them in descending order, prefix the field name with `-`.  **Note:** You may not be able to use all fields for sorting. This is due to performance limitations. 
  with_total_result_size: true, # Boolean | When this flag is set, the result includes the total size of the result, across all pages. This might decrease performance on large data sets.  - When `true`: `hasMore` is true when there is a next page. `totalResultSize` is always zero. - When `false`: `hasMore` is always false. `totalResultSize` contains the total number of results for this query. 
  name: 'name_example' # String | Filter by collection name.
}

begin
  # List collections in Application
  result = api_instance.list_collections_in_application(application_id, opts)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->list_collections_in_application: #{e}"
end
```

#### Using the list_collections_in_application_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<ListAccountCollections200Response>, Integer, Hash)> list_collections_in_application_with_http_info(application_id, opts)

```ruby
begin
  # List collections in Application
  data, status_code, headers = api_instance.list_collections_in_application_with_http_info(application_id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <ListAccountCollections200Response>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->list_collections_in_application_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **application_id** | **Integer** | The ID of the Application. It is displayed in your Talon.One deployment URL. |  |
| **page_size** | **Integer** | The number of items in the response. | [optional][default to 1000] |
| **skip** | **Integer** | The number of items to skip when paging through large result sets. | [optional] |
| **sort** | **String** | The field by which results should be sorted. By default, results are sorted in ascending order. To sort them in descending order, prefix the field name with &#x60;-&#x60;.  **Note:** You may not be able to use all fields for sorting. This is due to performance limitations.  | [optional] |
| **with_total_result_size** | **Boolean** | When this flag is set, the result includes the total size of the result, across all pages. This might decrease performance on large data sets.  - When &#x60;true&#x60;: &#x60;hasMore&#x60; is true when there is a next page. &#x60;totalResultSize&#x60; is always zero. - When &#x60;false&#x60;: &#x60;hasMore&#x60; is always false. &#x60;totalResultSize&#x60; contains the total number of results for this query.  | [optional] |
| **name** | **String** | Filter by collection name. | [optional] |

### Return type

[**ListAccountCollections200Response**](ListAccountCollections200Response.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## list_stores

> <ListStores200Response> list_stores(application_id, opts)

List stores

List all stores for a specific Application.

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
application_id = 789 # Integer | The ID of the Application. It is displayed in your Talon.One deployment URL.
opts = {
  page_size: 789, # Integer | The number of items in the response.
  skip: 789, # Integer | The number of items to skip when paging through large result sets.
  sort: 'sort_example', # String | The field by which results should be sorted. By default, results are sorted in ascending order. To sort them in descending order, prefix the field name with `-`.  **Note:** You may not be able to use all fields for sorting. This is due to performance limitations. 
  with_total_result_size: true, # Boolean | When this flag is set, the result includes the total size of the result, across all pages. This might decrease performance on large data sets.  - When `true`: `hasMore` is true when there is a next page. `totalResultSize` is always zero. - When `false`: `hasMore` is always false. `totalResultSize` contains the total number of results for this query. 
  campaign_id: 8.14, # Float | Filter results by campaign ID.
  name: 'name_example', # String | The name of the store.
  integration_id: 'integration_id_example', # String | The integration ID of the store.
  query: 'query_example' # String | Filter results by `name` or `integrationId`.
}

begin
  # List stores
  result = api_instance.list_stores(application_id, opts)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->list_stores: #{e}"
end
```

#### Using the list_stores_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<ListStores200Response>, Integer, Hash)> list_stores_with_http_info(application_id, opts)

```ruby
begin
  # List stores
  data, status_code, headers = api_instance.list_stores_with_http_info(application_id, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <ListStores200Response>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->list_stores_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **application_id** | **Integer** | The ID of the Application. It is displayed in your Talon.One deployment URL. |  |
| **page_size** | **Integer** | The number of items in the response. | [optional][default to 1000] |
| **skip** | **Integer** | The number of items to skip when paging through large result sets. | [optional] |
| **sort** | **String** | The field by which results should be sorted. By default, results are sorted in ascending order. To sort them in descending order, prefix the field name with &#x60;-&#x60;.  **Note:** You may not be able to use all fields for sorting. This is due to performance limitations.  | [optional] |
| **with_total_result_size** | **Boolean** | When this flag is set, the result includes the total size of the result, across all pages. This might decrease performance on large data sets.  - When &#x60;true&#x60;: &#x60;hasMore&#x60; is true when there is a next page. &#x60;totalResultSize&#x60; is always zero. - When &#x60;false&#x60;: &#x60;hasMore&#x60; is always false. &#x60;totalResultSize&#x60; contains the total number of results for this query.  | [optional] |
| **campaign_id** | **Float** | Filter results by campaign ID. | [optional] |
| **name** | **String** | The name of the store. | [optional] |
| **integration_id** | **String** | The integration ID of the store. | [optional] |
| **query** | **String** | Filter results by &#x60;name&#x60; or &#x60;integrationId&#x60;. | [optional] |

### Return type

[**ListStores200Response**](ListStores200Response.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## okta_event_handler_challenge

> okta_event_handler_challenge

Validate Okta API ownership

Validate the ownership of the API through a challenge-response mechanism.  This challenger endpoint is used by Okta to confirm that communication between Talon.One and Okta is correctly configured and accessible for provisioning and deprovisioning of Talon.One users, and that only Talon.One can receive and respond to events from Okta. 

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

begin
  # Validate Okta API ownership
  api_instance.okta_event_handler_challenge
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->okta_event_handler_challenge: #{e}"
end
```

#### Using the okta_event_handler_challenge_with_http_info variant

This returns an Array which contains the response data (`nil` in this case), status code and headers.

> <Array(nil, Integer, Hash)> okta_event_handler_challenge_with_http_info

```ruby
begin
  # Validate Okta API ownership
  data, status_code, headers = api_instance.okta_event_handler_challenge_with_http_info
  p status_code # => 2xx
  p headers # => { ... }
  p data # => nil
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->okta_event_handler_challenge_with_http_info: #{e}"
end
```

### Parameters

This endpoint does not need any parameter.

### Return type

nil (empty response body)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined


## remove_loyalty_points

> remove_loyalty_points(loyalty_program_id, integration_id, deduct_loyalty_points)

Deduct points from customer profile

Deduct points from the specified loyalty program and specified customer profile.  **Important:** - Only active points can be deducted. - Only pending points are rolled back when a session is cancelled or reopened.  To get the `integrationId` of the profile from a `sessionId`, use the [Update customer session](https://docs.talon.one/integration-api#operation/updateCustomerSessionV2) endpoint. 

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
loyalty_program_id = 'loyalty_program_id_example' # String | The identifier for the loyalty program.
integration_id = 'integration_id_example' # String | The integration identifier for this customer profile. Must be: - Unique within the deployment. - Stable for the customer. Do not use an ID that the customer can update themselves. For example, you can use a database ID.  Once set, you cannot update this identifier. 
deduct_loyalty_points = TalonOne::DeductLoyaltyPoints.new({points: 300}) # DeductLoyaltyPoints | body

begin
  # Deduct points from customer profile
  api_instance.remove_loyalty_points(loyalty_program_id, integration_id, deduct_loyalty_points)
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->remove_loyalty_points: #{e}"
end
```

#### Using the remove_loyalty_points_with_http_info variant

This returns an Array which contains the response data (`nil` in this case), status code and headers.

> <Array(nil, Integer, Hash)> remove_loyalty_points_with_http_info(loyalty_program_id, integration_id, deduct_loyalty_points)

```ruby
begin
  # Deduct points from customer profile
  data, status_code, headers = api_instance.remove_loyalty_points_with_http_info(loyalty_program_id, integration_id, deduct_loyalty_points)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => nil
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->remove_loyalty_points_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **loyalty_program_id** | **String** | The identifier for the loyalty program. |  |
| **integration_id** | **String** | The integration identifier for this customer profile. Must be: - Unique within the deployment. - Stable for the customer. Do not use an ID that the customer can update themselves. For example, you can use a database ID.  Once set, you cannot update this identifier.  |  |
| **deduct_loyalty_points** | [**DeductLoyaltyPoints**](DeductLoyaltyPoints.md) | body |  |

### Return type

nil (empty response body)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## reset_password

> <NewPassword> reset_password(new_password)

Reset password

Consumes the supplied password reset token and updates the password for the associated account. 

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
new_password = TalonOne::NewPassword.new({password: 'Admin&12943!7', reset_token: 'Z2VgacVNkexLKBUIzsRDDZSGxnIkC53y'}) # NewPassword | body

begin
  # Reset password
  result = api_instance.reset_password(new_password)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->reset_password: #{e}"
end
```

#### Using the reset_password_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<NewPassword>, Integer, Hash)> reset_password_with_http_info(new_password)

```ruby
begin
  # Reset password
  data, status_code, headers = api_instance.reset_password_with_http_info(new_password)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <NewPassword>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->reset_password_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **new_password** | [**NewPassword**](NewPassword.md) | body |  |

### Return type

[**NewPassword**](NewPassword.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## scim_create_group

> <ScimGroup> scim_create_group(scim_base_group)

Create SCIM group

Create a new Talon.One group using the SCIM Group provisioning protocol with an identity provider, for example, Microsoft Entra ID, and assign members from the payload to the new group. In Talon.One, a `Group` corresponds to a [role](https://docs.talon.one/docs/product/account/account-settings/managing-roles), and `members` are the [users](https://docs.talon.one/docs/product/account/account-settings/managing-users) assigned to that role.

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
scim_base_group = TalonOne::ScimBaseGroup.new # ScimBaseGroup | body

begin
  # Create SCIM group
  result = api_instance.scim_create_group(scim_base_group)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->scim_create_group: #{e}"
end
```

#### Using the scim_create_group_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<ScimGroup>, Integer, Hash)> scim_create_group_with_http_info(scim_base_group)

```ruby
begin
  # Create SCIM group
  data, status_code, headers = api_instance.scim_create_group_with_http_info(scim_base_group)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <ScimGroup>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->scim_create_group_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **scim_base_group** | [**ScimBaseGroup**](ScimBaseGroup.md) | body |  |

### Return type

[**ScimGroup**](ScimGroup.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## scim_create_user

> <ScimUser> scim_create_user(scim_new_user)

Create SCIM user

Create a new Talon.One user using the SCIM provisioning protocol with an identity provider, for example, Microsoft Entra ID.

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
scim_new_user = TalonOne::ScimNewUser.new({user_name: 'john.doe@example.com'}) # ScimNewUser | body

begin
  # Create SCIM user
  result = api_instance.scim_create_user(scim_new_user)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->scim_create_user: #{e}"
end
```

#### Using the scim_create_user_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<ScimUser>, Integer, Hash)> scim_create_user_with_http_info(scim_new_user)

```ruby
begin
  # Create SCIM user
  data, status_code, headers = api_instance.scim_create_user_with_http_info(scim_new_user)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <ScimUser>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->scim_create_user_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **scim_new_user** | [**ScimNewUser**](ScimNewUser.md) | body |  |

### Return type

[**ScimUser**](ScimUser.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## scim_delete_group

> scim_delete_group(group_id)

Delete SCIM group

Delete a specific group created using the SCIM provisioning protocol with an identity provider, for example, Microsoft Entra ID. In Talon.One, a `Group` corresponds to a [role](https://docs.talon.one/docs/product/account/account-settings/managing-roles), and `members` are the [users](https://docs.talon.one/docs/product/account/account-settings/managing-users) assigned to that role.

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
group_id = 789 # Integer | The ID of the group.

begin
  # Delete SCIM group
  api_instance.scim_delete_group(group_id)
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->scim_delete_group: #{e}"
end
```

#### Using the scim_delete_group_with_http_info variant

This returns an Array which contains the response data (`nil` in this case), status code and headers.

> <Array(nil, Integer, Hash)> scim_delete_group_with_http_info(group_id)

```ruby
begin
  # Delete SCIM group
  data, status_code, headers = api_instance.scim_delete_group_with_http_info(group_id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => nil
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->scim_delete_group_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **group_id** | **Integer** | The ID of the group. |  |

### Return type

nil (empty response body)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined


## scim_delete_user

> scim_delete_user(user_id)

Delete SCIM user

Delete a specific Talon.One user created using the SCIM provisioning protocol with an identity provider, for example, Microsoft Entra ID.

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
user_id = 789 # Integer | The ID of the user.

begin
  # Delete SCIM user
  api_instance.scim_delete_user(user_id)
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->scim_delete_user: #{e}"
end
```

#### Using the scim_delete_user_with_http_info variant

This returns an Array which contains the response data (`nil` in this case), status code and headers.

> <Array(nil, Integer, Hash)> scim_delete_user_with_http_info(user_id)

```ruby
begin
  # Delete SCIM user
  data, status_code, headers = api_instance.scim_delete_user_with_http_info(user_id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => nil
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->scim_delete_user_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **user_id** | **Integer** | The ID of the user. |  |

### Return type

nil (empty response body)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined


## scim_get_group

> <ScimGroup> scim_get_group(group_id)

Get SCIM group

Retrieve data for a specific group created using the SCIM provisioning protocol with an identity provider, for example, Microsoft Entra ID. In Talon.One, a `Group` corresponds to a [role](https://docs.talon.one/docs/product/account/account-settings/managing-roles), and `members` are the [users](https://docs.talon.one/docs/product/account/account-settings/managing-users) assigned to that role.

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
group_id = 789 # Integer | The ID of the group.

begin
  # Get SCIM group
  result = api_instance.scim_get_group(group_id)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->scim_get_group: #{e}"
end
```

#### Using the scim_get_group_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<ScimGroup>, Integer, Hash)> scim_get_group_with_http_info(group_id)

```ruby
begin
  # Get SCIM group
  data, status_code, headers = api_instance.scim_get_group_with_http_info(group_id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <ScimGroup>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->scim_get_group_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **group_id** | **Integer** | The ID of the group. |  |

### Return type

[**ScimGroup**](ScimGroup.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## scim_get_groups

> <ScimGroupsListResponse> scim_get_groups

List SCIM groups

Retrieve a paginated list of groups created using the SCIM protocol with an identity provider, for example, Microsoft Entra ID. In Talon.One, a `Group` corresponds to a [role](https://docs.talon.one/docs/product/account/account-settings/managing-roles), and `members` are the [users](https://docs.talon.one/docs/product/account/account-settings/managing-users) assigned to that role.

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

begin
  # List SCIM groups
  result = api_instance.scim_get_groups
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->scim_get_groups: #{e}"
end
```

#### Using the scim_get_groups_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<ScimGroupsListResponse>, Integer, Hash)> scim_get_groups_with_http_info

```ruby
begin
  # List SCIM groups
  data, status_code, headers = api_instance.scim_get_groups_with_http_info
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <ScimGroupsListResponse>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->scim_get_groups_with_http_info: #{e}"
end
```

### Parameters

This endpoint does not need any parameter.

### Return type

[**ScimGroupsListResponse**](ScimGroupsListResponse.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## scim_get_resource_types

> <ScimResourceTypesListResponse> scim_get_resource_types

List supported SCIM resource types

Retrieve a list of resource types supported by the SCIM provisioning protocol.  Resource types define the various kinds of resources that can be managed via the SCIM API, such as users, groups, or custom-defined resources. 

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

begin
  # List supported SCIM resource types
  result = api_instance.scim_get_resource_types
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->scim_get_resource_types: #{e}"
end
```

#### Using the scim_get_resource_types_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<ScimResourceTypesListResponse>, Integer, Hash)> scim_get_resource_types_with_http_info

```ruby
begin
  # List supported SCIM resource types
  data, status_code, headers = api_instance.scim_get_resource_types_with_http_info
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <ScimResourceTypesListResponse>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->scim_get_resource_types_with_http_info: #{e}"
end
```

### Parameters

This endpoint does not need any parameter.

### Return type

[**ScimResourceTypesListResponse**](ScimResourceTypesListResponse.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## scim_get_schemas

> <ScimSchemasListResponse> scim_get_schemas

List supported SCIM schemas

Retrieve a list of schemas supported by the SCIM provisioning protocol.  Schemas define the structure and attributes of the different resources that can be managed via the SCIM API, such as users, groups, and any custom-defined resources. 

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

begin
  # List supported SCIM schemas
  result = api_instance.scim_get_schemas
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->scim_get_schemas: #{e}"
end
```

#### Using the scim_get_schemas_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<ScimSchemasListResponse>, Integer, Hash)> scim_get_schemas_with_http_info

```ruby
begin
  # List supported SCIM schemas
  data, status_code, headers = api_instance.scim_get_schemas_with_http_info
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <ScimSchemasListResponse>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->scim_get_schemas_with_http_info: #{e}"
end
```

### Parameters

This endpoint does not need any parameter.

### Return type

[**ScimSchemasListResponse**](ScimSchemasListResponse.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## scim_get_service_provider_config

> <ScimServiceProviderConfigResponse> scim_get_service_provider_config

Get SCIM service provider configuration

Retrieve the configuration settings of the SCIM service provider. It provides details about the features and capabilities supported by the SCIM API, such as the different operation settings. 

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

begin
  # Get SCIM service provider configuration
  result = api_instance.scim_get_service_provider_config
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->scim_get_service_provider_config: #{e}"
end
```

#### Using the scim_get_service_provider_config_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<ScimServiceProviderConfigResponse>, Integer, Hash)> scim_get_service_provider_config_with_http_info

```ruby
begin
  # Get SCIM service provider configuration
  data, status_code, headers = api_instance.scim_get_service_provider_config_with_http_info
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <ScimServiceProviderConfigResponse>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->scim_get_service_provider_config_with_http_info: #{e}"
end
```

### Parameters

This endpoint does not need any parameter.

### Return type

[**ScimServiceProviderConfigResponse**](ScimServiceProviderConfigResponse.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## scim_get_user

> <ScimUser> scim_get_user(user_id)

Get SCIM user

Retrieve data for a specific Talon.One user created using the SCIM provisioning protocol with an identity provider, for example, Microsoft Entra ID.

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
user_id = 789 # Integer | The ID of the user.

begin
  # Get SCIM user
  result = api_instance.scim_get_user(user_id)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->scim_get_user: #{e}"
end
```

#### Using the scim_get_user_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<ScimUser>, Integer, Hash)> scim_get_user_with_http_info(user_id)

```ruby
begin
  # Get SCIM user
  data, status_code, headers = api_instance.scim_get_user_with_http_info(user_id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <ScimUser>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->scim_get_user_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **user_id** | **Integer** | The ID of the user. |  |

### Return type

[**ScimUser**](ScimUser.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## scim_get_users

> <ScimUsersListResponse> scim_get_users

List SCIM users

Retrieve a paginated list of users that have been provisioned using the SCIM protocol with an identity provider, for example, Microsoft Entra ID.

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

begin
  # List SCIM users
  result = api_instance.scim_get_users
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->scim_get_users: #{e}"
end
```

#### Using the scim_get_users_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<ScimUsersListResponse>, Integer, Hash)> scim_get_users_with_http_info

```ruby
begin
  # List SCIM users
  data, status_code, headers = api_instance.scim_get_users_with_http_info
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <ScimUsersListResponse>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->scim_get_users_with_http_info: #{e}"
end
```

### Parameters

This endpoint does not need any parameter.

### Return type

[**ScimUsersListResponse**](ScimUsersListResponse.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## scim_patch_group

> <ScimGroup> scim_patch_group(group_id, scim_patch_request)

Update SCIM group attributes

Update certain attributes of a group created using the SCIM provisioning protocol with an identity provider, for example, Microsoft Entra ID. This endpoint allows for selective adding, removing, or replacing of specific group attributes while other attributes remain unchanged. In Talon.One, a `Group` corresponds to a [role](https://docs.talon.one/docs/product/account/account-settings/managing-roles), and `members` are the [users](https://docs.talon.one/docs/product/account/account-settings/managing-users) assigned to that role. 

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
group_id = 789 # Integer | The ID of the group.
scim_patch_request = TalonOne::ScimPatchRequest.new({operations: [TalonOne::ScimPatchOperation.new({op: 'add'})]}) # ScimPatchRequest | body

begin
  # Update SCIM group attributes
  result = api_instance.scim_patch_group(group_id, scim_patch_request)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->scim_patch_group: #{e}"
end
```

#### Using the scim_patch_group_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<ScimGroup>, Integer, Hash)> scim_patch_group_with_http_info(group_id, scim_patch_request)

```ruby
begin
  # Update SCIM group attributes
  data, status_code, headers = api_instance.scim_patch_group_with_http_info(group_id, scim_patch_request)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <ScimGroup>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->scim_patch_group_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **group_id** | **Integer** | The ID of the group. |  |
| **scim_patch_request** | [**ScimPatchRequest**](ScimPatchRequest.md) | body |  |

### Return type

[**ScimGroup**](ScimGroup.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## scim_patch_user

> <ScimUser> scim_patch_user(user_id, scim_patch_request)

Update SCIM user attributes

Update certain attributes of a specific Talon.One user created using the SCIM provisioning protocol with an identity provider, for example, Microsoft Entra ID.  This endpoint allows for selective adding, removing, or replacing specific attributes while leaving other attributes unchanged. 

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
user_id = 789 # Integer | The ID of the user.
scim_patch_request = TalonOne::ScimPatchRequest.new({operations: [TalonOne::ScimPatchOperation.new({op: 'add'})]}) # ScimPatchRequest | body

begin
  # Update SCIM user attributes
  result = api_instance.scim_patch_user(user_id, scim_patch_request)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->scim_patch_user: #{e}"
end
```

#### Using the scim_patch_user_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<ScimUser>, Integer, Hash)> scim_patch_user_with_http_info(user_id, scim_patch_request)

```ruby
begin
  # Update SCIM user attributes
  data, status_code, headers = api_instance.scim_patch_user_with_http_info(user_id, scim_patch_request)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <ScimUser>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->scim_patch_user_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **user_id** | **Integer** | The ID of the user. |  |
| **scim_patch_request** | [**ScimPatchRequest**](ScimPatchRequest.md) | body |  |

### Return type

[**ScimUser**](ScimUser.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## scim_replace_group_attributes

> <ScimGroup> scim_replace_group_attributes(group_id, scim_base_group)

Update SCIM group

Update the details of a specific group created using the SCIM provisioning protocol with an identity provider, for example, Microsoft Entra ID. This endpoint replaces all attributes of the given group with the attributes provided in the request payload. In Talon.One, a `Group` corresponds to a [role](https://docs.talon.one/docs/product/account/account-settings/managing-roles), and `members` are the [users](https://docs.talon.one/docs/product/account/account-settings/managing-users) assigned to that role. 

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
group_id = 789 # Integer | The ID of the group.
scim_base_group = TalonOne::ScimBaseGroup.new # ScimBaseGroup | body

begin
  # Update SCIM group
  result = api_instance.scim_replace_group_attributes(group_id, scim_base_group)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->scim_replace_group_attributes: #{e}"
end
```

#### Using the scim_replace_group_attributes_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<ScimGroup>, Integer, Hash)> scim_replace_group_attributes_with_http_info(group_id, scim_base_group)

```ruby
begin
  # Update SCIM group
  data, status_code, headers = api_instance.scim_replace_group_attributes_with_http_info(group_id, scim_base_group)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <ScimGroup>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->scim_replace_group_attributes_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **group_id** | **Integer** | The ID of the group. |  |
| **scim_base_group** | [**ScimBaseGroup**](ScimBaseGroup.md) | body |  |

### Return type

[**ScimGroup**](ScimGroup.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## scim_replace_user_attributes

> <ScimUser> scim_replace_user_attributes(user_id, scim_new_user)

Update SCIM user

Update the details of a specific Talon.One user created using the SCIM provisioning protocol with an identity provider, for example, Microsoft Entra ID.  This endpoint replaces all attributes of the specific user with the attributes provided in the request payload. 

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
user_id = 789 # Integer | The ID of the user.
scim_new_user = TalonOne::ScimNewUser.new({user_name: 'john.doe@example.com'}) # ScimNewUser | body

begin
  # Update SCIM user
  result = api_instance.scim_replace_user_attributes(user_id, scim_new_user)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->scim_replace_user_attributes: #{e}"
end
```

#### Using the scim_replace_user_attributes_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<ScimUser>, Integer, Hash)> scim_replace_user_attributes_with_http_info(user_id, scim_new_user)

```ruby
begin
  # Update SCIM user
  data, status_code, headers = api_instance.scim_replace_user_attributes_with_http_info(user_id, scim_new_user)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <ScimUser>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->scim_replace_user_attributes_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **user_id** | **Integer** | The ID of the user. |  |
| **scim_new_user** | [**ScimNewUser**](ScimNewUser.md) | body |  |

### Return type

[**ScimUser**](ScimUser.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## search_coupons_advanced_application_wide_without_total_count

> <GetCouponsWithoutTotalCount200Response> search_coupons_advanced_application_wide_without_total_count(application_id, body, opts)

List coupons that match the given attributes (without total count)

List the coupons whose attributes match the query criteria in all the campaigns of the given Application.  The match is successful if all the attributes of the request are found in a coupon, even if the coupon has more attributes that are not present on the request.  **Note:** The total count is not included in the response. 

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
application_id = 789 # Integer | The ID of the Application. It is displayed in your Talon.One deployment URL.
body = { ... } # Object | body
opts = {
  page_size: 789, # Integer | The number of items in the response.
  skip: 789, # Integer | The number of items to skip when paging through large result sets.
  sort: 'sort_example', # String | The field by which results should be sorted. By default, results are sorted in ascending order. To sort them in descending order, prefix the field name with `-`.  **Note:** You may not be able to use all fields for sorting. This is due to performance limitations. 
  value: 'value_example', # String | Filter results performing case-insensitive matching against the coupon code. Both the code and the query are folded to remove all non-alpha-numeric characters.
  created_before: Time.parse('2013-10-20T19:20:30+01:00'), # Time | Filter results comparing the parameter value, expected to be an RFC3339 timestamp string, to the coupon creation timestamp. You can use any time zone setting. Talon.One will convert to UTC internally.
  created_after: Time.parse('2013-10-20T19:20:30+01:00'), # Time | Filter results comparing the parameter value, expected to be an RFC3339 timestamp string, to the coupon creation timestamp. You can use any time zone setting. Talon.One will convert to UTC internally.
  valid: 'expired', # String | Either \"expired\", \"validNow\", or \"validFuture\". The first option matches coupons in which the expiration date is set and in the past. The second matches coupons in which start date is null or in the past and expiration date is null or in the future, the third matches coupons in which start date is set and in the future. 
  usable: 'true', # String | Either \"true\" or \"false\". If \"true\", only coupons where `usageCounter < usageLimit` will be returned, \"false\" will return only coupons where `usageCounter >= usageLimit`. 
  referral_id: 789, # Integer | Filter the results by matching them with the ID of a referral. This filter shows the coupons created by redeeming a referral code.
  recipient_integration_id: 'recipient_integration_id_example', # String | Filter results by match with a profile ID specified in the coupon's RecipientIntegrationId field.
  batch_id: 'batch_id_example', # String | Filter results by batches of coupons
  exact_match: true, # Boolean | Filter results to an exact case-insensitive matching against the coupon code.
  campaign_state: 'enabled' # String | Filter results by the state of the campaign.  - `enabled`: Campaigns that are scheduled, running (activated), or expired. - `running`: Campaigns that are running (activated). - `disabled`: Campaigns that are disabled. - `expired`: Campaigns that are expired. - `archived`: Campaigns that are archived. 
}

begin
  # List coupons that match the given attributes (without total count)
  result = api_instance.search_coupons_advanced_application_wide_without_total_count(application_id, body, opts)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->search_coupons_advanced_application_wide_without_total_count: #{e}"
end
```

#### Using the search_coupons_advanced_application_wide_without_total_count_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<GetCouponsWithoutTotalCount200Response>, Integer, Hash)> search_coupons_advanced_application_wide_without_total_count_with_http_info(application_id, body, opts)

```ruby
begin
  # List coupons that match the given attributes (without total count)
  data, status_code, headers = api_instance.search_coupons_advanced_application_wide_without_total_count_with_http_info(application_id, body, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <GetCouponsWithoutTotalCount200Response>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->search_coupons_advanced_application_wide_without_total_count_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **application_id** | **Integer** | The ID of the Application. It is displayed in your Talon.One deployment URL. |  |
| **body** | **Object** | body |  |
| **page_size** | **Integer** | The number of items in the response. | [optional][default to 1000] |
| **skip** | **Integer** | The number of items to skip when paging through large result sets. | [optional] |
| **sort** | **String** | The field by which results should be sorted. By default, results are sorted in ascending order. To sort them in descending order, prefix the field name with &#x60;-&#x60;.  **Note:** You may not be able to use all fields for sorting. This is due to performance limitations.  | [optional] |
| **value** | **String** | Filter results performing case-insensitive matching against the coupon code. Both the code and the query are folded to remove all non-alpha-numeric characters. | [optional] |
| **created_before** | **Time** | Filter results comparing the parameter value, expected to be an RFC3339 timestamp string, to the coupon creation timestamp. You can use any time zone setting. Talon.One will convert to UTC internally. | [optional] |
| **created_after** | **Time** | Filter results comparing the parameter value, expected to be an RFC3339 timestamp string, to the coupon creation timestamp. You can use any time zone setting. Talon.One will convert to UTC internally. | [optional] |
| **valid** | **String** | Either \&quot;expired\&quot;, \&quot;validNow\&quot;, or \&quot;validFuture\&quot;. The first option matches coupons in which the expiration date is set and in the past. The second matches coupons in which start date is null or in the past and expiration date is null or in the future, the third matches coupons in which start date is set and in the future.  | [optional] |
| **usable** | **String** | Either \&quot;true\&quot; or \&quot;false\&quot;. If \&quot;true\&quot;, only coupons where &#x60;usageCounter &lt; usageLimit&#x60; will be returned, \&quot;false\&quot; will return only coupons where &#x60;usageCounter &gt;&#x3D; usageLimit&#x60;.  | [optional] |
| **referral_id** | **Integer** | Filter the results by matching them with the ID of a referral. This filter shows the coupons created by redeeming a referral code. | [optional] |
| **recipient_integration_id** | **String** | Filter results by match with a profile ID specified in the coupon&#39;s RecipientIntegrationId field. | [optional] |
| **batch_id** | **String** | Filter results by batches of coupons | [optional] |
| **exact_match** | **Boolean** | Filter results to an exact case-insensitive matching against the coupon code. | [optional][default to false] |
| **campaign_state** | **String** | Filter results by the state of the campaign.  - &#x60;enabled&#x60;: Campaigns that are scheduled, running (activated), or expired. - &#x60;running&#x60;: Campaigns that are running (activated). - &#x60;disabled&#x60;: Campaigns that are disabled. - &#x60;expired&#x60;: Campaigns that are expired. - &#x60;archived&#x60;: Campaigns that are archived.  | [optional] |

### Return type

[**GetCouponsWithoutTotalCount200Response**](GetCouponsWithoutTotalCount200Response.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## search_coupons_advanced_without_total_count

> <GetCouponsWithoutTotalCount200Response> search_coupons_advanced_without_total_count(application_id, campaign_id, body, opts)

List coupons that match the given attributes in campaign (without total count)

List the coupons whose attributes match the query criteria in the given campaign.  The match is successful if all the attributes of the request are found in a coupon, even if the coupon has more attributes that are not present on the request.  **Note:** The total count is not included in the response. 

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
application_id = 789 # Integer | The ID of the Application. It is displayed in your Talon.One deployment URL.
campaign_id = 789 # Integer | The ID of the campaign. It is displayed in your Talon.One deployment URL.
body = { ... } # Object | body
opts = {
  page_size: 789, # Integer | The number of items in the response.
  skip: 789, # Integer | The number of items to skip when paging through large result sets.
  sort: 'sort_example', # String | The field by which results should be sorted. By default, results are sorted in ascending order. To sort them in descending order, prefix the field name with `-`.  **Note:** You may not be able to use all fields for sorting. This is due to performance limitations. 
  value: 'value_example', # String | Filter results performing case-insensitive matching against the coupon code. Both the code and the query are folded to remove all non-alpha-numeric characters.
  created_before: Time.parse('2013-10-20T19:20:30+01:00'), # Time | Filter results comparing the parameter value, expected to be an RFC3339 timestamp string, to the coupon creation timestamp. You can use any time zone setting. Talon.One will convert to UTC internally.
  created_after: Time.parse('2013-10-20T19:20:30+01:00'), # Time | Filter results comparing the parameter value, expected to be an RFC3339 timestamp string, to the coupon creation timestamp. You can use any time zone setting. Talon.One will convert to UTC internally.
  valid: 'expired', # String | Either \"expired\", \"validNow\", or \"validFuture\". The first option matches coupons in which the expiration date is set and in the past. The second matches coupons in which start date is null or in the past and expiration date is null or in the future, the third matches coupons in which start date is set and in the future. 
  usable: 'true', # String | Either \"true\" or \"false\". If \"true\", only coupons where `usageCounter < usageLimit` will be returned, \"false\" will return only coupons where `usageCounter >= usageLimit`. 
  referral_id: 789, # Integer | Filter the results by matching them with the ID of a referral. This filter shows the coupons created by redeeming a referral code.
  recipient_integration_id: 'recipient_integration_id_example', # String | Filter results by match with a profile ID specified in the coupon's RecipientIntegrationId field.
  exact_match: true, # Boolean | Filter results to an exact case-insensitive matching against the coupon code.
  batch_id: 'batch_id_example' # String | Filter results by batches of coupons
}

begin
  # List coupons that match the given attributes in campaign (without total count)
  result = api_instance.search_coupons_advanced_without_total_count(application_id, campaign_id, body, opts)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->search_coupons_advanced_without_total_count: #{e}"
end
```

#### Using the search_coupons_advanced_without_total_count_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<GetCouponsWithoutTotalCount200Response>, Integer, Hash)> search_coupons_advanced_without_total_count_with_http_info(application_id, campaign_id, body, opts)

```ruby
begin
  # List coupons that match the given attributes in campaign (without total count)
  data, status_code, headers = api_instance.search_coupons_advanced_without_total_count_with_http_info(application_id, campaign_id, body, opts)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <GetCouponsWithoutTotalCount200Response>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->search_coupons_advanced_without_total_count_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **application_id** | **Integer** | The ID of the Application. It is displayed in your Talon.One deployment URL. |  |
| **campaign_id** | **Integer** | The ID of the campaign. It is displayed in your Talon.One deployment URL. |  |
| **body** | **Object** | body |  |
| **page_size** | **Integer** | The number of items in the response. | [optional][default to 1000] |
| **skip** | **Integer** | The number of items to skip when paging through large result sets. | [optional] |
| **sort** | **String** | The field by which results should be sorted. By default, results are sorted in ascending order. To sort them in descending order, prefix the field name with &#x60;-&#x60;.  **Note:** You may not be able to use all fields for sorting. This is due to performance limitations.  | [optional] |
| **value** | **String** | Filter results performing case-insensitive matching against the coupon code. Both the code and the query are folded to remove all non-alpha-numeric characters. | [optional] |
| **created_before** | **Time** | Filter results comparing the parameter value, expected to be an RFC3339 timestamp string, to the coupon creation timestamp. You can use any time zone setting. Talon.One will convert to UTC internally. | [optional] |
| **created_after** | **Time** | Filter results comparing the parameter value, expected to be an RFC3339 timestamp string, to the coupon creation timestamp. You can use any time zone setting. Talon.One will convert to UTC internally. | [optional] |
| **valid** | **String** | Either \&quot;expired\&quot;, \&quot;validNow\&quot;, or \&quot;validFuture\&quot;. The first option matches coupons in which the expiration date is set and in the past. The second matches coupons in which start date is null or in the past and expiration date is null or in the future, the third matches coupons in which start date is set and in the future.  | [optional] |
| **usable** | **String** | Either \&quot;true\&quot; or \&quot;false\&quot;. If \&quot;true\&quot;, only coupons where &#x60;usageCounter &lt; usageLimit&#x60; will be returned, \&quot;false\&quot; will return only coupons where &#x60;usageCounter &gt;&#x3D; usageLimit&#x60;.  | [optional] |
| **referral_id** | **Integer** | Filter the results by matching them with the ID of a referral. This filter shows the coupons created by redeeming a referral code. | [optional] |
| **recipient_integration_id** | **String** | Filter results by match with a profile ID specified in the coupon&#39;s RecipientIntegrationId field. | [optional] |
| **exact_match** | **Boolean** | Filter results to an exact case-insensitive matching against the coupon code. | [optional][default to false] |
| **batch_id** | **String** | Filter results by batches of coupons | [optional] |

### Return type

[**GetCouponsWithoutTotalCount200Response**](GetCouponsWithoutTotalCount200Response.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## summarize_campaign_store_budget

> <SummarizeCampaignStoreBudget200Response> summarize_campaign_store_budget(application_id, campaign_id)

Get summary of campaign store budgets

Fetch a summary of all store budget information for a given campaign.

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
application_id = 789 # Integer | The ID of the Application. It is displayed in your Talon.One deployment URL.
campaign_id = 789 # Integer | The ID of the campaign. It is displayed in your Talon.One deployment URL.

begin
  # Get summary of campaign store budgets
  result = api_instance.summarize_campaign_store_budget(application_id, campaign_id)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->summarize_campaign_store_budget: #{e}"
end
```

#### Using the summarize_campaign_store_budget_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<SummarizeCampaignStoreBudget200Response>, Integer, Hash)> summarize_campaign_store_budget_with_http_info(application_id, campaign_id)

```ruby
begin
  # Get summary of campaign store budgets
  data, status_code, headers = api_instance.summarize_campaign_store_budget_with_http_info(application_id, campaign_id)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <SummarizeCampaignStoreBudget200Response>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->summarize_campaign_store_budget_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **application_id** | **Integer** | The ID of the Application. It is displayed in your Talon.One deployment URL. |  |
| **campaign_id** | **Integer** | The ID of the campaign. It is displayed in your Talon.One deployment URL. |  |

### Return type

[**SummarizeCampaignStoreBudget200Response**](SummarizeCampaignStoreBudget200Response.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json


## transfer_loyalty_card

> transfer_loyalty_card(loyalty_program_id, loyalty_card_id, transfer_loyalty_card)

Transfer card data

Transfer loyalty card data, such as linked customers, loyalty balances and transactions, from a given loyalty card to a new, automatically created loyalty card.  **Important:**  - The original card is automatically blocked once the new card is created, and it cannot be activated again. - The default status of the new card is _active_. 

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
loyalty_program_id = 789 # Integer | Identifier of the card-based loyalty program containing the loyalty card. You can get the ID with the [List loyalty programs](https://docs.talon.one/management-api#tag/Loyalty/operation/getLoyaltyPrograms) endpoint. 
loyalty_card_id = 'loyalty_card_id_example' # String | Identifier of the loyalty card. You can get the identifier with the [List loyalty cards](https://docs.talon.one/management-api#tag/Loyalty-cards/operation/getLoyaltyCards) endpoint. 
transfer_loyalty_card = TalonOne::TransferLoyaltyCard.new({new_card_identifier: 'summer-loyalty-card-0543'}) # TransferLoyaltyCard | body

begin
  # Transfer card data
  api_instance.transfer_loyalty_card(loyalty_program_id, loyalty_card_id, transfer_loyalty_card)
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->transfer_loyalty_card: #{e}"
end
```

#### Using the transfer_loyalty_card_with_http_info variant

This returns an Array which contains the response data (`nil` in this case), status code and headers.

> <Array(nil, Integer, Hash)> transfer_loyalty_card_with_http_info(loyalty_program_id, loyalty_card_id, transfer_loyalty_card)

```ruby
begin
  # Transfer card data
  data, status_code, headers = api_instance.transfer_loyalty_card_with_http_info(loyalty_program_id, loyalty_card_id, transfer_loyalty_card)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => nil
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->transfer_loyalty_card_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **loyalty_program_id** | **Integer** | Identifier of the card-based loyalty program containing the loyalty card. You can get the ID with the [List loyalty programs](https://docs.talon.one/management-api#tag/Loyalty/operation/getLoyaltyPrograms) endpoint.  |  |
| **loyalty_card_id** | **String** | Identifier of the loyalty card. You can get the identifier with the [List loyalty cards](https://docs.talon.one/management-api#tag/Loyalty-cards/operation/getLoyaltyCards) endpoint.  |  |
| **transfer_loyalty_card** | [**TransferLoyaltyCard**](TransferLoyaltyCard.md) | body |  |

### Return type

nil (empty response body)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## update_account_collection

> <Collection> update_account_collection(collection_id, update_collection)

Update account-level collection

Edit the description of a given account-level collection and enable or disable the collection in the specified Applications.

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
collection_id = 789 # Integer | The ID of the collection. You can get it with the [List collections in account](#operation/listAccountCollections) endpoint.
update_collection = TalonOne::UpdateCollection.new # UpdateCollection | body

begin
  # Update account-level collection
  result = api_instance.update_account_collection(collection_id, update_collection)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->update_account_collection: #{e}"
end
```

#### Using the update_account_collection_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<Collection>, Integer, Hash)> update_account_collection_with_http_info(collection_id, update_collection)

```ruby
begin
  # Update account-level collection
  data, status_code, headers = api_instance.update_account_collection_with_http_info(collection_id, update_collection)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <Collection>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->update_account_collection_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **collection_id** | **Integer** | The ID of the collection. You can get it with the [List collections in account](#operation/listAccountCollections) endpoint. |  |
| **update_collection** | [**UpdateCollection**](UpdateCollection.md) | body |  |

### Return type

[**Collection**](Collection.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## update_achievement

> <Achievement> update_achievement(application_id, campaign_id, achievement_id, update_achievement)

Update achievement

Update the details of a specific achievement.

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
application_id = 789 # Integer | The ID of the Application. It is displayed in your Talon.One deployment URL.
campaign_id = 789 # Integer | The ID of the campaign. It is displayed in your Talon.One deployment URL.
achievement_id = 789 # Integer | The ID of the achievement. You can get this ID with the [List achievement](https://docs.talon.one/management-api#tag/Achievements/operation/listAchievements) endpoint.
update_achievement = TalonOne::UpdateAchievement.new # UpdateAchievement | body

begin
  # Update achievement
  result = api_instance.update_achievement(application_id, campaign_id, achievement_id, update_achievement)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->update_achievement: #{e}"
end
```

#### Using the update_achievement_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<Achievement>, Integer, Hash)> update_achievement_with_http_info(application_id, campaign_id, achievement_id, update_achievement)

```ruby
begin
  # Update achievement
  data, status_code, headers = api_instance.update_achievement_with_http_info(application_id, campaign_id, achievement_id, update_achievement)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <Achievement>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->update_achievement_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **application_id** | **Integer** | The ID of the Application. It is displayed in your Talon.One deployment URL. |  |
| **campaign_id** | **Integer** | The ID of the campaign. It is displayed in your Talon.One deployment URL. |  |
| **achievement_id** | **Integer** | The ID of the achievement. You can get this ID with the [List achievement](https://docs.talon.one/management-api#tag/Achievements/operation/listAchievements) endpoint. |  |
| **update_achievement** | [**UpdateAchievement**](UpdateAchievement.md) | body |  |

### Return type

[**Achievement**](Achievement.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## update_additional_cost

> <AccountAdditionalCost> update_additional_cost(additional_cost_id, new_additional_cost)

Update additional cost

Updates an existing additional cost. Once created, the only property of an additional cost that cannot be changed is the `name` property (or **API name** in the Campaign Manager). This restriction is in place to prevent accidentally breaking live integrations. 

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
additional_cost_id = 789 # Integer | The ID of the additional cost. You can find the ID the the Campaign Manager's URL when you display the details of the cost in **Account** > **Tools** > **Additional costs**. 
new_additional_cost = TalonOne::NewAdditionalCost.new({name: 'shippingFee', title: 'Shipping fee', description: 'A shipping fee'}) # NewAdditionalCost | body

begin
  # Update additional cost
  result = api_instance.update_additional_cost(additional_cost_id, new_additional_cost)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->update_additional_cost: #{e}"
end
```

#### Using the update_additional_cost_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<AccountAdditionalCost>, Integer, Hash)> update_additional_cost_with_http_info(additional_cost_id, new_additional_cost)

```ruby
begin
  # Update additional cost
  data, status_code, headers = api_instance.update_additional_cost_with_http_info(additional_cost_id, new_additional_cost)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <AccountAdditionalCost>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->update_additional_cost_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **additional_cost_id** | **Integer** | The ID of the additional cost. You can find the ID the the Campaign Manager&#39;s URL when you display the details of the cost in **Account** &gt; **Tools** &gt; **Additional costs**.  |  |
| **new_additional_cost** | [**NewAdditionalCost**](NewAdditionalCost.md) | body |  |

### Return type

[**AccountAdditionalCost**](AccountAdditionalCost.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## update_attribute

> <Attribute> update_attribute(attribute_id, new_attribute)

Update custom attribute

Update an existing custom attribute. Once created, the only property of a custom attribute that can be changed is the description.  To change the `type` or `name` property of a custom attribute, create a new attribute and update any relevant integrations and rules to use the new attribute. 

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
attribute_id = 789 # Integer | The ID of the attribute. You can find the ID in the Campaign Manager's URL when you display the details of an attribute in **Account** > **Tools** > **Attributes**.
new_attribute = TalonOne::NewAttribute.new({entity: 'Application', name: 'pageViewed', title: 'Page view event', type: 'string', description: 'Event triggered when a customer displays a page.', suggestions: ['suggestions_example'], editable: true}) # NewAttribute | body

begin
  # Update custom attribute
  result = api_instance.update_attribute(attribute_id, new_attribute)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->update_attribute: #{e}"
end
```

#### Using the update_attribute_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<Attribute>, Integer, Hash)> update_attribute_with_http_info(attribute_id, new_attribute)

```ruby
begin
  # Update custom attribute
  data, status_code, headers = api_instance.update_attribute_with_http_info(attribute_id, new_attribute)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <Attribute>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->update_attribute_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **attribute_id** | **Integer** | The ID of the attribute. You can find the ID in the Campaign Manager&#39;s URL when you display the details of an attribute in **Account** &gt; **Tools** &gt; **Attributes**. |  |
| **new_attribute** | [**NewAttribute**](NewAttribute.md) | body |  |

### Return type

[**Attribute**](Attribute.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## update_campaign

> <Campaign> update_campaign(application_id, campaign_id, update_campaign)

Update campaign

Update the given campaign.  **Important:** You cannot use this endpoint to update campaigns if [campaign staging and revisions](https://docs.talon.one/docs/product/applications/managing-general-settings#campaign-staging-and-revisions) is enabled for your Application. 

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
application_id = 789 # Integer | The ID of the Application. It is displayed in your Talon.One deployment URL.
campaign_id = 789 # Integer | The ID of the campaign. It is displayed in your Talon.One deployment URL.
update_campaign = TalonOne::UpdateCampaign.new({name: 'Summer promotions', tags: [Summer,  Shoes], features: [coupons,  loyalty], limits: [TalonOne::LimitConfig.new({action: 'createCoupon', limit: 1000, entities: [Coupon]})]}) # UpdateCampaign | body

begin
  # Update campaign
  result = api_instance.update_campaign(application_id, campaign_id, update_campaign)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->update_campaign: #{e}"
end
```

#### Using the update_campaign_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<Campaign>, Integer, Hash)> update_campaign_with_http_info(application_id, campaign_id, update_campaign)

```ruby
begin
  # Update campaign
  data, status_code, headers = api_instance.update_campaign_with_http_info(application_id, campaign_id, update_campaign)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <Campaign>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->update_campaign_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **application_id** | **Integer** | The ID of the Application. It is displayed in your Talon.One deployment URL. |  |
| **campaign_id** | **Integer** | The ID of the campaign. It is displayed in your Talon.One deployment URL. |  |
| **update_campaign** | [**UpdateCampaign**](UpdateCampaign.md) | body |  |

### Return type

[**Campaign**](Campaign.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## update_collection

> <Collection> update_collection(application_id, campaign_id, collection_id, update_campaign_collection)

Update campaign-level collection's description

Edit the description of a given campaign-level collection.

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
application_id = 789 # Integer | The ID of the Application. It is displayed in your Talon.One deployment URL.
campaign_id = 789 # Integer | The ID of the campaign. It is displayed in your Talon.One deployment URL.
collection_id = 789 # Integer | The ID of the collection. You can get it with the [List collections in Application](#operation/listCollectionsInApplication) endpoint.
update_campaign_collection = TalonOne::UpdateCampaignCollection.new # UpdateCampaignCollection | body

begin
  # Update campaign-level collection's description
  result = api_instance.update_collection(application_id, campaign_id, collection_id, update_campaign_collection)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->update_collection: #{e}"
end
```

#### Using the update_collection_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<Collection>, Integer, Hash)> update_collection_with_http_info(application_id, campaign_id, collection_id, update_campaign_collection)

```ruby
begin
  # Update campaign-level collection's description
  data, status_code, headers = api_instance.update_collection_with_http_info(application_id, campaign_id, collection_id, update_campaign_collection)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <Collection>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->update_collection_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **application_id** | **Integer** | The ID of the Application. It is displayed in your Talon.One deployment URL. |  |
| **campaign_id** | **Integer** | The ID of the campaign. It is displayed in your Talon.One deployment URL. |  |
| **collection_id** | **Integer** | The ID of the collection. You can get it with the [List collections in Application](#operation/listCollectionsInApplication) endpoint. |  |
| **update_campaign_collection** | [**UpdateCampaignCollection**](UpdateCampaignCollection.md) | body |  |

### Return type

[**Collection**](Collection.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## update_coupon

> <Coupon> update_coupon(application_id, campaign_id, coupon_id, update_coupon)

Update coupon

Update the specified coupon.  <div class=\"redoc-section\">   <p class=\"title\">Important</p>    <p>With this <code>PUT</code> endpoint, if you do not explicitly set a value for the <code>startDate</code>, <code>expiryDate</code>, and <code>recipientIntegrationId</code> properties in your request, it is automatically set to <code>null</code>.</p>  </div> 

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
application_id = 789 # Integer | The ID of the Application. It is displayed in your Talon.One deployment URL.
campaign_id = 789 # Integer | The ID of the campaign. It is displayed in your Talon.One deployment URL.
coupon_id = 'coupon_id_example' # String | The internal ID of the coupon code. You can find this value in the `id` property from the [List coupons](https://docs.talon.one/management-api#tag/Coupons/operation/getCouponsWithoutTotalCount) endpoint response. 
update_coupon = TalonOne::UpdateCoupon.new # UpdateCoupon | body

begin
  # Update coupon
  result = api_instance.update_coupon(application_id, campaign_id, coupon_id, update_coupon)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->update_coupon: #{e}"
end
```

#### Using the update_coupon_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<Coupon>, Integer, Hash)> update_coupon_with_http_info(application_id, campaign_id, coupon_id, update_coupon)

```ruby
begin
  # Update coupon
  data, status_code, headers = api_instance.update_coupon_with_http_info(application_id, campaign_id, coupon_id, update_coupon)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <Coupon>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->update_coupon_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **application_id** | **Integer** | The ID of the Application. It is displayed in your Talon.One deployment URL. |  |
| **campaign_id** | **Integer** | The ID of the campaign. It is displayed in your Talon.One deployment URL. |  |
| **coupon_id** | **String** | The internal ID of the coupon code. You can find this value in the &#x60;id&#x60; property from the [List coupons](https://docs.talon.one/management-api#tag/Coupons/operation/getCouponsWithoutTotalCount) endpoint response.  |  |
| **update_coupon** | [**UpdateCoupon**](UpdateCoupon.md) | body |  |

### Return type

[**Coupon**](Coupon.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## update_coupon_batch

> update_coupon_batch(application_id, campaign_id, update_coupon_batch)

Update coupons

Update all coupons or a specific batch of coupons in the given campaign. You can find the `batchId` on the **Coupons** page of your campaign in the Campaign Manager, or you can use [List coupons](#operation/getCouponsWithoutTotalCount).  <div class=\"redoc-section\">   <p class=\"title\">Important</p>    <ul>     <li>Only send sequential requests to this endpoint.</li>     <li>Requests to this endpoint time out after 30 minutes. If you hit a timeout, contact our support team.</li>     <li>With this <code>PUT</code> endpoint, if you do not explicitly set a value for the <code>startDate</code> and <code>expiryDate</code> properties in your request, it is automatically set to <code>null</code>.</li>   </ul>  </div>  To update a specific coupon, use [Update coupon](#operation/updateCoupon). 

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
application_id = 789 # Integer | The ID of the Application. It is displayed in your Talon.One deployment URL.
campaign_id = 789 # Integer | The ID of the campaign. It is displayed in your Talon.One deployment URL.
update_coupon_batch = TalonOne::UpdateCouponBatch.new # UpdateCouponBatch | body

begin
  # Update coupons
  api_instance.update_coupon_batch(application_id, campaign_id, update_coupon_batch)
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->update_coupon_batch: #{e}"
end
```

#### Using the update_coupon_batch_with_http_info variant

This returns an Array which contains the response data (`nil` in this case), status code and headers.

> <Array(nil, Integer, Hash)> update_coupon_batch_with_http_info(application_id, campaign_id, update_coupon_batch)

```ruby
begin
  # Update coupons
  data, status_code, headers = api_instance.update_coupon_batch_with_http_info(application_id, campaign_id, update_coupon_batch)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => nil
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->update_coupon_batch_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **application_id** | **Integer** | The ID of the Application. It is displayed in your Talon.One deployment URL. |  |
| **campaign_id** | **Integer** | The ID of the campaign. It is displayed in your Talon.One deployment URL. |  |
| **update_coupon_batch** | [**UpdateCouponBatch**](UpdateCouponBatch.md) | body |  |

### Return type

nil (empty response body)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined


## update_loyalty_card

> <LoyaltyCard> update_loyalty_card(loyalty_program_id, loyalty_card_id, update_loyalty_card)

Update loyalty card status

Update the status of the given loyalty card. A card can be _active_ or _inactive_.

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
loyalty_program_id = 789 # Integer | Identifier of the card-based loyalty program containing the loyalty card. You can get the ID with the [List loyalty programs](https://docs.talon.one/management-api#tag/Loyalty/operation/getLoyaltyPrograms) endpoint. 
loyalty_card_id = 'loyalty_card_id_example' # String | Identifier of the loyalty card. You can get the identifier with the [List loyalty cards](https://docs.talon.one/management-api#tag/Loyalty-cards/operation/getLoyaltyCards) endpoint. 
update_loyalty_card = TalonOne::UpdateLoyaltyCard.new({status: 'active'}) # UpdateLoyaltyCard | body

begin
  # Update loyalty card status
  result = api_instance.update_loyalty_card(loyalty_program_id, loyalty_card_id, update_loyalty_card)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->update_loyalty_card: #{e}"
end
```

#### Using the update_loyalty_card_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<LoyaltyCard>, Integer, Hash)> update_loyalty_card_with_http_info(loyalty_program_id, loyalty_card_id, update_loyalty_card)

```ruby
begin
  # Update loyalty card status
  data, status_code, headers = api_instance.update_loyalty_card_with_http_info(loyalty_program_id, loyalty_card_id, update_loyalty_card)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <LoyaltyCard>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->update_loyalty_card_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **loyalty_program_id** | **Integer** | Identifier of the card-based loyalty program containing the loyalty card. You can get the ID with the [List loyalty programs](https://docs.talon.one/management-api#tag/Loyalty/operation/getLoyaltyPrograms) endpoint.  |  |
| **loyalty_card_id** | **String** | Identifier of the loyalty card. You can get the identifier with the [List loyalty cards](https://docs.talon.one/management-api#tag/Loyalty-cards/operation/getLoyaltyCards) endpoint.  |  |
| **update_loyalty_card** | [**UpdateLoyaltyCard**](UpdateLoyaltyCard.md) | body |  |

### Return type

[**LoyaltyCard**](LoyaltyCard.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## update_referral

> <Referral> update_referral(application_id, campaign_id, referral_id, update_referral)

Update referral

Update the specified referral.

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
application_id = 789 # Integer | The ID of the Application. It is displayed in your Talon.One deployment URL.
campaign_id = 789 # Integer | The ID of the campaign. It is displayed in your Talon.One deployment URL.
referral_id = 'referral_id_example' # String | The ID of the referral code.
update_referral = TalonOne::UpdateReferral.new # UpdateReferral | body

begin
  # Update referral
  result = api_instance.update_referral(application_id, campaign_id, referral_id, update_referral)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->update_referral: #{e}"
end
```

#### Using the update_referral_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<Referral>, Integer, Hash)> update_referral_with_http_info(application_id, campaign_id, referral_id, update_referral)

```ruby
begin
  # Update referral
  data, status_code, headers = api_instance.update_referral_with_http_info(application_id, campaign_id, referral_id, update_referral)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <Referral>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->update_referral_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **application_id** | **Integer** | The ID of the Application. It is displayed in your Talon.One deployment URL. |  |
| **campaign_id** | **Integer** | The ID of the campaign. It is displayed in your Talon.One deployment URL. |  |
| **referral_id** | **String** | The ID of the referral code. |  |
| **update_referral** | [**UpdateReferral**](UpdateReferral.md) | body |  |

### Return type

[**Referral**](Referral.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## update_role_v2

> <RoleV2> update_role_v2(role_id, role_v2_base)

Update role

Update a specific role.

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
role_id = 789 # Integer | The ID of role.  **Note**: To find the ID of a role, use the [List roles](/management-api#tag/Roles/operation/listAllRolesV2) endpoint. 
role_v2_base = TalonOne::RoleV2Base.new # RoleV2Base | body

begin
  # Update role
  result = api_instance.update_role_v2(role_id, role_v2_base)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->update_role_v2: #{e}"
end
```

#### Using the update_role_v2_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<RoleV2>, Integer, Hash)> update_role_v2_with_http_info(role_id, role_v2_base)

```ruby
begin
  # Update role
  data, status_code, headers = api_instance.update_role_v2_with_http_info(role_id, role_v2_base)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <RoleV2>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->update_role_v2_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **role_id** | **Integer** | The ID of role.  **Note**: To find the ID of a role, use the [List roles](/management-api#tag/Roles/operation/listAllRolesV2) endpoint.  |  |
| **role_v2_base** | [**RoleV2Base**](RoleV2Base.md) | body |  |

### Return type

[**RoleV2**](RoleV2.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## update_store

> <Store> update_store(application_id, store_id, new_store)

Update store

Update store details for a specific store ID.

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
application_id = 789 # Integer | The ID of the Application. It is displayed in your Talon.One deployment URL.
store_id = 'store_id_example' # String | The ID of the store. You can get this ID with the [List stores](#tag/Stores/operation/listStores) endpoint. 
new_store = TalonOne::NewStore.new({name: 'South US store', description: 'This is the description of the store in south US.', integration_id: 'STORE-001'}) # NewStore | body

begin
  # Update store
  result = api_instance.update_store(application_id, store_id, new_store)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->update_store: #{e}"
end
```

#### Using the update_store_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<Store>, Integer, Hash)> update_store_with_http_info(application_id, store_id, new_store)

```ruby
begin
  # Update store
  data, status_code, headers = api_instance.update_store_with_http_info(application_id, store_id, new_store)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <Store>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->update_store_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **application_id** | **Integer** | The ID of the Application. It is displayed in your Talon.One deployment URL. |  |
| **store_id** | **String** | The ID of the store. You can get this ID with the [List stores](#tag/Stores/operation/listStores) endpoint.  |  |
| **new_store** | [**NewStore**](NewStore.md) | body |  |

### Return type

[**Store**](Store.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json


## update_user

> <User> update_user(user_id, update_user)

Update user

Update the details of a specific user.

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
user_id = 789 # Integer | The ID of the user.
update_user = TalonOne::UpdateUser.new # UpdateUser | body

begin
  # Update user
  result = api_instance.update_user(user_id, update_user)
  p result
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->update_user: #{e}"
end
```

#### Using the update_user_with_http_info variant

This returns an Array which contains the response data, status code and headers.

> <Array(<User>, Integer, Hash)> update_user_with_http_info(user_id, update_user)

```ruby
begin
  # Update user
  data, status_code, headers = api_instance.update_user_with_http_info(user_id, update_user)
  p status_code # => 2xx
  p headers # => { ... }
  p data # => <User>
rescue TalonOne::ApiError => e
  puts "Error when calling ManagementApi->update_user_with_http_info: #{e}"
end
```

### Parameters

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| **user_id** | **Integer** | The ID of the user. |  |
| **update_user** | [**UpdateUser**](UpdateUser.md) | body |  |

### Return type

[**User**](User.md)

### Authorization

[management_key](../README.md#management_key), [manager_auth](../README.md#manager_auth), [api_key_v1](../README.md#api_key_v1)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

