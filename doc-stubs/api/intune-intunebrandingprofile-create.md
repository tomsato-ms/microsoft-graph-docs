---
title: "Create intuneBrandingProfile"
description: "Create a new intuneBrandingProfile object."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Create intuneBrandingProfile
Namespace: microsoft.graph

Create a new [intuneBrandingProfile](../resources/intune-intunebrandingprofile.md) object.

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
POST /deviceManagement/intuneBrandingProfiles
```

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|
|Content-Type|application/json. Required.|

## Request body
In the request body, supply a JSON representation of the [intuneBrandingProfile](../resources/intune-intunebrandingprofile.md) object.

The following table shows the properties that are required when you create the [intuneBrandingProfile](../resources/intune-intunebrandingprofile.md).

|Property|Type|Description|
|:---|:---|:---|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/entity.md)|
|profileName|String|**TODO: Add Description**|
|profileDescription|String|**TODO: Add Description**|
|isDefaultProfile|Boolean|**TODO: Add Description**|
|createdDateTime|DateTimeOffset|**TODO: Add Description**|
|lastModifiedDateTime|DateTimeOffset|**TODO: Add Description**|
|displayName|String|**TODO: Add Description**|
|themeColor|[rgbColor](../resources/intune-rgbcolor.md)|**TODO: Add Description**|
|showLogo|Boolean|**TODO: Add Description**|
|showDisplayNameNextToLogo|Boolean|**TODO: Add Description**|
|themeColorLogo|[mimeContent](../resources/intune-mimecontent.md)|**TODO: Add Description**|
|lightBackgroundLogo|[mimeContent](../resources/intune-mimecontent.md)|**TODO: Add Description**|
|landingPageCustomizedImage|[mimeContent](../resources/intune-mimecontent.md)|**TODO: Add Description**|
|contactITName|String|**TODO: Add Description**|
|contactITPhoneNumber|String|**TODO: Add Description**|
|contactITEmailAddress|String|**TODO: Add Description**|
|contactITNotes|String|**TODO: Add Description**|
|onlineSupportSiteUrl|String|**TODO: Add Description**|
|onlineSupportSiteName|String|**TODO: Add Description**|
|privacyUrl|String|**TODO: Add Description**|
|customPrivacyMessage|String|**TODO: Add Description**|
|customCanSeePrivacyMessage|String|**TODO: Add Description**|
|customCantSeePrivacyMessage|String|**TODO: Add Description**|
|isRemoveDeviceDisabled|Boolean|**TODO: Add Description**|
|isFactoryResetDisabled|Boolean|**TODO: Add Description**|
|companyPortalBlockedActions|[companyPortalBlockedAction](../resources/intune-companyportalblockedaction.md) collection|**TODO: Add Description**|
|showAzureADEnterpriseApps|Boolean|**TODO: Add Description**|
|showOfficeWebApps|Boolean|**TODO: Add Description**|
|sendDeviceOwnershipChangePushNotification|Boolean|**TODO: Add Description**|
|enrollmentAvailability|enrollmentAvailabilityOptions|**TODO: Add Description**. Possible values are: `availableWithPrompts`, `availableWithoutPrompts`, `unavailable`.|
|roleScopeTagIds|String collection|**TODO: Add Description**|



## Response

If successful, this method returns a `201 Created` response code and an [intuneBrandingProfile](../resources/intune-intunebrandingprofile.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "create_intunebrandingprofile_from_"
}
-->
``` http
POST https://graph.microsoft.com/beta/deviceManagement/intuneBrandingProfiles
Content-Type: application/json
Content-length: 1368

{
  "@odata.type": "#microsoft.graph.intuneBrandingProfile",
  "profileName": "String",
  "profileDescription": "String",
  "isDefaultProfile": "Boolean",
  "displayName": "String",
  "themeColor": {
    "@odata.type": "microsoft.graph.rgbColor"
  },
  "showLogo": "Boolean",
  "showDisplayNameNextToLogo": "Boolean",
  "themeColorLogo": {
    "@odata.type": "microsoft.graph.mimeContent"
  },
  "lightBackgroundLogo": {
    "@odata.type": "microsoft.graph.mimeContent"
  },
  "landingPageCustomizedImage": {
    "@odata.type": "microsoft.graph.mimeContent"
  },
  "contactITName": "String",
  "contactITPhoneNumber": "String",
  "contactITEmailAddress": "String",
  "contactITNotes": "String",
  "onlineSupportSiteUrl": "String",
  "onlineSupportSiteName": "String",
  "privacyUrl": "String",
  "customPrivacyMessage": "String",
  "customCanSeePrivacyMessage": "String",
  "customCantSeePrivacyMessage": "String",
  "isRemoveDeviceDisabled": "Boolean",
  "isFactoryResetDisabled": "Boolean",
  "companyPortalBlockedActions": [
    {
      "@odata.type": "microsoft.graph.companyPortalBlockedAction"
    }
  ],
  "showAzureADEnterpriseApps": "Boolean",
  "showOfficeWebApps": "Boolean",
  "sendDeviceOwnershipChangePushNotification": "Boolean",
  "enrollmentAvailability": "String",
  "roleScopeTagIds": [
    "String"
  ]
}
```


### Response
**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true,
  "@odata.type": "microsoft.graph.intuneBrandingProfile"
}
-->
``` http
HTTP/1.1 201 Created

Content-Type: application/json
{
  "@odata.type": "#microsoft.graph.intuneBrandingProfile",
  "id": "a9213116-3116-a921-1631-21a9163121a9",
  "profileName": "String",
  "profileDescription": "String",
  "isDefaultProfile": "Boolean",
  "createdDateTime": "String (timestamp)",
  "lastModifiedDateTime": "String (timestamp)",
  "displayName": "String",
  "themeColor": {
    "@odata.type": "microsoft.graph.rgbColor"
  },
  "showLogo": "Boolean",
  "showDisplayNameNextToLogo": "Boolean",
  "themeColorLogo": {
    "@odata.type": "microsoft.graph.mimeContent"
  },
  "lightBackgroundLogo": {
    "@odata.type": "microsoft.graph.mimeContent"
  },
  "landingPageCustomizedImage": {
    "@odata.type": "microsoft.graph.mimeContent"
  },
  "contactITName": "String",
  "contactITPhoneNumber": "String",
  "contactITEmailAddress": "String",
  "contactITNotes": "String",
  "onlineSupportSiteUrl": "String",
  "onlineSupportSiteName": "String",
  "privacyUrl": "String",
  "customPrivacyMessage": "String",
  "customCanSeePrivacyMessage": "String",
  "customCantSeePrivacyMessage": "String",
  "isRemoveDeviceDisabled": "Boolean",
  "isFactoryResetDisabled": "Boolean",
  "companyPortalBlockedActions": [
    {
      "@odata.type": "microsoft.graph.companyPortalBlockedAction"
    }
  ],
  "showAzureADEnterpriseApps": "Boolean",
  "showOfficeWebApps": "Boolean",
  "sendDeviceOwnershipChangePushNotification": "Boolean",
  "enrollmentAvailability": "String",
  "roleScopeTagIds": [
    "String"
  ]
}
```
