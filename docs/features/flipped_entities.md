---
layout: default
title: Flipped Entities
parent: Features
grand_parent: Documentation
nav_order: 2
permalink: docs/features/flipped_entities
---
# Flipped Entities  
{: .d-inline-block }  

ALPHA  
{: .label .label-yellow }  

flipped_entities allows for flipping upside down for named entities.  

{: .requires }  
> LegoLib: Features v1.0.0 or later.  
> LegoLib v3.0.0 or later.  

{: .note }  
> {% assign message = site.data.messages["exception_player"] %}  
> {{ message.message }}  

## JSON Format  

| Field        | Type    | Required | Description                       |  
|:-------------|:--------|:---------|:----------------------------------|  
| `name`       | String  | Yes      | The custom name of the entity.    |  
| `flipped`    | Boolean | Yes      | The flipped status of the entity. |  


## Example  

File: `assets/legolib/flipped_entities/mclegoman.json`  
```  
{  
    "name": "MCLegoMan",  
    "flipped": true  
}  
```  
This example will flip all entities named `MCLegoMan` upside down.  

## File Locations  

{: .important }  
> {% assign message = site.data.messages["lowercase_filename"] %}  
> {{ message.message }}  

| JSON Location                               |  
|:--------------------------------------------|  
| `assets/legolib/flipped_entities/name.json` |  


---


