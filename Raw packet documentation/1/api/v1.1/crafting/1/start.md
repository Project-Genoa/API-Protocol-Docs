---
title: /1/api/v1.1/crafting/1/start
parent: Raw Packet Documentation
layout: default
---

# /1/api/v1.1/crafting/1/start

## Description
An endpoint

### POST Arguments

| Parameter   | Example Value                                                                                | Description |
|-------------|----------------------------------------------------------------------------------------------|-------------|
| ingredients | [{'itemId': '8d9b5797-3c36-3219-b1e2-55343d111097', 'itemInstanceIds': None, 'quantity': 2}] | Description |
| multiplier  | 1                                                                                            | Description |
| recipeId    | 3455a9ba-543e-4599-a15e-9ccc3ca762bb                                                         | Description |
| sessionId   | 90320bb7-482f-4ceb-8f02-256d99603024                                                         | Description |


## Response
~~~json
{
    "updates": {
        "crafting": 66,
        "inventory": 66
    }
}
~~~

### result

| Parameter | Example Value                     | Description |
|-----------|-----------------------------------|-------------|
| updates   | {'crafting': 66, 'inventory': 66} | Description |
