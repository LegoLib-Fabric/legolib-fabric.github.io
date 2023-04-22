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

**Please Note:** Make sure the filename of the texture file is the lowercase version of the name.  

| Entity Type   | JSON Location                                       | Texture Location                                             |  
|:--------------|:----------------------------------------------------|:-------------------------------------------------------------|  
| `allay`       | `assets/legolib/entity_names/allay/name.json`       | `assets/legolib/textures/entity_names/allay/name.json`       |  
| `armor_stand` | `assets/legolib/entity_names/armor_stand/name.json` | `assets/legolib/textures/entity_names/armor_stand/name.json` |  
| `arrow`       | `assets/legolib/entity_names/arrow/name.json`       | `assets/legolib/textures/entity_names/arrow/name.json`       |  
| `axolotl`     | `assets/legolib/entity_names/axolotl/name.json`     | `assets/legolib/textures/entity_names/axolotl/name.json`     |  
| `bat`         | `assets/legolib/entity_names/bat/name.json`         | `assets/legolib/textures/entity_names/bat/name.json`         |  
| `bee`         | `assets/legolib/entity_names/bee/name.json`         | `assets/legolib/textures/entity_names/bee/name.json`         |  
| `blaze`       | `assets/legolib/entity_names/blaze/name.json`       | `assets/legolib/textures/entity_names/blaze/name.json`       |  
| `cat`         | `assets/legolib/entity_names/cat/name.json`         | `assets/legolib/textures/entity_names/cat/name.json`         |  
| `cave_spider` | `assets/legolib/entity_names/cave_spider/name.json` | `assets/legolib/textures/entity_names/cave_spider/name.json` |  
| `chicken`     | `assets/legolib/entity_names/chicken/name.json`     | `assets/legolib/textures/entity_names/chicken/name.json`     |  
| `cod`         | `assets/legolib/entity_names/cod/name.json`         | `assets/legolib/textures/entity_names/cod/name.json`         |  
| `cow`         | `assets/legolib/entity_names/cow/name.json`         | `assets/legolib/textures/entity_names/cow/name.json`         |  
| `creeper`     | `assets/legolib/entity_names/creeper/name.json`     | `assets/legolib/textures/entity_names/creeper/name.json`     |  


## Resource Pack Template  

[Download Template](https://github.com/LegoLib-Fabric/community/tree/main/templates/entity_names){: .btn .btn-purple }  