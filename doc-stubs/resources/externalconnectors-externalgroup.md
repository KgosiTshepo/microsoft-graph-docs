---
title: "externalGroup resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# externalGroup resource type

Namespace: microsoft.graph.externalConnectors



**TODO: Add Description**


Inherits from [entity](../resources/externalconnectors-entity.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List externalGroups](../api/externalconnectors-externalgroup-list.md)|[microsoft.graph.externalConnectors.externalGroup](../resources/externalconnectors-externalgroup.md) collection|Get a list of the [externalGroup](../resources/externalconnectors-externalgroup.md) objects and their properties.|
|[Create externalGroup](../api/externalconnectors-externalgroup-create.md)|[microsoft.graph.externalConnectors.externalGroup](../resources/externalconnectors-externalgroup.md)|Create a new [externalGroup](../resources/externalconnectors-externalgroup.md) object.|
|[Get externalGroup](../api/externalconnectors-externalgroup-get.md)|[microsoft.graph.externalConnectors.externalGroup](../resources/externalconnectors-externalgroup.md)|Read the properties and relationships of an [externalGroup](../resources/externalconnectors-externalgroup.md) object.|
|[Update externalGroup](../api/externalconnectors-externalgroup-update.md)|[microsoft.graph.externalConnectors.externalGroup](../resources/externalconnectors-externalgroup.md)|Update the properties of an [externalGroup](../resources/externalconnectors-externalgroup.md) object.|
|[Delete externalGroup](../api/externalconnectors-externalgroup-delete.md)|None|Deletes an [externalGroup](../resources/externalconnectors-externalgroup.md) object.|
|[List members](../api/externalconnectors-externalgroup-list-members.md)|[microsoft.graph.externalConnectors.identity](../resources/externalconnectors-identity.md) collection|Get the identity resources from the members navigation property.|
|[Create identity](../api/externalconnectors-externalgroup-post-members.md)|[microsoft.graph.externalConnectors.identity](../resources/externalconnectors-identity.md)|Create a new identity object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|description|String|**TODO: Add Description**|
|displayName|String|**TODO: Add Description**|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/externalconnectors-entity.md).|

## Relationships
|Relationship|Type|Description|
|:---|:---|:---|
|members|[microsoft.graph.externalConnectors.identity](../resources/externalconnectors-identity.md) collection|**TODO: Add Description**|

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.externalConnectors.externalGroup",
  "baseType": "microsoft.graph.entity",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.externalConnectors.externalGroup",
  "id": "String (identifier)",
  "displayName": "String",
  "description": "String"
}
```
