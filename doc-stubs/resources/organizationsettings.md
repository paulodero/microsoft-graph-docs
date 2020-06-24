---
title: "organizationSettings resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# organizationSettings resource type

Namespace: microsoft.graph

**TODO: Add Description**


Inherits from [entity](../resources/entity.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List organizationSettings](../api/organizationsettings-list.md)|[organizationSettings](../resources/organizationsettings.md) collection|Get a list of the [organizationSettings](../resources/organizationsettings.md) objects and their properties.|
|[Create organizationSettings](../api/organizationsettings-create.md)|[organizationSettings](../resources/organizationsettings.md)|Create a new [organizationSettings](../resources/organizationsettings.md) object.|
|[Get organizationSettings](../api/organizationsettings-get.md)|[organizationSettings](../resources/organizationsettings.md)|Read the properties and relationships of an [organizationSettings](../resources/organizationsettings.md) object.|
|[Update organizationSettings](../api/organizationsettings-update.md)|[organizationSettings](../resources/organizationsettings.md)|Update the properties of an [organizationSettings](../resources/organizationsettings.md) object.|
|[Delete organizationSettings](../api/organizationsettings-delete.md)|None|Deletes an [organizationSettings](../resources/organizationsettings.md) object.|
|[List profileCardProperties](../api/organizationsettings-list-profilecardproperties.md)|[profileCardProperty](../resources/profilecardproperty.md) collection|Get the profileCardProperties from the profileCardProperties navigation property.|
|[Create profileCardProperties](../api/organizationsettings-post-profilecardproperties.md)|[profileCardProperty](../resources/profilecardproperty.md)|Create a new profileCardProperties object.|
|[Get profileCardProperties](../api/organizationsettings-get-profilecardproperty.md)|[profileCardProperty](../resources/profilecardproperty.md)|Read the properties and relationships of a [profileCardProperty](../resources/profilecardproperty.md) object.|
|[Update profileCardProperties](../api/organizationsettings-update-profilecardproperties.md)|[profileCardProperty](../resources/profilecardproperty.md)|Update the properties of a profileCardProperties object.|
|[Delete profileCardProperties](../api/organizationsettings-delete-profilecardproperties.md)|None|Delete a [profileCardProperty](../resources/profilecardproperty.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/entity.md)|

## Relationships
|Relationship|Type|Description|
|:---|:---|:---|
|profileCardProperties|[profileCardProperty](../resources/profilecardproperty.md) collection|**TODO: Add Description**|

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.organizationSettings",
  "baseType": "microsoft.graph.entity",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.organizationSettings",
  "id": "String (identifier)"
}
```

