---
title: /player/environment
parent: Raw Packet Documentation
layout: default
---

# /player/environment

## Description
An endpoint

### GET Arguments

| Parameter   | Example Value | Description |
|-------------|---------------|-------------|
| buildNumber | 2020.1217.02  | Description |


## Response
~~~json
{
    "result": {
        "serviceEnvironments": {
            "production": {
                "serviceUri": "http://192.168.1.181:8080",
                "cdnUri": "http://192.168.1.181:8080/cdn",
                "playfabTitleId": "20CA2"
            }
        },
        "supportedEnvironments": {
            "2020.1217.02": [
                "production"
            ]
        }
    },
    "expiration": null,
    "continuationToken": null,
    "updates": null
}
~~~

### result

| Parameter             | Example Value                                                                                                                     | Description |
|-----------------------|-----------------------------------------------------------------------------------------------------------------------------------|-------------|
| serviceEnvironments   | {'production': {'serviceUri': 'http://192.168.1.181:8080', 'cdnUri': 'http://192.168.1.181:8080/cdn', 'playfabTitleId': '20CA2'}} | Description |
| supportedEnvironments | {'2020.1217.02': ['production']}                                                                                                  | Description |
