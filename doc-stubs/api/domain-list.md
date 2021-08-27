---
title: "List domains"
description: "Get a list of the domain objects and their properties."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
ms.localizationpriority: medium
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# List domains
Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

Get a list of the [domain](../resources/domain.md) objects and their properties.

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
GET /domains
```

## Optional query parameters
This method supports some of the OData query parameters to help customize the response. For general information, see [OData query parameters](/graph/query-parameters).

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|

## Request body
Do not supply a request body for this method.

## Response

If successful, this method returns a `200 OK` response code and a collection of [domain](../resources/domain.md) objects in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "list_domain"
}
-->
``` http
GET https://graph.microsoft.com/beta/domains
```


### Response
>**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true,
  "@odata.type": "Collection(Microsoft.DirectoryServices.domain)"
}
-->
``` http
HTTP/1.1 200 OK
Content-Type: application/json

{
  "value": [
    {
      "@odata.type": "#Microsoft.DirectoryServices.domain",
      "authenticationType": "String",
      "availabilityStatus": "String",
      "isAdminManaged": "Boolean",
      "isDefault": "Boolean",
      "isInitial": "Boolean",
      "isRoot": "Boolean",
      "isVerified": "Boolean",
      "id": "264021fc-21fc-2640-fc21-4026fc214026",
      "passwordNotificationWindowInDays": "Integer",
      "passwordValidityPeriodInDays": "Integer",
      "supportedServices": [
        "String"
      ],
      "state": {
        "@odata.type": "microsoft.graph.domainState"
      }
    }
  ]
}
```
