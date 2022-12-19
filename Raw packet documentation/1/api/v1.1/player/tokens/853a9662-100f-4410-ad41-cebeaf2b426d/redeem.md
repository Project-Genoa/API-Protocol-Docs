---
title: /1/api/v1.1/player/tokens/853a9662-100f-4410-ad41-cebeaf2b426d/redeem
parent: Raw Packet Documentation
layout: default
---

# /1/api/v1.1/player/tokens/853a9662-100f-4410-ad41-cebeaf2b426d/redeem

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
        "itemid": "5fa4c9bd-e618-a2e4-96e6-639f7cffc4e4"
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
| clientProperties | {'itemid': '5fa4c9bd-e618-a2e4-96e6-639f7cffc4e4'}                                              | Description |
| rewards          | {'inventory': [], 'buildplates': [], 'challenges': [], 'personaItems': [], 'utilityBlocks': []} | Description |
