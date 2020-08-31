---
author: swapnil1993
ms.author: swapnil1993
ms.date: 08/28/2020
title: DocumentSetContent
description: "The documentSetContent resource contains metadata about file present in default content location of a content."
localization_priority: Normal
doc_type: resourcePageType
ms.prod: ""
---
# DocumentSetContent resource type

The **documentSetContent** resource contains metadata about file present in default content location of a content type.

## JSON representation

Here is a JSON representation of a **documentSetContent** resource.
<!-- { "blockType": "resource", "@odata.type": "microsoft.graph.documentSetContent" } -->

```json
{
  "contentType": { "@type": "microsoft.graph.contentTypeInfo" },
  "fileName": "string",
  "folderName": "string"
}
```

## Properties

| Property name  | Type    | Description
|:---------------|:--------|:--------------------------------------------------
| contentType    | microsoft.graph.contentTypeInfo | Content type information of the file. 
| fileName      | string  | Name of the file in resource folder that should be added as a default content or a template in the document set  
| folderName         | string  | Folder name in which the file will be placed when a new document set is created in the library.