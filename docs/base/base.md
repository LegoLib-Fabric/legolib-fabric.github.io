---
layout: default
title: Base
parent: Documentation
nav_order: 2
has_children: false
permalink: docs/base
---
# Base  
{: .d-inline-block }  

Contains functions required by all modules.  

{: .latestrelease }  
>  
> {: .release}  
> {% assign release = site.data.base["release"] %}  
> {{ release.name }} {{ release.version }}  
>  
> {: .development}  
> {% assign development = site.data.base["development"] %}  
> {{ development.name }} {{ development.version }}  

{: .warning }  
> {% assign release = site.data.messages["incomplete_documentation"] %}  
> {{ release.message }}  