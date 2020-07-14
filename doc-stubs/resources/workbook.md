---
title: "workbook resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# workbook resource type

Namespace: microsoft.graph

**TODO: Add Description**


Inherits from [entity](../resources/entity.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List workbooks](../api/workbook-list.md)|[workbook](../resources/workbook.md) collection|Get a list of the [workbook](../resources/workbook.md) objects and their properties.|
|[Create workbook](../api/workbook-create.md)|[workbook](../resources/workbook.md)|Create a new [workbook](../resources/workbook.md) object.|
|[Get workbook](../api/workbook-get.md)|[workbook](../resources/workbook.md)|Read the properties and relationships of a [workbook](../resources/workbook.md) object.|
|[Update workbook](../api/workbook-update.md)|[workbook](../resources/workbook.md)|Update the properties of a [workbook](../resources/workbook.md) object.|
|[Delete workbook](../api/workbook-delete.md)|None|Deletes a [workbook](../resources/workbook.md) object.|
|[sessionInfoResource](../api/workbook-sessioninforesource.md)|[workbookSessionInfo](../resources/workbooksessioninfo.md)|**TODO: Add Description**|
|[List operations](../api/workbook-list-operations.md)|[workbookOperation](../resources/workbookoperation.md) collection|Get the workbookOperations from the operations navigation property.|
|[Create operations](../api/workbook-post-operations.md)|[workbookOperation](../resources/workbookoperation.md)|Create a new operations object.|
|[Get operations](../api/workbook-get-workbookoperation.md)|[workbookOperation](../resources/workbookoperation.md)|Read the properties and relationships of a [workbookOperation](../resources/workbookoperation.md) object.|
|[Update operations](../api/workbook-update-operations.md)|[workbookOperation](../resources/workbookoperation.md)|Update the properties of an operations object.|
|[Delete operations](../api/workbook-delete-operations.md)|None|Delete a [workbookOperation](../resources/workbookoperation.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/entity.md)|

## Relationships
|Relationship|Type|Description|
|:---|:---|:---|
|application|[workbookApplication](../resources/workbookapplication.md)|**TODO: Add Description**|
|comments|[workbookComment](../resources/workbookcomment.md) collection|**TODO: Add Description**|
|functions|[workbookFunctions](../resources/workbookfunctions.md)|**TODO: Add Description**|
|names|[workbookNamedItem](../resources/workbooknameditem.md) collection|**TODO: Add Description**|
|operations|[workbookOperation](../resources/workbookoperation.md) collection|**TODO: Add Description**|
|tables|[workbookTable](../resources/workbooktable.md) collection|**TODO: Add Description**|
|worksheets|[workbookWorksheet](../resources/workbookworksheet.md) collection|**TODO: Add Description**|

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.workbook",
  "baseType": "microsoft.graph.entity",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.workbook",
  "id": "String (identifier)"
}
```

