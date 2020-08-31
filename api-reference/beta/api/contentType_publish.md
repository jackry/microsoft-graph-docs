---
author: swapnil1993
ms.author: swapnil1993
ms.date: 08/29/2020
title: "ContentType Publish"
description: "Publish a site content type"
localization_priority: Normal
doc_type: apiPageType
ms.prod: "sharepoint"
---
# Publish a site content type
Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]
Publishes a site [contentType][]

## Permissions

One of the following permissions is required to call this API. To learn more, including how to choose permissions, see [Permissions](/graph/permissions_reference.md).

|Permission type      | Permissions (from least to most privileged)              |
|:--------------------|:---------------------------------------------------------|
|Delegated (work or school account) | Sites.FullControl.All    |
|Delegated (personal Microsoft account) | Sites.FullControl.All    |
|Application | Sites.FullControl.All |

## HTTP request

<!-- { "blockType": "request" } -->

```http
POST /sites/{siteId}/contentTypes/{contentTypeId}/publish
```

**Note:** The siteId should belong to a content type hub site.

## Example

```http
GET /sites/{siteId}/contentTypes/{contentTypeId}/publish
Content-Type: application/json
```

## Response

If successful, this call returns a `204 No Content` response.
<!-- { "blockType": "response" } -->

```http
HTTP/1.1 204 No Content
```

[contentType]: ../resources/contentType.md