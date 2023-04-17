---
title: Boost Minifigs
layout: default
parent: General Documentation
nav_order: 2
---

This page describes the Boost Minifigs
<br/>
<br/>
Boost Minifigs are NFC tags attached to toys which can be used to obtain boosts in Minecraft Earth.

Boost Minifigs each contain an NFC tag which points towards a unique URL.

The format of the URL is `pid.mattel/\<B64>`

the B64 is a 24bit binary content encoded in base64.

## Format Description
As an example, we'll be looking at "Pigging Out Pig": `pid.mattel/AgBBsvJnU84rAF6jiQkErLvS02eAAAAH`


`02 00` `41 B2 F2 67` 53 `CE 2B 00 5E` a3 89 09 `04 AC BB D2 D3 67 80` 00 00 07

it is split up into 3 groups:

`02 00` - HEADER
`41 B2 F2 67` - The Boost ID as defined in JSON encoded as an unsigned 32-bit big-endian integer (1102246503 - "pigging out pig")
`CE 2B 00 5E` - Date and time of manufacture as little-endian UNIX 32-bit datetime or smth idk
`04 AC BB D2 D3 67 80` - The 7-byte UID of the NFC tag (NTAG 213)
the rest is unknown

## Creating Boost Minis
Minecraft Earth only checks the Base64 string itself so it can be spoofed even if the `pid.mattel` URL does not point anywhere.

Boost Minis only need to be NFC tags which point to a URL with the format: `pid.mattel/AgBB....U84rAF6jiQkErLvS02eAAAAH` (Using Pigging Out Pig as an example)

The four dots will need to be replaced with the boost's ID converted to Base64, as provided in this table:
| Boost Figurine         | Boost Type                             | Boost ID   | Boost ID (Base64) |
|------------------------|----------------------------------------|------------|-------------------|
| Seeking Dolphin        | Tappable Interaction Radius +35m - 10m | 1102246031 |                   |
| Crafting Villager      | Tappable Interaction Radius +35m - 10m | 1102200076 |                   |
| Crafting Steve         | Tappable Interaction Radius +35m - 10m | 1102246335 |                   |
| Spawning Chicken (2)   | Mob Collection XP +50% - 10m           | 1102199976 |                   |
| Undying Evoker         | Hotbar Retention                       | 1102200015 |                   |
| Mining Creeper         | Mining Speed +25% - 10m                | 1102200014 |                   |
| Enraged Golem          | Defense +25% - 10m                     | 1102246373 |                   |
| Smelting Blaze         | Tappable Interaction Radius +35m - 10m | 1102246010 |                   |
| Regenerating Mooshroom | Max Health +10% - 10m                  | 1102245998 |                   |
| Attacking Alex         | Attack Damage +25% - 10m               | 1102246352 |                   |
| Fishing Polar Bear     | Healthed Gained From Food +50% - 10m   | 1102210222 |                   |
| Defending Alex         | Defense +25% - 10m                     | 1102200013 |                   |
| Snacking Rabbit        | Max Health +10% - 10m                  | 1102200016 |                   |
| Poison Enderman        | Attack Damage +25% - 10m               | 1102327946 |                   |
| Attacking Steve        | Attack Damage +25% - 10m               | 1102199975 |                   |
| Slowed Creeper         | Adventure XP +50% - 10m                | 1102246361 |                   |
| Seeking Wolf           | Tappable Interaction Radius +35m - 10m | 1102210221 |                   |
| Snacking Rabbit (2)    | Max Health +10% - 10m                  | 1102210223 |                   |
| Hoarding Skeleton      | Backpack Retention                     | 1102200075 |                   |
| Attacking Steve (2)    | Attack Damage +25% - 10m               | 1102210224 |                   |
| Healing Witch          | Max Health +10% - 10m                  | 1102218105 |                   |
| Repairing Villager     | Tappable Interaction Radius +35m - 10m | 1102246467 |                   |
| Pigging Out Pig        | Max Health +10% - 10m                  | 1102246503 |                   |

(Base64 values to be added...)