---
title: /1/api/v1.1/features
parent: Raw Packet Documentation
layout: default
---

# /1/api/v1.1/features

## Description
The endpoint used to determine whether certain features should appear to be enabled on the client. If any of these are false, the feature will simply be disabled with the button (if applicable) being greyed-out and a "we're having trouble at the moment" modal when used.

### GET Arguments

[NO ARGUMENTS]


## Response
~~~json
{
    "result": {
        "workshop_enabled": true,
        "buildplates_enabled": true,
        "enable_ruby_purchasing": false,
        "commerce_enabled": true,
        "full_logging_enabled": true,
        "challenges_enabled": true,
        "craftingv2_enabled": true,
        "smeltingv2_enabled": true,
        "inventory_item_boosts_enabled": true,
        "player_health_enabled": true,
        "minifigs_enabled": true,
        "potions_enabled": true,
        "social_link_share_enabled": true,
        "social_link_launch_enabled": true,
        "encoded_join_enabled": true,
        "adventure_crystals_enabled": true,
        "item_limits_enabled": true,
        "adventure_crystals_ftue_enabled": true,
        "expire_crystals_on_cleanup_enabled": true,
        "challenges_v2_enabled": true,
        "player_journal_enabled": true,
        "player_stats_enabled": true,
        "activity_log_enabled": true,
        "seasons_enabled": true,
        "daily_login_enabled": true,
        "store_pdp_enabled": true,
        "hotbar_stacksplitting_enabled": true,
        "fancy_rewards_screen_enabled": true,
        "async_ecs_dispatcher": true,
        "adventure_oobe_enabled": true,
        "tappable_oobe_enabled": true,
        "map_permission_oobe_enabled": true,
        "journal_oobe_enabled": true,
        "freedom_oobe_enabled": true,
        "challenge_oobe_enabled": true,
        "level_rewards_v2_enabled": true,
        "content_driven_season_assets": true,
        "paid_earned_rubies_enabled": true
    },
    "expiration": null,
    "continuationTokem": null,
    "updates": {}
}
~~~

### result

[tba]

| Parameter                          | Example Value | Description |
|------------------------------------|---------------|-------------|
| workshop_enabled                   | True          | Description |
| buildplates_enabled                | True          | Description |
| enable_ruby_purchasing             | False         | Description |
| commerce_enabled                   | True          | Description |
| full_logging_enabled               | True          | Description |
| challenges_enabled                 | True          | Description |
| craftingv2_enabled                 | True          | Description |
| smeltingv2_enabled                 | True          | Description |
| inventory_item_boosts_enabled      | True          | Description |
| player_health_enabled              | True          | Description |
| minifigs_enabled                   | True          | Description |
| potions_enabled                    | True          | Description |
| social_link_share_enabled          | True          | Description |
| social_link_launch_enabled         | True          | Description |
| encoded_join_enabled               | True          | Description |
| adventure_crystals_enabled         | True          | Description |
| item_limits_enabled                | True          | Description |
| adventure_crystals_ftue_enabled    | True          | Description |
| expire_crystals_on_cleanup_enabled | True          | Description |
| challenges_v2_enabled              | True          | Description |
| player_journal_enabled             | True          | Description |
| player_stats_enabled               | True          | Description |
| activity_log_enabled               | True          | Description |
| seasons_enabled                    | True          | Description |
| daily_login_enabled                | True          | Description |
| store_pdp_enabled                  | True          | Description |
| hotbar_stacksplitting_enabled      | True          | Description |
| fancy_rewards_screen_enabled       | True          | Description |
| async_ecs_dispatcher               | True          | Description |
| adventure_oobe_enabled             | True          | Description |
| tappable_oobe_enabled              | True          | Description |
| map_permission_oobe_enabled        | True          | Description |
| journal_oobe_enabled               | True          | Description |
| freedom_oobe_enabled               | True          | Description |
| challenge_oobe_enabled             | True          | Description |
| level_rewards_v2_enabled           | True          | Description |
| content_driven_season_assets       | True          | Description |
| paid_earned_rubies_enabled         | True          | Description |
