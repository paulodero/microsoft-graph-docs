---
title: "connectedOrganization resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# connectedOrganization resource type

Namespace: microsoft.graph

**TODO: Add Description**


Inherits from [entity](../resources/entity.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List connectedOrganizations](../api/connectedorganization-list.md)|[connectedOrganization](../resources/connectedorganization.md) collection|Get a list of the [connectedOrganization](../resources/connectedorganization.md) objects and their properties.|
|[Create connectedOrganization](../api/connectedorganization-post-connectedorganizations.md)|[connectedOrganization](../resources/connectedorganization.md)|Create a new [connectedOrganization](../resources/connectedorganization.md) object.|
|[Get connectedOrganization](../api/connectedorganization-get.md)|[connectedOrganization](../resources/connectedorganization.md)|Read the properties and relationships of a [connectedOrganization](../resources/connectedorganization.md) object.|
|[Update connectedOrganization](../api/connectedorganization-update.md)|[connectedOrganization](../resources/connectedorganization.md)|Update the properties of a [connectedOrganization](../resources/connectedorganization.md) object.|
|[Delete connectedOrganization](../api/connectedorganization-delete.md)|None|Deletes a [connectedOrganization](../resources/connectedorganization.md) object.|
|[List externalSponsors](../api/connectedorganization-list-externalsponsors.md)|[directoryObject](../resources/directoryobject.md) collection|Get the directoryObjects from the externalSponsors navigation property.|
|[Create externalSponsors](../api/connectedorganization-post-externalsponsors.md)|[directoryObject](../resources/directoryobject.md)|Create a new externalSponsors object.|
|[Get externalSponsors](../api/connectedorganization-get-directoryobject.md)|[directoryObject](../resources/directoryobject.md)|Read the properties and relationships of a [directoryObject](../resources/directoryobject.md) object.|
|[Update externalSponsors](../api/connectedorganization-update-externalsponsors.md)|[directoryObject](../resources/directoryobject.md)|Update the properties of an externalSponsors object.|
|[Delete externalSponsors](../api/connectedorganization-delete-externalsponsors.md)|None|Delete a [directoryObject](../resources/directoryobject.md) object.|
|[List internalSponsors](../api/connectedorganization-list-internalsponsors.md)|[directoryObject](../resources/directoryobject.md) collection|Get the directoryObjects from the internalSponsors navigation property.|
|[Create internalSponsors](../api/connectedorganization-post-internalsponsors.md)|[directoryObject](../resources/directoryobject.md)|Create a new internalSponsors object.|
|[Get internalSponsors](../api/connectedorganization-get-directoryobject.md)|[directoryObject](../resources/directoryobject.md)|Read the properties and relationships of a [directoryObject](../resources/directoryobject.md) object.|
|[Update internalSponsors](../api/connectedorganization-update-internalsponsors.md)|[directoryObject](../resources/directoryobject.md)|Update the properties of an internalSponsors object.|
|[Delete internalSponsors](../api/connectedorganization-delete-internalsponsors.md)|None|Delete a [directoryObject](../resources/directoryobject.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|createdBy|String|**TODO: Add Description**|
|createdDateTime|DateTimeOffset|**TODO: Add Description**|
|description|String|**TODO: Add Description**|
|displayName|String|**TODO: Add Description**|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/entity.md)|
|identitySources|[identitySource](../resources/identitysource.md) collection|**TODO: Add Description**|
|modifiedBy|String|**TODO: Add Description**|
|modifiedDateTime|DateTimeOffset|**TODO: Add Description**|

## Relationships
|Relationship|Type|Description|
|:---|:---|:---|
|externalSponsors|[directoryObject](../resources/directoryobject.md) collection|**TODO: Add Description**|
|internalSponsors|[directoryObject](../resources/directoryobject.md) collection|**TODO: Add Description**|

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.connectedOrganization",
  "baseType": "microsoft.graph.entity",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.connectedOrganization",
  "id": "String (identifier)",
  "displayName": "String",
  "description": "String",
  "createdBy": "String",
  "createdDateTime": "String (timestamp)",
  "modifiedBy": "String",
  "modifiedDateTime": "String (timestamp)",
  "identitySources": [
    {
      "@odata.type": "microsoft.graph.azureActiveDirectoryTenant"
    }
  ]
}
```

