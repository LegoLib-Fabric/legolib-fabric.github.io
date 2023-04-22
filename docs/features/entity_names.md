---
layout: default
title: entity_names
parent: Features
grand_parent: Documentation
nav_order: 3
permalink: docs/features/entity_names
---
# entity_names  

This is the format of the entity_names JSON.  
entity_names allows for a custom texture for named entities.  


## JSON Format  

| Field        | Type   | Description                    |  
|:-------------|:-------|:-------------------------------|  
| `name`       | String | The custom name of the entity. |  


## Example  

File: `assets/legolib/textures/entity_names/allay/golden.json`  
```  
{  
    "name": "Golden"  
}  
```  
This example will change the texture of an allay named `Golden` to  
`legolib:textures/entity_names/allay/golden.png`  


## Entity Types  

{: .important }
Make sure the filename is the name in lowercase.  

| Entity Type   | JSON Location                                       | Texture Location                                            |  
|:--------------|:----------------------------------------------------|:------------------------------------------------------------|  
| `allay`       | `assets/legolib/entity_names/allay/name.json`       | `assets/legolib/textures/entity_names/allay/name.png`       |  
| `armor_stand` | `assets/legolib/entity_names/armor_stand/name.json` | `assets/legolib/textures/entity_names/armor_stand/name.png` |  
| `arrow`       | `assets/legolib/entity_names/arrow/name.json`       | `assets/legolib/textures/entity_names/arrow/name.png`       |  
| `axolotl`     | `assets/legolib/entity_names/axolotl/name.json`     | `assets/legolib/textures/entity_names/axolotl/name.png`     |  
| `bat`         | `assets/legolib/entity_names/bat/name.json`         | `assets/legolib/textures/entity_names/bat/name.png`         |  
| `bee`         | `assets/legolib/entity_names/bee/name.json`         | `assets/legolib/textures/entity_names/bee/name.png`         |  
| `blaze`       | `assets/legolib/entity_names/blaze/name.json`       | `assets/legolib/textures/entity_names/blaze/name.png`       |  
| `cat`         | `assets/legolib/entity_names/cat/name.json`         | `assets/legolib/textures/entity_names/cat/name.png`         |  
| `cave_spider` | `assets/legolib/entity_names/cave_spider/name.json` | `assets/legolib/textures/entity_names/cave_spider/name.png` |  
| `chicken`     | `assets/legolib/entity_names/chicken/name.json`     | `assets/legolib/textures/entity_names/chicken/name.png`     |  
| `cod`         | `assets/legolib/entity_names/cod/name.json`         | `assets/legolib/textures/entity_names/cod/name.png`         |  
| `cow`         | `assets/legolib/entity_names/cow/name.json`         | `assets/legolib/textures/entity_names/cow/name.png`         |  
| `creeper`     | `assets/legolib/entity_names/creeper/name.json`     | `assets/legolib/textures/entity_names/creeper/name.png`     |  


## Textures  

entity_names uses the same texture layout as the vanilla entity.  
[mcasset.cloud](https://mcasset.cloud) is a great resource to obtain vanilla resources.  


## Resource Pack Template  

Use our resource pack template to get started  

[Download Template](https://github.com/LegoLib-Fabric/community/tree/main/templates/entity_names){: .btn .btn-purple }  