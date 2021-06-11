---
title: "channelDescriptionUpdatedEventMessageDetail resource type"
description: "Represents details for channel description updated event message"
author: "harshnat"
localization_priority: Normal
ms.prod: "microsoft-teams"
doc_type: resourcePageType
---

# channelDescriptionUpdatedEventMessageDetail resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

Represents details for channel description updated event message.

This message is generated when channel's description is updated.


Inherits from [eventMessageDetail](../resources/eventmessagedetail.md).

## Properties
|Property|Type|Description|
|:---|:---|:---|
|channelDescription|String|Updated description of the channel.|
|channelId|String|Unique identifier of the channel.|
|initiator|[identitySet](../resources/identityset.md)|Initiator of the event.|

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "@odata.type": "microsoft.graph.channelDescriptionUpdatedEventMessageDetail"
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.channelDescriptionUpdatedEventMessageDetail",
  "channelId": "String",
  "channelDescription": "String",
  "initiator": {
    "@odata.type": "microsoft.graph.identitySet"
  }
}
```
