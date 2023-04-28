---
layout: default
title: entity_names
parent: Features
grand_parent: Documentation
nav_order: 1
permalink: docs/features/entity_names
---
# entity_names  
{: .d-inline-block }  

ALPHA  
{: .label .label-yellow }  

entity_names allows for a custom texture for named entities.  

{: .requires }  
> LegoLib: Features v1.0.0 or later.  
> LegoLib v3.0.0 or later.  

{: .warning }  
> {% assign message = site.data.messages["incomplete_documentation"] %}  
> {{ message.message }}  

## JSON Format  

| Field        | Type   | Required | Description                    |  
|:-------------|:-------|:---------|:-------------------------------|  
| `name`       | String | Yes      | The custom name of the entity. |  
| `entity`     | String | Yes      | The entity type.               |  


## Example  

File: `assets/legolib/textures/entity_names/allay/golden.json`  
```  
{  
    "name": "Golden",  
    "entity": "allay"  
}  
```  
This example will change the texture of an allay named `Golden` to  
`legolib:textures/entity_names/allay/golden.png`  


## File Locations  

{: .important }  
> {% assign message = site.data.messages["lowercase_filename"] %}  
> {{ message.message }}  

| Entity Type   | JSON Location                                       | Texture Location                                            |  
|:--------------|:----------------------------------------------------|:------------------------------------------------------------|  
| `allay`       | `assets/legolib/entity_names/allay_name.json`       | `assets/legolib/textures/entity_names/allay/name.png`       |  
| `armor_stand` | `assets/legolib/entity_names/armor_stand_name.json` | `assets/legolib/textures/entity_names/armor_stand/name.png` |  
| `arrow`       | `assets/legolib/entity_names/arrow_name.json`       | `assets/legolib/textures/entity_names/arrow/name.png`       |  
| `axolotl`     | `assets/legolib/entity_names/axolotl_name.json`     | `assets/legolib/textures/entity_names/axolotl/name.png`     |  
| `bat`         | `assets/legolib/entity_names/bat_name.json`         | `assets/legolib/textures/entity_names/bat/name.png`         |  
| `bee`         | `assets/legolib/entity_names/bee_name.json`         | `assets/legolib/textures/entity_names/bee/name.png`         |  
| `blaze`       | `assets/legolib/entity_names/blaze_name.json`       | `assets/legolib/textures/entity_names/blaze/name.png`       |  
| `cat`         | `assets/legolib/entity_names/cat_name.json`         | `assets/legolib/textures/entity_names/cat/name.png`         |  
| `cave_spider` | `assets/legolib/entity_names/cave_spider_name.json` | `assets/legolib/textures/entity_names/cave_spider/name.png` |  
| `chicken`     | `assets/legolib/entity_names/chicken_name.json`     | `assets/legolib/textures/entity_names/chicken/name.png`     |  
| `cod`         | `assets/legolib/entity_names/cod_name.json`         | `assets/legolib/textures/entity_names/cod/name.png`         |  
| `cow`         | `assets/legolib/entity_names/cow_name.json`         | `assets/legolib/textures/entity_names/cow/name.png`         |  
| `creeper`     | `assets/legolib/entity_names/creeper_name.json`     | `assets/legolib/textures/entity_names/creeper/name.png`     |  


## Textures  

entity_names uses the same texture layout as the vanilla entity.  

{: .recommendedtools }  
> [mcasset.cloud](https://mcasset.cloud) is great for exploring and extracting vanilla assets. [^1]  
> [Blockbench](https://www.blockbench.net) is great for creating and editing minecraft textures. [^2]   


## Resource Pack Template  

Use our resource pack template to get started  

[Download Template](https://github.com/LegoLib-Fabric/community/tree/main/templates/entity_names){: .btn .btn-purple }  


---
[^1]: We are not affiliated with [mcasset.cloud](https://mcasset.cloud).  
[^2]: We are not affiliated with [Blockbench](https://www.blockbench.net).  