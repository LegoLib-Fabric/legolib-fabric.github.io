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

| Entity Types |
|:-------------|
| `allay`      |


## Resource Pack Template

[Download Template](https://github.com/LegoLib-Fabric/community/tree/main/templates/entity_names){: .btn .btn-purple }