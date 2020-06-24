---
title: "entitlementManagement resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# entitlementManagement resource type

Namespace: microsoft.graph

**TODO: Add Description**


Inherits from [entity](../resources/entity.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[Get entitlementManagement](../api/entitlementmanagement-get.md)|[entitlementManagement](../resources/entitlementmanagement.md)|Read the properties and relationships of an [entitlementManagement](../resources/entitlementmanagement.md) object.|
|[Update entitlementManagement](../api/entitlementmanagement-update.md)|[entitlementManagement](../resources/entitlementmanagement.md)|Update the properties of an [entitlementManagement](../resources/entitlementmanagement.md) object.|
|[List connectedOrganizations](../api/entitlementmanagement-list-connectedorganizations.md)|[connectedOrganization](../resources/connectedorganization.md) collection|Get the connectedOrganizations from the connectedOrganizations navigation property.|
|[Create connectedOrganizations](../api/entitlementmanagement-post-connectedorganizations.md)|[connectedOrganization](../resources/connectedorganization.md)|Create a new connectedOrganizations object.|
|[Get connectedOrganizations](../api/entitlementmanagement-get-connectedorganization.md)|[connectedOrganization](../resources/connectedorganization.md)|Read the properties and relationships of a [connectedOrganization](../resources/connectedorganization.md) object.|
|[Update connectedOrganizations](../api/entitlementmanagement-update-connectedorganizations.md)|[connectedOrganization](../resources/connectedorganization.md)|Update the properties of a connectedOrganizations object.|
|[Delete connectedOrganizations](../api/entitlementmanagement-delete-connectedorganizations.md)|None|Delete a [connectedOrganization](../resources/connectedorganization.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/entity.md)|

## Relationships
|Relationship|Type|Description|
|:---|:---|:---|
|accessPackageAssignmentPolicies|[accessPackageAssignmentPolicy](../resources/accesspackageassignmentpolicy.md) collection|**TODO: Add Description**|
|accessPackageAssignmentRequests|[accessPackageAssignmentRequest](../resources/accesspackageassignmentrequest.md) collection|**TODO: Add Description**|
|accessPackageAssignmentResourceRoles|[accessPackageAssignmentResourceRole](../resources/accesspackageassignmentresourcerole.md) collection|**TODO: Add Description**|
|accessPackageAssignments|[accessPackageAssignment](../resources/accesspackageassignment.md) collection|**TODO: Add Description**|
|accessPackageCatalogs|[accessPackageCatalog](../resources/accesspackagecatalog.md) collection|**TODO: Add Description**|
|accessPackageResourceRequests|[accessPackageResourceRequest](../resources/accesspackageresourcerequest.md) collection|**TODO: Add Description**|
|accessPackageResourceRoleScopes|[accessPackageResourceRoleScope](../resources/accesspackageresourcerolescope.md) collection|**TODO: Add Description**|
|accessPackageResources|[accessPackageResource](../resources/accesspackageresource.md) collection|**TODO: Add Description**|
|accessPackages|[accessPackage](../resources/accesspackage.md) collection|**TODO: Add Description**|
|connectedOrganizations|[connectedOrganization](../resources/connectedorganization.md) collection|**TODO: Add Description**|
|settings|[entitlementManagementSettings](../resources/entitlementmanagementsettings.md)|**TODO: Add Description**|

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.entitlementManagement",
  "baseType": "microsoft.graph.entity",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.entitlementManagement",
  "id": "String (identifier)"
}
```

