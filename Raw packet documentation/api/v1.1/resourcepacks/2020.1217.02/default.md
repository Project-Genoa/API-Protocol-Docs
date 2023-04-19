---
title: /api/v1.1/resourcepacks/2020.1217.02/default
parent: Raw Packet Documentation
layout: default
---

# /api/v1.1/resourcepacks/2020.1217.02/default

## Description
Tells the client where to download the resource pack on the CDN

### GET Arguments

[NO ARGUMENTS]


## Response
~~~json
{
    "continuationToken": null,
    "expiration": null,
    "result": [
        {
            "order": 0,
            "parsedResourcePackVersion": [
                2020,
                1214,
                4
            ],
            "relativePath": "availableresourcepack/resourcepacks/dba38e59-091a-4826-b76a-a08d7de5a9e2-1301b0c257a311678123b9e7325d0d6c61db3c35",
            "resourcePackId": "dba38e59-091a-4826-b76a-a08d7de5a9e2",
            "resourcePackVersion": "2020.1214.04"
        }
    ],
    "updates": {}
}
~~~

### result

| Parameter                 | Example Value                                                                                                     | Description                                                                                                        |
|---------------------------|-------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------|
| order                     | 0                                                                                                                 | Unknown, most likely related to resource pack priority                                                             |
| parsedResourcePackVersion | [ 2020, 1214, 4 ]                                                                                                 | The machine-readable JSON representation of the resource pack version                                              |
| relativePath              | availableresourcepack/resourcepacks/dba38e59-091a-4826-b76a-a08d7de5a9e2-1301b0c257a311678123b9e7325d0d6c61db3c35 | The path to the resource pack file relative to the CDN's root, must be a zip file with a `genoa.mcpack` file in it |
| resourcePackId            | dba38e59-091a-4826-b76a-a08d7de5a9e2                                                                              | The resource pack's UUID                                                                                           |
| resourcePackVersion       | 2020.1214.04                                                                                                      | The human-readable string representation of the resource pack format                                               |