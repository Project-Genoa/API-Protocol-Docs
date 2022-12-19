---
title: /1/api/v1.1/player/utilityBlocks
parent: Raw Packet Documentation
layout: default
---

# /1/api/v1.1/player/utilityBlocks

## Description
An endpoint

### GET Arguments

[NO ARGUMENTS]


## Response
~~~json
{
    "result": {
        "crafting": {
            "1": {
                "sessionId": null,
                "recipeId": null,
                "output": null,
                "escrow": [],
                "completed": 0,
                "available": 0,
                "total": 0,
                "nextCompletionUtc": null,
                "totalCompletionUtc": null,
                "state": "Empty",
                "boostState": null,
                "unlockPrice": null,
                "streamVersion": 55
            },
            "2": {
                "sessionId": null,
                "recipeId": null,
                "output": null,
                "escrow": [],
                "completed": 0,
                "available": 0,
                "total": 0,
                "nextCompletionUtc": null,
                "totalCompletionUtc": null,
                "state": "Locked",
                "boostState": null,
                "unlockPrice": {
                    "cost": 10,
                    "discount": 0
                },
                "streamVersion": 55
            },
            "3": {
                "sessionId": null,
                "recipeId": null,
                "output": null,
                "escrow": [],
                "completed": 0,
                "available": 0,
                "total": 0,
                "nextCompletionUtc": null,
                "totalCompletionUtc": null,
                "state": "Locked",
                "boostState": null,
                "unlockPrice": {
                    "cost": 15,
                    "discount": 1
                },
                "streamVersion": 55
            }
        },
        "smelting": {
            "1": {
                "fuel": null,
                "burning": null,
                "hasSufficientFuel": null,
                "heatAppliedToCurrentItem": null,
                "sessionId": null,
                "recipeId": null,
                "output": null,
                "escrow": [],
                "completed": 0,
                "available": 0,
                "total": 0,
                "nextCompletionUtc": null,
                "totalCompletionUtc": null,
                "state": "Empty",
                "boostState": null,
                "unlockPrice": null,
                "streamVersion": 1
            },
            "2": {
                "fuel": null,
                "burning": null,
                "hasSufficientFuel": null,
                "heatAppliedToCurrentItem": null,
                "sessionId": null,
                "recipeId": null,
                "output": null,
                "escrow": [],
                "completed": 0,
                "available": 0,
                "total": 0,
                "nextCompletionUtc": null,
                "totalCompletionUtc": null,
                "state": "Locked",
                "boostState": null,
                "unlockPrice": {
                    "cost": 10,
                    "discount": 0
                },
                "streamVersion": 1
            },
            "3": {
                "fuel": null,
                "burning": null,
                "hasSufficientFuel": null,
                "heatAppliedToCurrentItem": null,
                "sessionId": null,
                "recipeId": null,
                "output": null,
                "escrow": [],
                "completed": 0,
                "available": 0,
                "total": 0,
                "nextCompletionUtc": null,
                "totalCompletionUtc": null,
                "state": "Locked",
                "boostState": null,
                "unlockPrice": {
                    "cost": 15,
                    "discount": 1
                },
                "streamVersion": 1
            }
        }
    },
    "updates": {}
}
~~~

### result

| Parameter | Example Value                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            | Description |
|-----------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------|
| crafting  | {'1': {'sessionId': None, 'recipeId': None, 'output': None, 'escrow': [], 'completed': 0, 'available': 0, 'total': 0, 'nextCompletionUtc': None, 'totalCompletionUtc': None, 'state': 'Empty', 'boostState': None, 'unlockPrice': None, 'streamVersion': 55}, '2': {'sessionId': None, 'recipeId': None, 'output': None, 'escrow': [], 'completed': 0, 'available': 0, 'total': 0, 'nextCompletionUtc': None, 'totalCompletionUtc': None, 'state': 'Locked', 'boostState': None, 'unlockPrice': {'cost': 10, 'discount': 0}, 'streamVersion': 55}, '3': {'sessionId': None, 'recipeId': None, 'output': None, 'escrow': [], 'completed': 0, 'available': 0, 'total': 0, 'nextCompletionUtc': None, 'totalCompletionUtc': None, 'state': 'Locked', 'boostState': None, 'unlockPrice': {'cost': 15, 'discount': 1}, 'streamVersion': 55}}                                                                                                                                                                                                                                                                                  | Description |
| smelting  | {'1': {'fuel': None, 'burning': None, 'hasSufficientFuel': None, 'heatAppliedToCurrentItem': None, 'sessionId': None, 'recipeId': None, 'output': None, 'escrow': [], 'completed': 0, 'available': 0, 'total': 0, 'nextCompletionUtc': None, 'totalCompletionUtc': None, 'state': 'Empty', 'boostState': None, 'unlockPrice': None, 'streamVersion': 1}, '2': {'fuel': None, 'burning': None, 'hasSufficientFuel': None, 'heatAppliedToCurrentItem': None, 'sessionId': None, 'recipeId': None, 'output': None, 'escrow': [], 'completed': 0, 'available': 0, 'total': 0, 'nextCompletionUtc': None, 'totalCompletionUtc': None, 'state': 'Locked', 'boostState': None, 'unlockPrice': {'cost': 10, 'discount': 0}, 'streamVersion': 1}, '3': {'fuel': None, 'burning': None, 'hasSufficientFuel': None, 'heatAppliedToCurrentItem': None, 'sessionId': None, 'recipeId': None, 'output': None, 'escrow': [], 'completed': 0, 'available': 0, 'total': 0, 'nextCompletionUtc': None, 'totalCompletionUtc': None, 'state': 'Locked', 'boostState': None, 'unlockPrice': {'cost': 15, 'discount': 1}, 'streamVersion': 1}} | Description |
