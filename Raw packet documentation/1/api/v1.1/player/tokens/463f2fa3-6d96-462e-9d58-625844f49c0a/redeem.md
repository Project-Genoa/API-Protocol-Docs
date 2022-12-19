---
title: /1/api/v1.1/player/tokens/463f2fa3-6d96-462e-9d58-625844f49c0a/redeem
parent: Raw Packet Documentation
layout: default
---

# /1/api/v1.1/player/tokens/463f2fa3-6d96-462e-9d58-625844f49c0a/redeem

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
        "itemid": "3f5cc89e-8f89-1440-d58f-2f6e05c054ac"
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
| clientProperties | {'itemid': '3f5cc89e-8f89-1440-d58f-2f6e05c054ac'}                                              | Description |
| rewards          | {'inventory': [], 'buildplates': [], 'challenges': [], 'personaItems': [], 'utilityBlocks': []} | Description |
