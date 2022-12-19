---
title: /1/api/v1.1/player/tokens/67525020-241c-44a8-811c-bba7ebe88096/redeem
parent: Raw Packet Documentation
layout: default
---

# /1/api/v1.1/player/tokens/67525020-241c-44a8-811c-bba7ebe88096/redeem

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
        "itemid": "99daba35-8d70-2281-01ab-bf5471c6f877"
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
| clientProperties | {'itemid': '99daba35-8d70-2281-01ab-bf5471c6f877'}                                              | Description |
| rewards          | {'inventory': [], 'buildplates': [], 'challenges': [], 'personaItems': [], 'utilityBlocks': []} | Description |
