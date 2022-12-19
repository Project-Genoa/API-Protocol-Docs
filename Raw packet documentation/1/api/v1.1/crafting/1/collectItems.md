---
title: /1/api/v1.1/crafting/1/collectItems
parent: Raw Packet Documentation
layout: default
---

# /1/api/v1.1/crafting/1/collectItems

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
                    "id": "41fabdc3-ee72-026d-6ab9-dbe3fcf34087",
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
        "crafting": 69,
        "inventory": 69,
        "playerJournal": 69
    }
}
~~~

### result

| Parameter | Example Value                                                                                                                                              | Description |
|-----------|------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------|
| rewards   | {'inventory': [{'id': '41fabdc3-ee72-026d-6ab9-dbe3fcf34087', 'amount': 1}], 'buildplates': [], 'challenges': [], 'personaItems': [], 'utilityBlocks': []} | Description |
