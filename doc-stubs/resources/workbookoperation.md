---
title: "workbookOperation resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# workbookOperation resource type

Namespace: microsoft.graph

**TODO: Add Description**


Inherits from [entity](../resources/entity.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List operations](../api/workbook-list-operations.md)|[workbookOperation](../resources/workbookoperation.md) collection|Get the workbookOperations from the operations navigation property.|
|[Create operations](../api/workbook-post-operations.md)|[workbookOperation](../resources/workbookoperation.md)|Create a new operations object.|
|[Update operations](../api/workbook-update-operations.md)|[workbookOperation](../resources/workbookoperation.md)|Update the properties of an operations object.|
|[Get operations](../api/workbook-get-workbookoperation.md)|[workbookOperation](../resources/workbookoperation.md)|Read the properties and relationships of a [workbookOperation](../resources/workbookoperation.md) object.|
|[Delete operations](../api/workbook-delete-operations.md)|None|Delete a [workbookOperation](../resources/workbookoperation.md) object.|
|[List workbookOperations](../api/workbookoperation-list.md)|[workbookOperation](../resources/workbookoperation.md) collection|Get a list of the [workbookOperation](../resources/workbookoperation.md) objects and their properties.|
|[Create workbookOperation](../api/workbookoperation-create.md)|[workbookOperation](../resources/workbookoperation.md)|Create a new [workbookOperation](../resources/workbookoperation.md) object.|
|[Get workbookOperation](../api/workbookoperation-get.md)|[workbookOperation](../resources/workbookoperation.md)|Read the properties and relationships of a [workbookOperation](../resources/workbookoperation.md) object.|
|[Update workbookOperation](../api/workbookoperation-update.md)|[workbookOperation](../resources/workbookoperation.md)|Update the properties of a [workbookOperation](../resources/workbookoperation.md) object.|
|[Delete workbookOperation](../api/workbookoperation-delete.md)|None|Deletes a [workbookOperation](../resources/workbookoperation.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|error|[workbookOperationError](../resources/workbookoperationerror.md)|**TODO: Add Description**|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/entity.md)|
|resourceLocation|String|**TODO: Add Description**|
|status|workbookOperationStatus|**TODO: Add Description**. Possible values are: `notStarted`, `running`, `succeeded`, `failed`.|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.workbookOperation",
  "baseType": "microsoft.graph.entity",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.workbookOperation",
  "id": "String (identifier)",
  "status": "String",
  "resourceLocation": "String",
  "error": {
    "@odata.type": "microsoft.graph.workbookOperationError"
  }
}
```

