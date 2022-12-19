---
title: /1/api/v1.1/tappables/tileX_tileY
parent: Raw Packet Documentation
layout: default
---

# /1/api/v1.1/tappables/tileX_tileY

## Description
An endpoint

### POST Arguments

| Parameter        | Example Value                                                    | Description |
|------------------|------------------------------------------------------------------|-------------|
| id               | 18d57bd2-c6aa-4506-8d14-0936d2f8a363                             | Description |
| playerCoordinate | {'latitude': 0, 'longitude': 0 }                                 | Description |


## Response
~~~json
{
    "result": {
        "token": {
            "lifetime": "Persistent",
            "clientType": "redeemtappable",
            "clientProperties": {},
            "rewards": {
                "experiencePoints": 40,
                "inventory": [
                    {
                        "id": "99daba35-8d70-2281-01ab-bf5471c6f877",
                        "amount": 1
                    },
                    {
                        "id": "99daba35-8d70-2281-01ab-bf5471c6f877",
                        "amount": 1
                    }
                ],
                "rubies": 1,
                "buildplates": [],
                "challenges": [],
                "personaItems": [],
                "utilityBlocks": []
            }
        },
        "updates": null
    },
    "expiration": null,
    "continuationToken": null,
    "updates": {
        "characterProfile": 62,
        "inventory": 62,
        "playerJournal": 62
    }
}
~~~

### result

| Parameter | Example Value                                                                                                                                                                                                                                                                                                                                               | Description |
|-----------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------|
| token     | {'lifetime': 'Persistent', 'clientType': 'redeemtappable', 'clientProperties': {}, 'rewards': {'experiencePoints': 40, 'inventory': [{'id': '99daba35-8d70-2281-01ab-bf5471c6f877', 'amount': 1}, {'id': '99daba35-8d70-2281-01ab-bf5471c6f877', 'amount': 1}], 'rubies': 1, 'buildplates': [], 'challenges': [], 'personaItems': [], 'utilityBlocks': []}} | Description |
| updates   | None                                                                                                                                                                                                                                                                                                                                                        | Description |
