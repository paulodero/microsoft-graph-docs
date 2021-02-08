---
title: "Get application"
description: "Read the properties and relationships of an application object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Get application
Namespace: microsoft.graph

Read the properties and relationships of an [application](../resources/application.md) object.

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
GET /applications/{applicationsId}
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

If successful, this method returns a `200 OK` response code and an [application](../resources/application.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "get_application"
}
-->
``` http
GET https://graph.microsoft.com/beta/applications/{applicationsId}
```


### Response
**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true,
  "@odata.type": "Microsoft.DirectoryServices.application"
}
-->
``` http
HTTP/1.1 200 OK
Content-Type: application/json

{
  "value": {
    "@odata.type": "#Microsoft.DirectoryServices.application",
    "id": "32c8592e-592e-32c8-2e59-c8322e59c832",
    "deletedDateTime": "String (timestamp)",
    "api": {
      "@odata.type": "microsoft.graph.apiApplication"
    },
    "appId": "String",
    "appMetadata": {
      "@odata.type": "microsoft.graph.appMetadata"
    },
    "appRoles": [
      {
        "@odata.type": "microsoft.graph.appRole"
      }
    ],
    "createdDateTime": "String (timestamp)",
    "description": "String",
    "isFallbackPublicClient": "Boolean",
    "identifierUris": [
      "String"
    ],
    "defaultRedirectUri": "String",
    "displayName": "String",
    "expectsForwardableIdTokens": "Boolean",
    "groupMembershipClaims": "String",
    "info": {
      "@odata.type": "microsoft.graph.informationalUrl"
    },
    "isDeviceOnlyAuthSupported": "Boolean",
    "keyCredentials": [
      {
        "@odata.type": "microsoft.graph.keyCredential"
      }
    ],
    "legacyAllowPassthroughUsers": "Boolean",
    "logo": "Stream",
    "microsoftPolicyGroup": "Boolean",
    "notes": "String",
    "optionalClaims": {
      "@odata.type": "microsoft.graph.optionalClaims"
    },
    "parentalControlSettings": {
      "@odata.type": "microsoft.graph.parentalControlSettings"
    },
    "passwordCredentials": [
      {
        "@odata.type": "microsoft.graph.passwordCredential"
      }
    ],
    "publicClient": {
      "@odata.type": "microsoft.graph.publicClientApplication"
    },
    "publisherDomain": "String",
    "requiredResourceAccess": [
      {
        "@odata.type": "microsoft.graph.requiredResourceAccess"
      }
    ],
    "servicePrincipalLifecyclePolicy": "String",
    "signInAudience": "String",
    "spa": {
      "@odata.type": "microsoft.graph.spaApplication"
    },
    "tags": [
      "String"
    ],
    "tokenEncryptionKeyId": "Guid",
    "trustedSubjectNameAndIssuers": [
      {
        "@odata.type": "microsoft.graph.trustedSubjectNameAndIssuer"
      }
    ],
    "uniqueName": "String",
    "web": {
      "@odata.type": "microsoft.graph.webApplication"
    }
  }
}
```

