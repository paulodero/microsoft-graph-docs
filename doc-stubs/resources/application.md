---
title: "application resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# application resource type

Namespace: microsoft.graph

**TODO: Add Description**


Inherits from [directoryObject](../resources/directoryobject.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List applications](../api/application-list.md)|[application](../resources/application.md) collection|Get a list of the [application](../resources/application.md) objects and their properties.|
|[Create application](../api/application-post-applications.md)|[application](../resources/application.md)|Create a new [application](../resources/application.md) object.|
|[Get application](../api/application-get.md)|[application](../resources/application.md)|Read the properties and relationships of an [application](../resources/application.md) object.|
|[Update application](../api/application-update.md)|[application](../resources/application.md)|Update the properties of an [application](../resources/application.md) object.|
|[Delete application](../api/application-delete.md)|None|Deletes an [application](../resources/application.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|api|[apiApplication](../resources/apiapplication.md)|**TODO: Add Description**|
|appId|String|**TODO: Add Description**|
|appMetadata|[appMetadata](../resources/appmetadata.md)|**TODO: Add Description**|
|appRoles|[appRole](../resources/approle.md) collection|**TODO: Add Description**|
|createdDateTime|DateTimeOffset|**TODO: Add Description**|
|defaultRedirectUri|String|**TODO: Add Description**|
|deletedDateTime|DateTimeOffset|**TODO: Add Description** Inherited from [directoryObject](../resources/directoryobject.md)|
|description|String|**TODO: Add Description**|
|displayName|String|**TODO: Add Description**|
|expectsForwardableIdTokens|Boolean|**TODO: Add Description**|
|groupMembershipClaims|String|**TODO: Add Description**|
|id|String|**TODO: Add Description** Inherited from [directoryObject](../resources/directoryobject.md)|
|identifierUris|String collection|**TODO: Add Description**|
|info|[informationalUrl](../resources/informationalurl.md)|**TODO: Add Description**|
|isDeviceOnlyAuthSupported|Boolean|**TODO: Add Description**|
|isFallbackPublicClient|Boolean|**TODO: Add Description**|
|keyCredentials|[keyCredential](../resources/keycredential.md) collection|**TODO: Add Description**|
|legacyAllowPassthroughUsers|Boolean|**TODO: Add Description**|
|logo|Stream|**TODO: Add Description**|
|microsoftPolicyGroup|Boolean|**TODO: Add Description**|
|notes|String|**TODO: Add Description**|
|optionalClaims|[optionalClaims](../resources/optionalclaims.md)|**TODO: Add Description**|
|parentalControlSettings|[parentalControlSettings](../resources/parentalcontrolsettings.md)|**TODO: Add Description**|
|passwordCredentials|[passwordCredential](../resources/passwordcredential.md) collection|**TODO: Add Description**|
|publicClient|[publicClientApplication](../resources/publicclientapplication.md)|**TODO: Add Description**|
|publisherDomain|String|**TODO: Add Description**|
|requiredResourceAccess|[requiredResourceAccess](../resources/requiredresourceaccess.md) collection|**TODO: Add Description**|
|servicePrincipalLifecyclePolicy|String|**TODO: Add Description**|
|signInAudience|String|**TODO: Add Description**|
|spa|[spaApplication](../resources/spaapplication.md)|**TODO: Add Description**|
|tags|String collection|**TODO: Add Description**|
|tokenEncryptionKeyId|Guid|**TODO: Add Description**|
|trustedSubjectNameAndIssuers|[trustedSubjectNameAndIssuer](../resources/trustedsubjectnameandissuer.md) collection|**TODO: Add Description**|
|uniqueName|String|**TODO: Add Description**|
|web|[webApplication](../resources/webapplication.md)|**TODO: Add Description**|

## Relationships
|Relationship|Type|Description|
|:---|:---|:---|
|createdOnBehalfOf|[directoryObject](../resources/directoryobject.md)|**TODO: Add Description**|
|extensionProperties|[extensionProperty](../resources/extensionproperty.md) collection|**TODO: Add Description**|
|homeRealmDiscoveryPolicies|[homeRealmDiscoveryPolicy](../resources/homerealmdiscoverypolicy.md) collection|**TODO: Add Description**|
|owners|[directoryObject](../resources/directoryobject.md) collection|**TODO: Add Description**|
|policies|[directoryObject](../resources/directoryobject.md) collection|**TODO: Add Description**|
|tokenIssuancePolicies|[tokenIssuancePolicy](../resources/tokenissuancepolicy.md) collection|**TODO: Add Description**|
|tokenLifetimePolicies|[tokenLifetimePolicy](../resources/tokenlifetimepolicy.md) collection|**TODO: Add Description**|

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.application",
  "baseType": "Microsoft.DirectoryServices.directoryObject",
  "openType": true
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.application",
  "id": "String (identifier)",
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
```

