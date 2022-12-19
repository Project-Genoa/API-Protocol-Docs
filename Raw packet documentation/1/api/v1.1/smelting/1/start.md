---
title: /1/api/v1.1/smelting/1/start
parent: Raw Packet Documentation
layout: default
---

# /1/api/v1.1/smelting/1/start

## Description
An endpoint

### POST Arguments

| Parameter  | Example Value                                                                              | Description |
|------------|--------------------------------------------------------------------------------------------|-------------|
| fuel       | {'itemId': 'a1bf49f9-1f1f-2a4d-5f7b-c0c5ba833068', 'itemInstanceIds': None, 'quantity': 1} | Description |
| input      | {'itemId': 'a1bf49f9-1f1f-2a4d-5f7b-c0c5ba833068', 'itemInstanceIds': None, 'quantity': 1} | Description |
| multiplier | 1                                                                                          | Description |
| recipeId   | 54d16eeb-3ab7-a9eb-5f36-66a087bece72                                                       | Description |
| sessionId  | 4a8c16f3-49fb-4bf7-bf0a-f12407c94ed7                                                       | Description |


## Response
~~~json
{
    "updates": {
        "inventory": 74,
        "smelting": 74
    }
}
~~~

### result

| Parameter | Example Value                     | Description |
|-----------|-----------------------------------|-------------|
| updates   | {'inventory': 74, 'smelting': 74} | Description |
