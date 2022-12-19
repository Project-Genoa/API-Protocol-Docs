---
title: /1/api/v1.1/player/tokens/2f3639da-0352-497d-bd15-805e0371de5b/redeem
parent: Raw Packet Documentation
layout: default
---

# /1/api/v1.1/player/tokens/2f3639da-0352-497d-bd15-805e0371de5b/redeem

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
        "itemid": "fc593f6c-c5a9-c608-d0aa-c89a42b6703d"
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
| clientProperties | {'itemid': 'fc593f6c-c5a9-c608-d0aa-c89a42b6703d'}                                              | Description |
| rewards          | {'inventory': [], 'buildplates': [], 'challenges': [], 'personaItems': [], 'utilityBlocks': []} | Description |
