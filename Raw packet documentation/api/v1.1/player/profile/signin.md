---
title: /api/v1.1/player/profile/signin
parent: Raw Packet Documentation
layout: default
---

# /api/v1.1/player/profile/signin

## Description
An endpoint

### POST Arguments

| Parameter     | Example Value                                                                                                                                            | Description |
|---------------|----------------------------------------------------------------------------------------------------------------------------------------------------------|-------------|
| advertisingId | nope                                                                                                                                                     | Description |
| appsFlyerId   | nope                                                                                                                                                     | Description |
| buildNumber   | 2020.1217.02                                                                                                                                             | Description |
| clientVersion | 0.33.0                                                                                                                                                   | Description |
| coordinate    | {'latitude': 0, 'longitude': 0}                                                                                                                          | Description |
| deviceId      | 0d8d4802cc724c6686860938c394269b                                                                                                                         | Description |
| deviceOS      | Android                                                                                                                                                  | Description |
| deviceToken   | nope                                                                                                                                                     | Description |
| language      | en_GB                                                                                                                                                    | Description |
| sessionTicket | 1111111111111111-0000000000000000-0000000000000000-20CA2-0000000000000000-0000000000000000000000000000000000000000000                                    | Description |
| streams       | None                                                                                                                                                     | Description |


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

| Parameter           | Example Value    | Description |
|---------------------|------------------|-------------|
| authenticationToken | 1111111111111111 | Description |
| basePath            | /1               | Description |
| clientProperties    | {}               | Description |
| mixedReality        | None             | Description |
| mrToken             | None             | Description |
| streams             | None             | Description |
| tokens              | {}               | Description |
| updates             | {}               | Description |
