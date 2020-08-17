---
title: "Update vppToken"
description: "Update the properties of a vppToken object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Update vppToken
Namespace: microsoft.graph

Update the properties of a [vppToken](../resources/intune-vpptoken.md) object.

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
PATCH /deviceAppManagement/vppTokens/{vppTokenId}
```

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|
|Content-Type|application/json. Required.|

## Request body
In the request body, supply a JSON representation of the [vppToken](../resources/intune-vpptoken.md) object.

The following table shows the properties that are required when you create the [vppToken](../resources/intune-vpptoken.md).

|Property|Type|Description|
|:---|:---|:---|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/entity.md)|
|organizationName|String|**TODO: Add Description**|
|vppTokenAccountType|vppTokenAccountType|**TODO: Add Description**. Possible values are: `business`, `education`.|
|appleId|String|**TODO: Add Description**|
|expirationDateTime|DateTimeOffset|**TODO: Add Description**|
|lastSyncDateTime|DateTimeOffset|**TODO: Add Description**|
|token|String|**TODO: Add Description**|
|lastModifiedDateTime|DateTimeOffset|**TODO: Add Description**|
|state|vppTokenState|**TODO: Add Description**. Possible values are: `unknown`, `valid`, `expired`, `invalid`, `assignedToExternalMDM`, `duplicateLocationId`.|
|tokenActionResults|[vppTokenActionResult](../resources/intune-vpptokenactionresult.md) collection|**TODO: Add Description**|
|lastSyncStatus|vppTokenSyncStatus|**TODO: Add Description**. Possible values are: `none`, `inProgress`, `completed`, `failed`.|
|automaticallyUpdateApps|Boolean|**TODO: Add Description**|
|countryOrRegion|String|**TODO: Add Description**|
|dataSharingConsentGranted|Boolean|**TODO: Add Description**|
|displayName|String|**TODO: Add Description**|
|locationName|String|**TODO: Add Description**|
|claimTokenManagementFromExternalMdm|Boolean|**TODO: Add Description**|
|roleScopeTagIds|String collection|**TODO: Add Description**|



## Response

If successful, this method returns a `200 OK` response code and an updated [vppToken](../resources/intune-vpptoken.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "update_vpptoken"
}
-->
``` http
PATCH https://graph.microsoft.com/beta/deviceAppManagement/vppTokens/{vppTokenId}
Content-Type: application/json
Content-length: 688

{
  "@odata.type": "#microsoft.graph.vppToken",
  "organizationName": "String",
  "vppTokenAccountType": "String",
  "appleId": "String",
  "expirationDateTime": "String (timestamp)",
  "lastSyncDateTime": "String (timestamp)",
  "token": "String",
  "state": "String",
  "tokenActionResults": [
    {
      "@odata.type": "microsoft.graph.vppTokenActionResult"
    }
  ],
  "lastSyncStatus": "String",
  "automaticallyUpdateApps": "Boolean",
  "countryOrRegion": "String",
  "dataSharingConsentGranted": "Boolean",
  "displayName": "String",
  "locationName": "String",
  "claimTokenManagementFromExternalMdm": "Boolean",
  "roleScopeTagIds": [
    "String"
  ]
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
  "@odata.type": "#microsoft.graph.vppToken",
  "id": "3154a7da-a7da-3154-daa7-5431daa75431",
  "organizationName": "String",
  "vppTokenAccountType": "String",
  "appleId": "String",
  "expirationDateTime": "String (timestamp)",
  "lastSyncDateTime": "String (timestamp)",
  "token": "String",
  "lastModifiedDateTime": "String (timestamp)",
  "state": "String",
  "tokenActionResults": [
    {
      "@odata.type": "microsoft.graph.vppTokenActionResult"
    }
  ],
  "lastSyncStatus": "String",
  "automaticallyUpdateApps": "Boolean",
  "countryOrRegion": "String",
  "dataSharingConsentGranted": "Boolean",
  "displayName": "String",
  "locationName": "String",
  "claimTokenManagementFromExternalMdm": "Boolean",
  "roleScopeTagIds": [
    "String"
  ]
}
```
