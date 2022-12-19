---
title: /api/v1.1/resourcepacks/[buildID]/default
parent: Raw Packet Documentation
layout: default
---

# /api/v1.1/resourcepacks/[buildID]/default

## Description
Tells the client information about the API

### URI Arguments

| Parameter   | Example Value | Description                    |
|-------------|---------------|--------------------------------|
| buildID | 2020.1217.02  | The Build ID of the client |


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

| Parameter                 | Example Value                                                                                                     | Description                                                              |
|---------------------------|-------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------|
| order                     | 0                                                                                                                 | Unknown, presumably the order of "overriding" of the resources, 0 is top |
| parsedResourcePackVersion | [2020,1214,4]                                                                                                     | The version of the resource pack (list format)                           |
| relativePath              | availableresourcepack/resourcepacks/dba38e59-091a-4826-b76a-a08d7de5a9e2-1301b0c257a311678123b9e7325d0d6c61db3c35 | The relative path to the resource pack file on the server                |
| resoucePackId             | dba38e59-091a-4826-b76a-a08d7de5a9e2                                                                              | The UUID of the resource pack                                            |
| resourcePackVersion       | 2020.1214.04                                                                                                      | The version of the resource pack (string format)                         |