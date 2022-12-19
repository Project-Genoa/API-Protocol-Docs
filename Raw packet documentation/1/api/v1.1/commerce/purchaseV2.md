---
title: /1/api/v1.1/commerce/purchaseV2
parent: Raw Packet Documentation
layout: default
---

# /1/api/v1.1/commerce/purchaseV2

## Description
An endpoint

### POST Arguments

| Parameter             | Example Value                        | Description |
|-----------------------|--------------------------------------|-------------|
| expectedPurchasePrice | 2                                    | Description |
| itemId                | c025702d-5b96-4745-bb4b-93911ee8c32a | Description |


## Response
~~~json
{
    "result": {
        "purchased": 0,
        "earned": 5
    },
    "expiration": null,
    "continuationToken": null,
    "updates": {}
}
~~~

### result

| Parameter | Example Value | Description |
|-----------|---------------|-------------|
| purchased | 0             | Description |
| earned    | 5             | Description |
