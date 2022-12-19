---
title: player/environment
parent: Raw Packet Documentation
layout: default
---

# player/environment

## Description
Tells the client information about the API

## GET Arguments:

| Parameter   | Example Value | Description                    |
|-------------|---------------|--------------------------------|
| buildID | 2020.1217.02  | The Build ID of the client |

## Response
~~~json
{
    "continuationToken": null,
    "expiration": null,
    "result": {
        "serviceEnvironments": {
            "production": {
                "cdnUri": "http://192.168.1.1/cdn",
                "playfabTitleId": "20CA2",
                "serviceUri": "http://192.168.1.1"
            }
        },
        "supportedEnvironments": {
            "2020.1217.02": [
                "production"
            ]
        }
    },
    "updates": null
}
~~~

### serviceEnvironments

| Parameter      | Example Value          | Description                                                          |
|----------------|------------------------|----------------------------------------------------------------------|
| cdnUri         | http://192.168.1.1/cdn | The URI to the API's CDN                                             |
| playfabTitleId | 20CA2                  | The playfabtitleid that identifies the game when logging in via XBox |
| serviceUri     | http://192.168.1.1     | The URI pointing to the main API                                     |

### supportedEnvironments

| Parameter  | Example Value | Description                  |
|------------|---------------|------------------------------|
| build ID   | 2020.1217.02  | The build ID of the client   |
| build type | production    | The build type of the client |

