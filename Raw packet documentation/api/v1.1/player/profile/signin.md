---
title: /api/v1.1/player/profile/signin
parent: Raw Packet Documentation
layout: default
---

# /api/v1.1/player/profile/signin

## Description
The endpoint used to "sign in" the player with the API

### POST Arguments

| Parameter     | Example Value                                                                                                         | Description                        |
|---------------|-----------------------------------------------------------------------------------------------------------------------|------------------------------------|
| advertisingId | nope                                                                                                                  | The advertising ID of the user     |
| appsFlyerId   | nope                                                                                                                  | The "appsFlyerID" of the user      |
| buildNumber   | 2020.1217.02                                                                                                          | The client's build number          |
| clientVersion | 0.33.0                                                                                                                | The client's version               |
| coordinate    | {'latitude': 0, 'longitude': 0}                                                                                       | The location of the client         |
| deviceId      | nope                                                                                                                  | The deviceId of the client         |
| deviceOS      | Android                                                                                                               | The operating system of the client |
| deviceToken   | nope                                                                                                                  | The device token of the client     |
| language      | en_GB                                                                                                                 | The client's language              |
| sessionTicket | 1111111111111111-0000000000000000-0000000000000000-20CA2-0000000000000000-0000000000000000000000000000000000000000000 | An Playfab sessionTicket           |
| streams       | None                                                                                                                  | Unknown                            |


## Response
~~~json
{
    "result": {
        "authenticationToken": "1111111111111111",
        "basePath": "/1",
        "clientProperties": {},
        "mixedReality": null,
        "mrToken": null,
        "streams": null,
        "tokens": {},
        "updates": {}
    },
    "updates": {}
}
~~~

### result

| Parameter           | Example Value    | Description                                                                                     |
|---------------------|------------------|-------------------------------------------------------------------------------------------------|
| authenticationToken | 1111111111111111 | The authentication token that will be used in the `Authorization` header of all future requests |
| basePath            | /1               | The root path of the main API, used for load balancing                                          |
| clientProperties    | {}               | Unknown                                                                                         |
| mixedReality        | None             | _Unknown_                                                                                       |
| mrToken             | None             | Unknown                                                                                         |
| streams             | None             | Unknown                                                                                         |
| tokens              | {}               | Unknown                                                                                         |
| updates             | {}               | Unknown                                                                                         |
