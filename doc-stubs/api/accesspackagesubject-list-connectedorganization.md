---
title: "List connectedOrganization"
description: "Get the connectedOrganizations from the connectedOrganization navigation property."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# List connectedOrganization
Namespace: microsoft.graph

Get the connectedOrganizations from the connectedOrganization navigation property.

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
GET /connectedOrganizations
```

## Optional query parameters
This method supports some of the OData query parameters to help customize the response. For general information, see [OData query parameters](/graph/query-parameters).

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|

## Request body
Do not supply a request body for this method.

## Response

If successful, this method returns a `200 OK` response code and a collection of [connectedOrganization](../resources/connectedorganization.md) objects in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "get_connectedorganization"
}
-->
``` http
GET https://graph.microsoft.com/beta/connectedOrganizations
```


### Response
**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true,
  "@odata.type": "collection(microsoft.graph.connectedorganization)"
}
-->
``` http
HTTP/1.1 200 OK
Content-Type: application/json
{
  "value": [
    {
      "@odata.type": "#microsoft.graph.connectedOrganization",
      "id": "1bf2c3e0-c3e0-1bf2-e0c3-f21be0c3f21b",
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
  ]
}
```

