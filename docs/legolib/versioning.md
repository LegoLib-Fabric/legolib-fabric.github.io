---
layout: default
title: Versioning
parent: LegoLib
grand_parent: Documentation
nav_order: 1
permalink: docs/legolib/versioning
---
# Versioning  
{: .d-inline-block }  

LegoLib uses the following versioning style  
`major.minor.patch.release_type_short_code.build`  

## Version Types

| Version Type | Description                                                                                                                              |  
|:-------------|:-----------------------------------------------------------------------------------------------------------------------------------------|  
| Major                                                                                      | The major version only increases after a full rewrite.     |  
| Minor                                                                                      | The minor version increases every release cycle.           |  
| Patch                                                                                      | The patch version increases if a patch is required.        |  
| [Release Type](https://legolib-fabric.mclegoman.com/docs/legolib/versioning#release-types) | The release type changes throughout the development cycle. |  
| Build                                                                                      | The build version increases every release.                 |  


### Release Types  

| Release Type        | Short Code |  Long Code           | Description                                                                                                                                                                          |  
|:--------------------|:-----------|:---------------------|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|  
| Alpha               | `alpha`    |  `ALHPA`             | These releases are early in development and will often will contain bugs, and/or unfinished code.                                                                                    |  
| Beta                | `beta`     |  `BETA`              | These releases are nearing the end of development and may still contain bugs, and/or unfinished code.                                                                                |  
| Release Candidate   | `rc`       |  `RELEASE_CANDIDATE` | These releases are the final stage of development before release and are the most polished development builds. If no bugs are found these releases will turn into the final release. |  
| Release             | `release`  |  `RELEASE`           | These releases are the final stable version and are less likely to contain bugs.                                                                                                     |  