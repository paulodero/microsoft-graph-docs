---
title: "profileCardProperty resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# profileCardProperty resource type

Namespace: microsoft.graph

**TODO: Add Description**


Inherits from [entity](../resources/entity.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List profileCardProperties](../api/organizationsettings-list-profilecardproperties.md)|[profileCardProperty](../resources/profilecardproperty.md) collection|Get the profileCardProperties from the profileCardProperties navigation property.|
|[Create profileCardProperties](../api/organizationsettings-post-profilecardproperties.md)|[profileCardProperty](../resources/profilecardproperty.md)|Create a new profileCardProperties object.|
|[Update profileCardProperties](../api/organizationsettings-update-profilecardproperties.md)|[profileCardProperty](../resources/profilecardproperty.md)|Update the properties of a profileCardProperties object.|
|[Get profileCardProperties](../api/organizationsettings-get-profilecardproperty.md)|[profileCardProperty](../resources/profilecardproperty.md)|Read the properties and relationships of a [profileCardProperty](../resources/profilecardproperty.md) object.|
|[Delete profileCardProperties](../api/organizationsettings-delete-profilecardproperties.md)|None|Delete a [profileCardProperty](../resources/profilecardproperty.md) object.|
|[List profileCardProperties](../api/profilecardproperty-list.md)|[profileCardProperty](../resources/profilecardproperty.md) collection|Get a list of the [profileCardProperty](../resources/profilecardproperty.md) objects and their properties.|
|[Create profileCardProperty](../api/profilecardproperty-create.md)|[profileCardProperty](../resources/profilecardproperty.md)|Create a new [profileCardProperty](../resources/profilecardproperty.md) object.|
|[Get profileCardProperty](../api/profilecardproperty-get.md)|[profileCardProperty](../resources/profilecardproperty.md)|Read the properties and relationships of a [profileCardProperty](../resources/profilecardproperty.md) object.|
|[Update profileCardProperty](../api/profilecardproperty-update.md)|[profileCardProperty](../resources/profilecardproperty.md)|Update the properties of a [profileCardProperty](../resources/profilecardproperty.md) object.|
|[Delete profileCardProperty](../api/profilecardproperty-delete.md)|None|Deletes a [profileCardProperty](../resources/profilecardproperty.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|annotations|[profileCardAnnotation](../resources/profilecardannotation.md) collection|**TODO: Add Description**|
|directoryPropertyName|String|**TODO: Add Description**|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/entity.md)|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.profileCardProperty",
  "baseType": "microsoft.graph.entity",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.profileCardProperty",
  "id": "String (identifier)",
  "directoryPropertyName": "String",
  "annotations": [
    {
      "@odata.type": "microsoft.graph.profileCardAnnotation"
    }
  ]
}
```

