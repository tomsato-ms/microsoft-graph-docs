---
title: "Get androidForWorkGeneralDeviceConfiguration"
description: "Read the properties and relationships of an androidForWorkGeneralDeviceConfiguration object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Get androidForWorkGeneralDeviceConfiguration
Namespace: microsoft.graph

Read the properties and relationships of an [androidForWorkGeneralDeviceConfiguration](../resources/androidforworkgeneraldeviceconfiguration.md) object.

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
GET ** Entity URI for microsoft.graph.androidForWorkGeneralDeviceConfiguration not found
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

If successful, this method returns a `200 OK` response code and an [androidForWorkGeneralDeviceConfiguration](../resources/androidforworkgeneraldeviceconfiguration.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "get_androidforworkgeneraldeviceconfiguration"
}
-->
``` http
GET https://graph.microsoft.com/beta** Entity URI for microsoft.graph.androidForWorkGeneralDeviceConfiguration not found
```


### Response
**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true,
  "@odata.type": "microsoft.graph.androidForWorkGeneralDeviceConfiguration"
}
-->
``` http
HTTP/1.1 200 OK

Content-Type: application/json
{
  "value": {
    "@odata.type": "#microsoft.graph.androidForWorkGeneralDeviceConfiguration",
    "id": "d7000914-0914-d700-1409-00d7140900d7",
    "lastModifiedDateTime": "String (timestamp)",
    "roleScopeTagIds": [
      "String"
    ],
    "supportsScopeTags": "Boolean",
    "deviceManagementApplicabilityRuleOsEdition": {
      "@odata.type": "microsoft.graph.deviceManagementApplicabilityRuleOsEdition"
    },
    "deviceManagementApplicabilityRuleOsVersion": {
      "@odata.type": "microsoft.graph.deviceManagementApplicabilityRuleOsVersion"
    },
    "deviceManagementApplicabilityRuleDeviceMode": {
      "@odata.type": "microsoft.graph.deviceManagementApplicabilityRuleDeviceMode"
    },
    "createdDateTime": "String (timestamp)",
    "description": "String",
    "displayName": "String",
    "version": "Integer",
    "passwordBlockFaceUnlock": "Boolean",
    "passwordBlockFingerprintUnlock": "Boolean",
    "passwordBlockIrisUnlock": "Boolean",
    "passwordBlockTrustAgents": "Boolean",
    "passwordExpirationDays": "Integer",
    "passwordMinimumLength": "Integer",
    "passwordMinutesOfInactivityBeforeScreenTimeout": "Integer",
    "passwordPreviousPasswordBlockCount": "Integer",
    "passwordSignInFailureCountBeforeFactoryReset": "Integer",
    "passwordRequiredType": "String",
    "workProfileDataSharingType": "String",
    "workProfileBlockNotificationsWhileDeviceLocked": "Boolean",
    "workProfileBlockAddingAccounts": "Boolean",
    "workProfileBluetoothEnableContactSharing": "Boolean",
    "workProfileBlockScreenCapture": "Boolean",
    "workProfileBlockCrossProfileCallerId": "Boolean",
    "workProfileBlockCamera": "Boolean",
    "workProfileBlockCrossProfileContactsSearch": "Boolean",
    "workProfileBlockCrossProfileCopyPaste": "Boolean",
    "workProfileDefaultAppPermissionPolicy": "String",
    "workProfilePasswordBlockFaceUnlock": "Boolean",
    "workProfilePasswordBlockFingerprintUnlock": "Boolean",
    "workProfilePasswordBlockIrisUnlock": "Boolean",
    "workProfilePasswordBlockTrustAgents": "Boolean",
    "workProfilePasswordExpirationDays": "Integer",
    "workProfilePasswordMinimumLength": "Integer",
    "workProfilePasswordMinNumericCharacters": "Integer",
    "workProfilePasswordMinNonLetterCharacters": "Integer",
    "workProfilePasswordMinLetterCharacters": "Integer",
    "workProfilePasswordMinLowerCaseCharacters": "Integer",
    "workProfilePasswordMinUpperCaseCharacters": "Integer",
    "workProfilePasswordMinSymbolCharacters": "Integer",
    "workProfilePasswordMinutesOfInactivityBeforeScreenTimeout": "Integer",
    "workProfilePasswordPreviousPasswordBlockCount": "Integer",
    "workProfilePasswordSignInFailureCountBeforeFactoryReset": "Integer",
    "workProfilePasswordRequiredType": "String",
    "workProfileRequirePassword": "Boolean",
    "securityRequireVerifyApps": "Boolean",
    "vpnAlwaysOnPackageIdentifier": "String",
    "vpnEnableAlwaysOnLockdownMode": "Boolean",
    "workProfileAllowWidgets": "Boolean",
    "workProfileBlockPersonalAppInstallsFromUnknownSources": "Boolean"
  }
}
```
