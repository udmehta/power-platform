---
title: Microsoft Power Platform CLI canvas command group| Microsoft Docs
description: "Describes commands and parameters for the Microsoft Power Platform CLI canvas command group."
keywords: "pac cli"
ms.subservice: developer
author: snizar007
ms.author: snizar
ms.date: 9/18/2023
ms.reviewer: jdaly
ms.topic: reference
contributors: 
 - JimDaly
---
<!-- 
Do not edit this file. 
This file is generated by a program and any changes will be overwritten when this topic is re-generated.
Use the include files to add additional content to this topic.
-->
# pac canvas

Operating with Power Apps .msapp files

[!INCLUDE [canvas-intro](includes/canvas-intro.md)]

## Commands

|Command|Description|
|---------|---------|
|[pac canvas create](#pac-canvas-create)|Generate a canvas app from a custom connector|
|[pac canvas pack](#pac-canvas-pack)|(Preview) Pack sources into an msapp file|
|[pac canvas unpack](#pac-canvas-unpack)|(Preview) Extract an msapp file into sources|


## pac canvas create

Generate a canvas app from a custom connector

[!INCLUDE [canvas-create-intro](includes/canvas-create-intro.md)]


### Required Parameters for canvas create

#### `--msapp`

Path to .msapp file to be generated


### Optional Parameters for canvas create

#### `--connector-display-name`

The display name of the Connector to generate the Power App from.

#### `--connector-id`

The ID of the Connector to generate the Power App from.

#### `--environment`

The target Environment ID or URL. The default value is the environment of your currently active Dataverse Auth Profile.

[!INCLUDE [canvas-create-remarks](includes/canvas-create-remarks.md)]

## pac canvas pack

(Preview) Pack sources into an msapp file

[!INCLUDE [canvas-pack-intro](includes/canvas-pack-intro.md)]


### Required Parameters for canvas pack

#### `--msapp`

Path to .msapp file

#### `--sources`

Directory to sources to be packed

[!INCLUDE [canvas-pack-remarks](includes/canvas-pack-remarks.md)]

## pac canvas unpack

(Preview) Extract an msapp file into sources

[!INCLUDE [canvas-unpack-intro](includes/canvas-unpack-intro.md)]


### Required Parameters for canvas unpack

#### `--msapp`

Path to .msapp file


### Optional Parameters for canvas unpack

#### `--sources`

Directory to sources to be unpacked

[!INCLUDE [canvas-unpack-remarks](includes/canvas-unpack-remarks.md)]

[!INCLUDE [canvas-remarks](includes/canvas-remarks.md)]

### See also

[Microsoft Power Platform CLI Command Groups](index.md)<br />
[Microsoft Power Platform CLI overview](../introduction.md)