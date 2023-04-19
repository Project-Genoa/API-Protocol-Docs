---
title: /player/environment
parent: Raw Packet Documentation
layout: default
---

# /player/environment

## Description
This is the main locator endpoint, it tells the client what server it should connect to for the `service` (main API) and the `cdnUri` (CDN server)

It also tells the client the playfab ID and the environments supported by the server. If the app's version is not in the list of supported environments, an update prompt will show


### GET Arguments

| Parameter   | Example Value |       Description      |
|-------------|---------------|------------------------|
| buildNumber | 2020.1217.02  | The buildID of the app |


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

| Parameter      | Example Value                 | Description                                        |
|----------------|-------------------------------|----------------------------------------------------|
| serviceUri     | http://192.168.1.181:8080     | The main API URI                                   |
| cdnUri         | http://192.168.1.181:8080/cdn | The URI to the CDN Root                            |
| playfabTitleId | 20CA2                         | The Playfab Title ID used to obtain user info, etc |