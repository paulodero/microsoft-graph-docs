---
title: "Update unifiedRoleManagementPolicyAuthenticationContextRule"
description: "Update the properties of an unifiedRoleManagementPolicyAuthenticationContextRule object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Update unifiedRoleManagementPolicyAuthenticationContextRule
Namespace: microsoft.graph

Update the properties of an [unifiedRoleManagementPolicyAuthenticationContextRule](../resources/unifiedrolemanagementpolicyauthenticationcontextrule.md) object.

## Permissions
One of the following permissions is required to call this API. To learn more, including how to choose permissions, see [Permissions](/graph/permissions-reference).

|Permission type|Permissions (from least to most privileged)|
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
PATCH /unifiedRoleManagementPolicyAuthenticationContextRule
```

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|
|Content-Type|application/json. Required.|

## Request body
In the request body, supply a JSON representation of the [unifiedRoleManagementPolicyAuthenticationContextRule](../resources/unifiedrolemanagementpolicyauthenticationcontextrule.md) object.

The following table shows the properties that are required when you update the [unifiedRoleManagementPolicyAuthenticationContextRule](../resources/unifiedrolemanagementpolicyauthenticationcontextrule.md).

|Property|Type|Description|
|:---|:---|:---|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/entity.md)|
|target|[unifiedRoleManagementPolicyRuleTarget](../resources/unifiedrolemanagementpolicyruletarget.md)|**TODO: Add Description** Inherited from [unifiedRoleManagementPolicyRule](../resources/unifiedrolemanagementpolicyrule.md)|
|isEnabled|Boolean|**TODO: Add Description**|
|claimValue|String|**TODO: Add Description**|



## Response

If successful, this method returns a `200 OK` response code and an updated [unifiedRoleManagementPolicyAuthenticationContextRule](../resources/unifiedrolemanagementpolicyauthenticationcontextrule.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "update_unifiedrolemanagementpolicyauthenticationcontextrule"
}
-->
``` http
PATCH https://graph.microsoft.com/beta/unifiedRoleManagementPolicyAuthenticationContextRule
Content-Type: application/json
Content-length: 245

{
  "@odata.type": "#microsoft.graph.unifiedRoleManagementPolicyAuthenticationContextRule",
  "target": {
    "@odata.type": "microsoft.graph.unifiedRoleManagementPolicyRuleTarget"
  },
  "isEnabled": "Boolean",
  "claimValue": "String"
}
```


### Response
**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true
}
-->
``` http
HTTP/1.1 200 OK
Content-Type: application/json

{
  "@odata.type": "#microsoft.graph.unifiedRoleManagementPolicyAuthenticationContextRule",
  "id": "9f663f8f-3f8f-9f66-8f3f-669f8f3f669f",
  "target": {
    "@odata.type": "microsoft.graph.unifiedRoleManagementPolicyRuleTarget"
  },
  "isEnabled": "Boolean",
  "claimValue": "String"
}
```

