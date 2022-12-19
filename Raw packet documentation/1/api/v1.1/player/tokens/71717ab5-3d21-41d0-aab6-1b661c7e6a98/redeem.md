---
title: /1/api/v1.1/player/tokens/71717ab5-3d21-41d0-aab6-1b661c7e6a98/redeem
parent: Raw Packet Documentation
layout: default
---

# /1/api/v1.1/player/tokens/71717ab5-3d21-41d0-aab6-1b661c7e6a98/redeem

## Description
An endpoint

### POST Arguments

[NO ARGUMENTS]


## Response
~~~json
{
    "lifetime": "Persistent",
    "clientType": "item.unlocked",
    "clientProperties": {
        "itemid": "234432db-03c6-46f3-85c6-289cc710ca90"
    },
    "rewards": {
        "inventory": [],
        "buildplates": [],
        "challenges": [],
        "personaItems": [],
        "utilityBlocks": []
    }
}
~~~

### result

| Parameter        | Example Value                                                                                   | Description |
|------------------|-------------------------------------------------------------------------------------------------|-------------|
| lifetime         | Persistent                                                                                      | Description |
| clientType       | item.unlocked                                                                                   | Description |
| clientProperties | {'itemid': '234432db-03c6-46f3-85c6-289cc710ca90'}                                              | Description |
| rewards          | {'inventory': [], 'buildplates': [], 'challenges': [], 'personaItems': [], 'utilityBlocks': []} | Description |
