---
title: "directoryObject: getAvailableExtensionProperties"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# directoryObject: getAvailableExtensionProperties
Namespace: microsoft.graph

**TODO: Add Description**

## Permissions
One of the following permissions is required to call this API. To learn more, including how to choose permissions, see [Permissions](/concepts/permissions-reference.md).

|Permission type|Permissions (from most to least privileged)|
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
POST /directoryObjects/getAvailableExtensionProperties
POST /stsPolicy/appliesTo/getAvailableExtensionProperties
POST /directory/deletedItems/getAvailableExtensionProperties
POST /groups/{groupsId}/owners/getAvailableExtensionProperties
POST /groups/{groupsId}/members/getAvailableExtensionProperties
POST /groups/{groupsId}/memberOf/getAvailableExtensionProperties
POST /devices/{devicesId}/memberOf/getAvailableExtensionProperties
POST /contacts/{contactsId}/memberOf/getAvailableExtensionProperties
POST /groups/{groupsId}/acceptedSenders/getAvailableExtensionProperties
POST /groups/{groupsId}/rejectedSenders/getAvailableExtensionProperties
POST /contacts/{contactsId}/directReports/getAvailableExtensionProperties
POST /devices/{devicesId}/registeredUsers/getAvailableExtensionProperties
POST /groups/{groupsId}/transitiveMembers/getAvailableExtensionProperties
POST /devices/{devicesId}/registeredOwners/getAvailableExtensionProperties
POST /groups/{groupsId}/transitiveMemberOf/getAvailableExtensionProperties
POST /devices/{devicesId}/transitiveMemberOf/getAvailableExtensionProperties
POST /contacts/{contactsId}/transitiveMemberOf/getAvailableExtensionProperties
POST /domains/{domainsId}/domainNameReferences/getAvailableExtensionProperties
POST /directoryRoles/{directoryRolesId}/members/getAvailableExtensionProperties
POST /groups/{groupsId}/membersWithLicenseErrors/getAvailableExtensionProperties
POST /servicePrincipals/{servicePrincipalsId}/owners/getAvailableExtensionProperties
POST /servicePrincipals/{servicePrincipalsId}/memberOf/getAvailableExtensionProperties
POST /servicePrincipals/{servicePrincipalsId}/ownedObjects/getAvailableExtensionProperties
POST /servicePrincipals/{servicePrincipalsId}/createdObjects/getAvailableExtensionProperties
POST /servicePrincipals/{servicePrincipalsId}/transitiveMemberOf/getAvailableExtensionProperties
```

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|
|Content-Type|application/json. Required.|

## Request body
In the request body, supply JSON representation of the parameters.

The following table shows the parameters that can be used with this action.

|Parameter|Type|Description|
|:---|:---|:---|
|isSyncedFromOnPremises|Boolean|**TODO: Add Description**|



## Response

If successful, this action returns a `200 OK` response code and a [extensionProperty](../resources/extensionproperty.md) collection in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "directoryobject_getavailableextensionproperties"
}
-->
``` http
POST https://graph.microsoft.com/v1.0/directoryObjects/getAvailableExtensionProperties

Content-Type: application/json
Content-length: 43

{
  "isSyncedFromOnPremises": "Boolean"
}
```


### Response
**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true,
  "@odata.type": "collection(microsoft.graph.extensionproperty)"
}
-->
``` http
HTTP/1.1 200 OK
Content-Type: application/json
{
  "value": [
    {
      "@odata.type": "#microsoft.graph.extensionProperty",
      "id": "String (identifier)",
      "deletedDateTime": "String (timestamp)",
      "appDisplayName": "String",
      "name": "String",
      "dataType": "String",
      "isSyncedFromOnPremises": "Boolean",
      "targetObjects": [
        "String"
      ]
    }
  ]
}
```

