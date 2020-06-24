---
title: "Create profileCardProperties"
description: "Create a new profileCardProperties object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Create profileCardProperties
Namespace: microsoft.graph

Create a new profileCardProperties object.

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
POST /organization/{organizationId}/settings/profileCardProperties
```

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|
|Content-Type|application/json. Required.|

## Request body
In the request body, supply a JSON representation of the [profileCardProperty](../resources/profilecardproperty.md) object.

The following table shows the properties that are required when you create the [profileCardProperty](../resources/profilecardproperty.md).

|Property|Type|Description|
|:---|:---|:---|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/entity.md)|
|directoryPropertyName|String|**TODO: Add Description**|
|annotations|[profileCardAnnotation](../resources/profilecardannotation.md) collection|**TODO: Add Description**|



## Response

If successful, this method returns a `201 Created` response code and a [profileCardProperty](../resources/profilecardproperty.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "create_profilecardproperty_from_"
}
-->
``` http
POST https://graph.microsoft.com/beta/organization/{organizationId}/settings/profileCardProperties
Content-Type: application/json
Content-length: 201

{
  "@odata.type": "#microsoft.graph.profileCardProperty",
  "directoryPropertyName": "String",
  "annotations": [
    {
      "@odata.type": "microsoft.graph.profileCardAnnotation"
    }
  ]
}
```


### Response
**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true,
  "@odata.type": "microsoft.graph.profilecardproperty"
}
-->
``` http
HTTP/1.1 201 Created
Content-Type: application/json
{
  "@odata.type": "#microsoft.graph.profileCardProperty",
  "id": "b4a35c0c-5c0c-b4a3-0c5c-a3b40c5ca3b4",
  "directoryPropertyName": "String",
  "annotations": [
    {
      "@odata.type": "microsoft.graph.profileCardAnnotation"
    }
  ]
}
```

