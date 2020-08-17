---
title: "Get windowsWifiEnterpriseEAPConfiguration"
description: "Read the properties and relationships of a windowsWifiEnterpriseEAPConfiguration object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Get windowsWifiEnterpriseEAPConfiguration
Namespace: microsoft.graph

Read the properties and relationships of a [windowsWifiEnterpriseEAPConfiguration](../resources/windowswifienterpriseeapconfiguration.md) object.

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
GET ** Entity URI for microsoft.graph.windowsWifiEnterpriseEAPConfiguration not found
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

If successful, this method returns a `200 OK` response code and a [windowsWifiEnterpriseEAPConfiguration](../resources/windowswifienterpriseeapconfiguration.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "get_windowswifienterpriseeapconfiguration"
}
-->
``` http
GET https://graph.microsoft.com/beta** Entity URI for microsoft.graph.windowsWifiEnterpriseEAPConfiguration not found
```


### Response
**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true,
  "@odata.type": "microsoft.graph.windowsWifiEnterpriseEAPConfiguration"
}
-->
``` http
HTTP/1.1 200 OK

Content-Type: application/json
{
  "value": {
    "@odata.type": "#microsoft.graph.windowsWifiEnterpriseEAPConfiguration",
    "id": "0f97ed73-ed73-0f97-73ed-970f73ed970f",
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
    "preSharedKey": "String",
    "wifiSecurityType": "String",
    "meteredConnectionLimit": "String",
    "ssid": "String",
    "networkName": "String",
    "connectAutomatically": "Boolean",
    "connectToPreferredNetwork": "Boolean",
    "connectWhenNetworkNameIsHidden": "Boolean",
    "proxySetting": "String",
    "proxyManualAddress": "String",
    "proxyManualPort": "Integer",
    "proxyAutomaticConfigurationUrl": "String",
    "forceFIPSCompliance": "Boolean",
    "networkSingleSignOn": "String",
    "maximumAuthenticationTimeoutInSeconds": "Integer",
    "promptForAdditionalAuthenticationCredentials": "Boolean",
    "enablePairwiseMasterKeyCaching": "Boolean",
    "maximumPairwiseMasterKeyCacheTimeInMinutes": "Integer",
    "maximumNumberOfPairwiseMasterKeysInCache": "Integer",
    "enablePreAuthentication": "Boolean",
    "maximumPreAuthenticationAttempts": "Integer",
    "eapType": "String",
    "trustedServerCertificateNames": [
      "String"
    ],
    "authenticationMethod": "String",
    "innerAuthenticationProtocolForEAPTTLS": "String",
    "outerIdentityPrivacyTemporaryValue": "String",
    "requireCryptographicBinding": "Boolean",
    "performServerValidation": "Boolean",
    "disableUserPromptForServerValidation": "Boolean"
  }
}
```
