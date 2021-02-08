---
title: "sharedEmailDomain resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# sharedEmailDomain resource type

Namespace: microsoft.graph

**TODO: Add Description**

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List sharedEmailDomains](../api/sharedemaildomain-list.md)|[sharedEmailDomain](../resources/sharedemaildomain.md) collection|Get a list of the [sharedEmailDomain](../resources/sharedemaildomain.md) objects and their properties.|
|[Create sharedEmailDomain](../api/sharedemaildomain-create.md)|[sharedEmailDomain](../resources/sharedemaildomain.md)|Create a new [sharedEmailDomain](../resources/sharedemaildomain.md) object.|
|[Get sharedEmailDomain](../api/sharedemaildomain-get.md)|[sharedEmailDomain](../resources/sharedemaildomain.md)|Read the properties and relationships of a [sharedEmailDomain](../resources/sharedemaildomain.md) object.|
|[Update sharedEmailDomain](../api/sharedemaildomain-update.md)|[sharedEmailDomain](../resources/sharedemaildomain.md)|Update the properties of a [sharedEmailDomain](../resources/sharedemaildomain.md) object.|
|[Delete sharedEmailDomain](../api/sharedemaildomain-delete.md)|None|Deletes a [sharedEmailDomain](../resources/sharedemaildomain.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|id|String|**TODO: Add Description**|
|provisioningStatus|String|**TODO: Add Description**|

## Relationships
|Relationship|Type|Description|
|:---|:---|:---|
|domainNameReferences|[directoryObject](../resources/directoryobject.md) collection|**TODO: Add Description**|

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.sharedEmailDomain",
  "baseType": "",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.sharedEmailDomain",
  "id": "String (identifier)",
  "provisioningStatus": "String"
}
```

