---
title: /1/api/v1.1/player/tokens/debf9ada-92e0-4559-89bc-8a34c0084708/redeem
parent: Raw Packet Documentation
layout: default
---

# /1/api/v1.1/player/tokens/debf9ada-92e0-4559-89bc-8a34c0084708/redeem

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
        "itemid": "41fabdc3-ee72-026d-6ab9-dbe3fcf34087"
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
| clientProperties | {'itemid': '41fabdc3-ee72-026d-6ab9-dbe3fcf34087'}                                              | Description |
| rewards          | {'inventory': [], 'buildplates': [], 'challenges': [], 'personaItems': [], 'utilityBlocks': []} | Description |
