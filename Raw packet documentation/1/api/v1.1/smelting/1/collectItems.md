---
title: /1/api/v1.1/smelting/1/collectItems
parent: Raw Packet Documentation
layout: default
---

# /1/api/v1.1/smelting/1/collectItems

## Description
An endpoint

### POST Arguments

[NO ARGUMENTS]


## Response
~~~json
{
    "result": {
        "rewards": {
            "inventory": [
                {
                    "id": "ee36c362-6711-f648-980e-96cc891bec56",
                    "amount": 1
                }
            ],
            "buildplates": [],
            "challenges": [],
            "personaItems": [],
            "utilityBlocks": []
        }
    },
    "updates": {
        "inventory": 77,
        "playerJournal": 77,
        "smelting": 77
    }
}
~~~

### result

| Parameter | Example Value                                                                                                                                              | Description |
|-----------|------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------|
| rewards   | {'inventory': [{'id': 'ee36c362-6711-f648-980e-96cc891bec56', 'amount': 1}], 'buildplates': [], 'challenges': [], 'personaItems': [], 'utilityBlocks': []} | Description |
