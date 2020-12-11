---
title: "List cloudPcOnPremisesConnections"
description: "Get a list of the cloudPcOnPremisesConnection objects and their properties."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# List cloudPcOnPremisesConnections
Namespace: microsoft.graph

Get a list of the [cloudPcOnPremisesConnection](../resources/cloudpconpremisesconnection.md) objects and their properties.

## Permissions
One of the following permissions is required to call this API. To learn more, including how to choose permissions, see [Permissions](/graph/permissions-reference).

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
GET /deviceManagement/virtualEndpoint/onPremisesConnections
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

If successful, this method returns a `200 OK` response code and a collection of [cloudPcOnPremisesConnection](../resources/cloudpconpremisesconnection.md) objects in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "get_cloudpconpremisesconnection"
}
-->
``` http
GET https://graph.microsoft.com/beta/deviceManagement/virtualEndpoint/onPremisesConnections
```


### Response
**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true,
  "@odata.type": "Collection(microsoft.graph.cloudPcOnPremisesConnection)"
}
-->
``` http
HTTP/1.1 200 OK

Content-Type: application/json
{
  "value": [
    {
      "@odata.type": "#microsoft.graph.cloudPcOnPremisesConnection",
      "id": "23b58486-8486-23b5-8684-b5238684b523",
      "displayName": "String",
      "subscriptionId": "String",
      "subscriptionName": "String",
      "adDomainName": "String",
      "adDomainUsername": "String",
      "adDomainPassword": "String",
      "organizationalUnit": "String",
      "resourceGroupId": "String",
      "virtualNetworkId": "String",
      "subnetId": "String",
      "healthCheckStatus": "String",
      "healthCheckStatusDetails": {
        "@odata.type": "microsoft.graph.cloudPcOnPremisesConnectionStatusDetails"
      },
      "inUse": "Boolean"
    }
  ]
}
```

