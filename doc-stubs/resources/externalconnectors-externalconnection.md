---
title: "externalConnection resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# externalConnection resource type

Namespace: microsoft.graph.externalConnectors



**TODO: Add Description**


Inherits from [entity](../resources/externalconnectors-entity.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List externalConnections](../api/externalconnectors-externalconnection-list.md)|[microsoft.graph.externalConnectors.externalConnection](../resources/externalconnectors-externalconnection.md) collection|Get a list of the [externalConnection](../resources/externalconnectors-externalconnection.md) objects and their properties.|
|[Create externalConnection](../api/externalconnectors-externalconnection-post-connections.md)|[microsoft.graph.externalConnectors.externalConnection](../resources/externalconnectors-externalconnection.md)|Create a new [externalConnection](../resources/externalconnectors-externalconnection.md) object.|
|[Get externalConnection](../api/externalconnectors-externalconnection-get.md)|[microsoft.graph.externalConnectors.externalConnection](../resources/externalconnectors-externalconnection.md)|Read the properties and relationships of an [externalConnection](../resources/externalconnectors-externalconnection.md) object.|
|[Update externalConnection](../api/externalconnectors-externalconnection-update.md)|[microsoft.graph.externalConnectors.externalConnection](../resources/externalconnectors-externalconnection.md)|Update the properties of an [externalConnection](../resources/externalconnectors-externalconnection.md) object.|
|[Delete externalConnection](../api/externalconnectors-externalconnection-delete.md)|None|Deletes an [externalConnection](../resources/externalconnectors-externalconnection.md) object.|
|[List groups](../api/externalconnectors-externalconnection-list-groups.md)|[microsoft.graph.externalConnectors.externalGroup](../resources/externalconnectors-externalgroup.md) collection|Get the externalGroup resources from the groups navigation property.|
|[Create externalGroup](../api/externalconnectors-externalconnection-post-groups.md)|[microsoft.graph.externalConnectors.externalGroup](../resources/externalconnectors-externalgroup.md)|Create a new externalGroup object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|configuration|[microsoft.graph.externalConnectors.configuration](../resources/externalconnectors-configuration.md)|**TODO: Add Description**|
|description|String|**TODO: Add Description**|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/externalconnectors-entity.md).|
|name|String|**TODO: Add Description**|
|state|connectionState|**TODO: Add Description**. Possible values are: `draft`, `ready`, `obsolete`, `limitExceeded`, `unknownFutureValue`.|

## Relationships
|Relationship|Type|Description|
|:---|:---|:---|
|groups|[microsoft.graph.externalConnectors.externalGroup](../resources/externalconnectors-externalgroup.md) collection|**TODO: Add Description**|
|items|[microsoft.graph.externalConnectors.externalItem](../resources/externalconnectors-externalitem.md) collection|**TODO: Add Description**|
|operations|[microsoft.graph.externalConnectors.connectionOperation](../resources/externalconnectors-connectionoperation.md) collection|**TODO: Add Description**|
|schema|[schema](../resources/externalconnectors-schema.md)|**TODO: Add Description**|

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.externalConnectors.externalConnection",
  "baseType": "microsoft.graph.entity",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.externalConnectors.externalConnection",
  "id": "String (identifier)",
  "name": "String",
  "description": "String",
  "configuration": {
    "@odata.type": "microsoft.graph.externalConnectors.configuration"
  },
  "state": "String"
}
```
