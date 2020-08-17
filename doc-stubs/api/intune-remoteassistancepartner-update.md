---
title: "Update remoteAssistancePartner"
description: "Update the properties of a remoteAssistancePartner object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Update remoteAssistancePartner
Namespace: microsoft.graph

Update the properties of a [remoteAssistancePartner](../resources/intune-remoteassistancepartner.md) object.

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
PATCH /deviceManagement/remoteAssistancePartners/{remoteAssistancePartnerId}
```

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|
|Content-Type|application/json. Required.|

## Request body
In the request body, supply a JSON representation of the [remoteAssistancePartner](../resources/intune-remoteassistancepartner.md) object.

The following table shows the properties that are required when you create the [remoteAssistancePartner](../resources/intune-remoteassistancepartner.md).

|Property|Type|Description|
|:---|:---|:---|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/entity.md)|
|displayName|String|**TODO: Add Description**|
|onboardingUrl|String|**TODO: Add Description**|
|onboardingStatus|remoteAssistanceOnboardingStatus|**TODO: Add Description**. Possible values are: `notOnboarded`, `onboarding`, `onboarded`.|
|lastConnectionDateTime|DateTimeOffset|**TODO: Add Description**|
|onboardingRequestExpiryDateTime|DateTimeOffset|**TODO: Add Description**|



## Response

If successful, this method returns a `200 OK` response code and an updated [remoteAssistancePartner](../resources/intune-remoteassistancepartner.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "update_remoteassistancepartner"
}
-->
``` http
PATCH https://graph.microsoft.com/beta/deviceManagement/remoteAssistancePartners/{remoteAssistancePartnerId}
Content-Type: application/json
Content-length: 267

{
  "@odata.type": "#microsoft.graph.remoteAssistancePartner",
  "displayName": "String",
  "onboardingUrl": "String",
  "onboardingStatus": "String",
  "lastConnectionDateTime": "String (timestamp)",
  "onboardingRequestExpiryDateTime": "String (timestamp)"
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
  "@odata.type": "#microsoft.graph.remoteAssistancePartner",
  "id": "41411f67-1f67-4141-671f-4141671f4141",
  "displayName": "String",
  "onboardingUrl": "String",
  "onboardingStatus": "String",
  "lastConnectionDateTime": "String (timestamp)",
  "onboardingRequestExpiryDateTime": "String (timestamp)"
}
```
