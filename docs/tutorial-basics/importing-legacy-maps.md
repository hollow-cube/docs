---
sidebar_position: 6
---

# Importing Legacy Maps

## Explanation

Map Maker is based on a gamemode of the same name (previously known as Parkour Maker) from a 1.8 server known as Omega Parkour 
that ran from mid 2020 to late 2022. During that time, over **40,000** unique maps were created. If you were part of that era and would 
like you download your map or transfer it over to publish in the new Map Maker, this document will outline the steps needed to do so.

## Commands

### Viewing Legacy Maps

- /map list legacy \<page>
  - Lists a paginated set of your legacy maps in chat, 10 at a time.
    - You can input a specific page argument. If none is defined, the value is defaulted to 1.
    - Note that you must have a legacy map from the old Map Maker for this to work.

### Importing a Legacy Map

- /map import legacy \<ID>
  - Imports your defined legacy map into one of your map slots.
    - The ID argument is the four-digit alphanumeric legacy ID from the old Map Maker.
    - Note that you must be the owner of the legacy map and have an available empty map slot for this to work.

### Exporting a Legacy Map

- /map export legacy \<ID>
  - Exports your map into a downloadable zip file format.
    - The ID argument is the four-digit alphanumeric legacy ID from the old Map Maker.
    - Note that you must be the owner of the legacy map for this to work.