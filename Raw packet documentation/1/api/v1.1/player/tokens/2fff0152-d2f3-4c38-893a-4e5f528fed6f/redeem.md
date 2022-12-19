---
title: /1/api/v1.1/player/tokens/2fff0152-d2f3-4c38-893a-4e5f528fed6f/redeem
parent: Raw Packet Documentation
layout: default
---

# /1/api/v1.1/player/tokens/2fff0152-d2f3-4c38-893a-4e5f528fed6f/redeem

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
        "itemid": "ee36c362-6711-f648-980e-96cc891bec56"
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
| clientProperties | {'itemid': 'ee36c362-6711-f648-980e-96cc891bec56'}                                              | Description |
| rewards          | {'inventory': [], 'buildplates': [], 'challenges': [], 'personaItems': [], 'utilityBlocks': []} | Description |
