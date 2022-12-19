---
title: /1/api/v1.1/boosts
parent: Raw Packet Documentation
layout: default
---

# /1/api/v1.1/boosts

## Description
An endpoint

### GET Arguments

[NO ARGUMENTS]


## Response
~~~json
{
    "result": {
        "potions": [
            {
                "enabled": true,
                "expiration": "2022-12-16T18:08:29.2231254Z",
                "instanceId": "e15b89cc-afac-427d-9d27-44e6b4217613",
                "itemId": "234432db-03c6-46f3-85c6-289cc710ca90"
            },
            {
                "enabled": true,
                "expiration": "2022-12-16T18:13:32.8928508Z",
                "instanceId": "6ea54d68-bd45-4d75-909a-edd112814f38",
                "itemId": "d9bbd707-8a7a-4edb-a85c-f8ec0c78a1f9"
            },
            null,
            null,
            null
        ],
        "miniFigs": [
            null,
            null,
            null,
            null,
            null
        ],
        "miniFigRecords": {},
        "activeEffects": [
            {
                "effect": {
                    "type": "TappableInteractionRadius",
                    "duration": "00:10:00",
                    "value": 35.0,
                    "unit": "Increment",
                    "targets": "Player",
                    "items": [],
                    "itemScenarios": [],
                    "activation": "Timed",
                    "modifiesType": null
                },
                "expiration": "2022-12-16T18:08:29.2231254Z"
            }
        ],
        "statusEffects": {
            "tappableInteractionRadius": 105,
            "experiencePointRate": null,
            "itemExperiencePointRates": null,
            "attackDamageRate": 35,
            "playerDefenseRate": null,
            "blockDamageRate": null,
            "maximumPlayerHealth": 20,
            "craftingSpeed": null,
            "smeltingFuelIntensity": null,
            "foodHealthRate": null
        },
        "scenarioBoosts": {
            "death": [
                {
                    "effects": [
                        {
                            "type": "RetainHotbar",
                            "duration": null,
                            "value": null,
                            "unit": null,
                            "targets": "Player",
                            "items": [],
                            "itemScenarios": [],
                            "activation": "Triggered",
                            "modifiesType": null
                        },
                        {
                            "type": "RetainExperiencePoints",
                            "duration": null,
                            "value": null,
                            "unit": null,
                            "targets": "Player",
                            "items": [],
                            "itemScenarios": [],
                            "activation": "Triggered",
                            "modifiesType": null
                        }
                    ],
                    "enabled": true,
                    "expiration": "2022-12-16T18:13:32.8928508Z",
                    "instanceId": "6ea54d68-bd45-4d75-909a-edd112814f38"
                }
            ]
        },
        "expiration": "2022-12-16T18:08:29.2231254Z"
    },
    "updates": {}
}
~~~

### result

| Parameter      | Example Value                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | Description |
|----------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------|
| potions        | [{'enabled': True, 'expiration': '2022-12-16T18:08:29.2231254Z', 'instanceId': 'e15b89cc-afac-427d-9d27-44e6b4217613', 'itemId': '234432db-03c6-46f3-85c6-289cc710ca90'}, {'enabled': True, 'expiration': '2022-12-16T18:13:32.8928508Z', 'instanceId': '6ea54d68-bd45-4d75-909a-edd112814f38', 'itemId': 'd9bbd707-8a7a-4edb-a85c-f8ec0c78a1f9'}, None, None, None]                                                                                                                                                        | Description |
| miniFigs       | [None, None, None, None, None]                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              | Description |
| miniFigRecords | {}                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          | Description |
| activeEffects  | [{'effect': {'type': 'TappableInteractionRadius', 'duration': '00:10:00', 'value': 35.0, 'unit': 'Increment', 'targets': 'Player', 'items': [], 'itemScenarios': [], 'activation': 'Timed', 'modifiesType': None}, 'expiration': '2022-12-16T18:08:29.2231254Z'}]                                                                                                                                                                                                                                                           | Description |
| statusEffects  | {'tappableInteractionRadius': 105, 'experiencePointRate': None, 'itemExperiencePointRates': None, 'attackDamageRate': 35, 'playerDefenseRate': None, 'blockDamageRate': None, 'maximumPlayerHealth': 20, 'craftingSpeed': None, 'smeltingFuelIntensity': None, 'foodHealthRate': None}                                                                                                                                                                                                                                      | Description |
| scenarioBoosts | {'death': [{'effects': [{'type': 'RetainHotbar', 'duration': None, 'value': None, 'unit': None, 'targets': 'Player', 'items': [], 'itemScenarios': [], 'activation': 'Triggered', 'modifiesType': None}, {'type': 'RetainExperiencePoints', 'duration': None, 'value': None, 'unit': None, 'targets': 'Player', 'items': [], 'itemScenarios': [], 'activation': 'Triggered', 'modifiesType': None}], 'enabled': True, 'expiration': '2022-12-16T18:13:32.8928508Z', 'instanceId': '6ea54d68-bd45-4d75-909a-edd112814f38'}]} | Description |
| expiration     | 2022-12-16T18:08:29.2231254Z                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | Description |
