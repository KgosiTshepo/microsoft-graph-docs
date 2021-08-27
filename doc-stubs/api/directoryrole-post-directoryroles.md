---
title: "Create directoryRole"
description: "Create a new directoryRole object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
ms.localizationpriority: medium
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Create directoryRole
Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

Create a new [directoryRole](../resources/directoryrole.md) object.

## Permissions
One of the following permissions is required to call this API. To learn more, including how to choose permissions, see [Permissions](/graph/permissions-reference).

|Permission type|Permissions (from least to most privileged)|
|:---|:---|
|Delegated (work or school account)|**TODO: Provide applicable permissions.**|
|Delegated (personal Microsoft account)|**TODO: Provide applicable permissions.**|
|Application|**TODO: Provide applicable permissions.**|

## HTTP request

<!-- {
  "blockType": "ignored"
}
-->
``` http
POST /directoryRoles
```

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|
|Content-Type|application/json. Required.|

## Request body
In the request body, supply a JSON representation of the [directoryRole](../resources/directoryrole.md) object.

The following table shows the properties that are required when you create the [directoryRole](../resources/directoryrole.md).

|Property|Type|Description|
|:---|:---|:---|
|id|String|**TODO: Add Description** Inherited from [directoryObject](../resources/directoryobject.md)|
|deletedDateTime|DateTimeOffset|**TODO: Add Description** Inherited from [directoryObject](../resources/directoryobject.md)|
|description|String|**TODO: Add Description**|
|displayName|String|**TODO: Add Description**|
|roleTemplateId|String|**TODO: Add Description**|



## Response

If successful, this method returns a `201 Created` response code and a [directoryRole](../resources/directoryrole.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "create_directoryrole_from_directoryroles"
}
-->
``` http
POST https://graph.microsoft.com/beta/directoryRoles
Content-Type: application/json
Content-length: 198

{
  "@odata.type": "#Microsoft.DirectoryServices.directoryRole",
  "deletedDateTime": "String (timestamp)",
  "description": "String",
  "displayName": "String",
  "roleTemplateId": "String"
}
```


### Response
>**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true,
  "@odata.type": "Microsoft.DirectoryServices.directoryRole"
}
-->
``` http
HTTP/1.1 201 Created
Content-Type: application/json

{
  "@odata.type": "#Microsoft.DirectoryServices.directoryRole",
  "id": "b5a74f24-4f24-b5a7-244f-a7b5244fa7b5",
  "deletedDateTime": "String (timestamp)",
  "description": "String",
  "displayName": "String",
  "roleTemplateId": "String"
}
```
