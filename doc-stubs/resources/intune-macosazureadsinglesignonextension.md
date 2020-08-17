---
title: "macOSAzureAdSingleSignOnExtension resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# macOSAzureAdSingleSignOnExtension resource type

Namespace: microsoft.graph

**TODO: Add Description**


Inherits from [macOSSingleSignOnExtension](../resources/macossinglesignonextension.md).

## Properties
|Property|Type|Description|
|:---|:---|:---|
|bundleIdAccessControlList|String collection|**TODO: Add Description**|
|configurations|[keyTypedValuePair](../resources/intune-keytypedvaluepair.md) collection|**TODO: Add Description**|
|enableSharedDeviceMode|Boolean|**TODO: Add Description**|

## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "@odata.type": "microsoft.graph.macOSAzureAdSingleSignOnExtension"
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.macOSAzureAdSingleSignOnExtension",
  "enableSharedDeviceMode": "Boolean",
  "bundleIdAccessControlList": [
    "String"
  ],
  "configurations": [
    {
      "@odata.type": "microsoft.graph.keyStringValuePair"
    }
  ]
}
```
