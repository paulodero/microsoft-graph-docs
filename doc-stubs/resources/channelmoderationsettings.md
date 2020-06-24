---
title: "channelModerationSettings resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# channelModerationSettings resource type

Namespace: microsoft.graph

**TODO: Add Description**

## Properties
|Property|Type|Description|
|:---|:---|:---|
|allowNewMessageFromBots|Boolean|**TODO: Add Description**|
|allowNewMessageFromConnectors|Boolean|**TODO: Add Description**|
|replyRestriction|replyRestriction|**TODO: Add Description**. Possible values are: `everyone`, `authorAndModerators`, `unknownFutureValue`.|
|userNewMessageRestriction|userNewMessageRestriction|**TODO: Add Description**. Possible values are: `everyone`, `everyoneExceptGuests`, `moderators`, `unknownFutureValue`.|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "@odata.type": "microsoft.graph.channelModerationSettings"
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.channelModerationSettings",
  "userNewMessageRestriction": "String",
  "replyRestriction": "String",
  "allowNewMessageFromBots": "Boolean",
  "allowNewMessageFromConnectors": "Boolean"
}
```

