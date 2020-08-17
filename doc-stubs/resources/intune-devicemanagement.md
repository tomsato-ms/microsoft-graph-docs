---
title: "deviceManagement resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# deviceManagement resource type

Namespace: microsoft.graph

**TODO: Add Description**


Inherits from [entity](../resources/entity.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List deviceManagements](../api/intune-devicemanagement-list.md)|[deviceManagement](../resources/intune-devicemanagement.md) collection|Get a list of the [deviceManagement](../resources/devicemanagement.md) objects and their properties.|
|[Create deviceManagement](../api/intune-devicemanagement-create.md)|[deviceManagement](../resources/intune-devicemanagement.md)|Create a new [deviceManagement](../resources/intune-devicemanagement.md) object.|
|[Get deviceManagement](../api/intune-devicemanagement-get.md)|[deviceManagement](../resources/intune-devicemanagement.md)|Read the properties and relationships of a [deviceManagement](../resources/intune-devicemanagement.md) object.|
|[Update deviceManagement](../api/intune-devicemanagement-update.md)|[deviceManagement](../resources/intune-devicemanagement.md)|Update the properties of a [deviceManagement](../resources/intune-devicemanagement.md) object.|
|[Delete deviceManagement](../api/intune-devicemanagement-delete.md)|None|Deletes a [deviceManagement](../resources/intune-devicemanagement.md) object.|
|[List userExperienceAnalyticsAppHealthApplicationPerformance](../api/intune-devicemanagement-list-userexperienceanalyticsapphealthapplicationperformance.md)|[userExperienceAnalyticsAppHealthApplicationPerformance](../resources/intune-userexperienceanalyticsapphealthapplicationperformance.md) collection|Get the userExperienceAnalyticsAppHealthApplicationPerformances from the userExperienceAnalyticsAppHealthApplicationPerformance navigation property.|
|[Create userExperienceAnalyticsAppHealthApplicationPerformance](../api/intune-devicemanagement-post-userexperienceanalyticsapphealthapplicationperformance.md)|[userExperienceAnalyticsAppHealthApplicationPerformance](../resources/intune-userexperienceanalyticsapphealthapplicationperformance.md)|Create a new userExperienceAnalyticsAppHealthApplicationPerformance object.|
|[Get userExperienceAnalyticsAppHealthApplicationPerformance](../api/intune-devicemanagement-get-userexperienceanalyticsapphealthapplicationperformance.md)|[userExperienceAnalyticsAppHealthApplicationPerformance](../resources/intune-userexperienceanalyticsapphealthapplicationperformance.md)|Read the properties and relationships of a [userExperienceAnalyticsAppHealthApplicationPerformance](../resources/intune-userexperienceanalyticsapphealthapplicationperformance.md) object.|
|[Update userExperienceAnalyticsAppHealthApplicationPerformance](../api/intune-devicemanagement-update-userexperienceanalyticsapphealthapplicationperformance.md)|[userExperienceAnalyticsAppHealthApplicationPerformance](../resources/intune-userexperienceanalyticsapphealthapplicationperformance.md)|Update the properties of a userExperienceAnalyticsAppHealthApplicationPerformance object.|
|[Delete userExperienceAnalyticsAppHealthApplicationPerformance](../api/intune-devicemanagement-delete-userexperienceanalyticsapphealthapplicationperformance.md)|None|Delete a [userExperienceAnalyticsAppHealthApplicationPerformance](../resources/intune-userexperienceanalyticsapphealthapplicationperformance.md) object.|
|[List userExperienceAnalyticsMetricHistory](../api/intune-devicemanagement-list-userexperienceanalyticsmetrichistory.md)|[userExperienceAnalyticsMetricHistory](../resources/intune-userexperienceanalyticsmetrichistory.md) collection|Get the userExperienceAnalyticsMetricHistories from the userExperienceAnalyticsMetricHistory navigation property.|
|[Create userExperienceAnalyticsMetricHistory](../api/intune-devicemanagement-post-userexperienceanalyticsmetrichistory.md)|[userExperienceAnalyticsMetricHistory](../resources/intune-userexperienceanalyticsmetrichistory.md)|Create a new userExperienceAnalyticsMetricHistory object.|
|[Get userExperienceAnalyticsMetricHistory](../api/intune-devicemanagement-get-userexperienceanalyticsmetrichistory.md)|[userExperienceAnalyticsMetricHistory](../resources/intune-userexperienceanalyticsmetrichistory.md)|Read the properties and relationships of a [userExperienceAnalyticsMetricHistory](../resources/intune-userexperienceanalyticsmetrichistory.md) object.|
|[Update userExperienceAnalyticsMetricHistory](../api/intune-devicemanagement-update-userexperienceanalyticsmetrichistory.md)|[userExperienceAnalyticsMetricHistory](../resources/intune-userexperienceanalyticsmetrichistory.md)|Update the properties of a userExperienceAnalyticsMetricHistory object.|
|[Delete userExperienceAnalyticsMetricHistory](../api/intune-devicemanagement-delete-userexperienceanalyticsmetrichistory.md)|None|Delete a [userExperienceAnalyticsMetricHistory](../resources/intune-userexperienceanalyticsmetrichistory.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|accountMoveCompletionDateTime|DateTimeOffset|**TODO: Add Description**|
|adminConsent|[adminConsent](../resources/intune-adminconsent.md)|**TODO: Add Description**|
|deviceComplianceReportSummarizationDateTime|DateTimeOffset|**TODO: Add Description**|
|deviceProtectionOverview|[deviceProtectionOverview](../resources/intune-deviceprotectionoverview.md)|**TODO: Add Description**|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/entity.md)|
|intuneAccountId|Guid|**TODO: Add Description**|
|intuneBrand|[intuneBrand](../resources/intune-intunebrand.md)|**TODO: Add Description**|
|lastReportAggregationDateTime|DateTimeOffset|**TODO: Add Description**|
|legacyPcManangementEnabled|Boolean|**TODO: Add Description**|
|managedDeviceCleanupSettings|[managedDeviceCleanupSettings](../resources/intune-manageddevicecleanupsettings.md)|**TODO: Add Description**|
|maximumDepTokens|Int32|**TODO: Add Description**|
|settings|[deviceManagementSettings](../resources/intune-devicemanagementsettings.md)|**TODO: Add Description**|
|subscriptions|deviceManagementSubscriptions|**TODO: Add Description**. Possible values are: `none`, `intune`, `office365`, `intunePremium`, `intune_EDU`, `intune_SMB`.|
|subscriptionState|deviceManagementSubscriptionState|**TODO: Add Description**. Possible values are: `pending`, `active`, `warning`, `disabled`, `deleted`, `blocked`, `lockedOut`.|
|unlicensedAdminstratorsEnabled|Boolean|**TODO: Add Description**|
|userExperienceAnalyticsSettings|[userExperienceAnalyticsSettings](../resources/intune-userexperienceanalyticssettings.md)|**TODO: Add Description**|
|windowsMalwareOverview|[windowsMalwareOverview](../resources/intune-windowsmalwareoverview.md)|**TODO: Add Description**|

## Relationships
|Relationship|Type|Description|
|:---|:---|:---|
|advancedThreatProtectionOnboardingStateSummary|[advancedThreatProtectionOnboardingStateSummary](../resources/intune-advancedthreatprotectiononboardingstatesummary.md)|**TODO: Add Description**|
|androidDeviceOwnerEnrollmentProfiles|[androidDeviceOwnerEnrollmentProfile](../resources/intune-androiddeviceownerenrollmentprofile.md) collection|**TODO: Add Description**|
|androidForWorkAppConfigurationSchemas|[androidForWorkAppConfigurationSchema](../resources/intune-androidforworkappconfigurationschema.md) collection|**TODO: Add Description**|
|androidForWorkEnrollmentProfiles|[androidForWorkEnrollmentProfile](../resources/intune-androidforworkenrollmentprofile.md) collection|**TODO: Add Description**|
|androidForWorkSettings|[androidForWorkSettings](../resources/intune-androidforworksettings.md)|**TODO: Add Description**|
|androidManagedStoreAccountEnterpriseSettings|[androidManagedStoreAccountEnterpriseSettings](../resources/intune-androidmanagedstoreaccountenterprisesettings.md)|**TODO: Add Description**|
|androidManagedStoreAppConfigurationSchemas|[androidManagedStoreAppConfigurationSchema](../resources/intune-androidmanagedstoreappconfigurationschema.md) collection|**TODO: Add Description**|
|applePushNotificationCertificate|[applePushNotificationCertificate](../resources/intune-applepushnotificationcertificate.md)|**TODO: Add Description**|
|appleUserInitiatedEnrollmentProfiles|[appleUserInitiatedEnrollmentProfile](../resources/intune-appleuserinitiatedenrollmentprofile.md) collection|**TODO: Add Description**|
|assignmentFilters|[deviceAndAppManagementAssignmentFilter](../resources/intune-deviceandappmanagementassignmentfilter.md) collection|**TODO: Add Description**|
|auditEvents|[auditEvent](../resources/intune-auditevent.md) collection|**TODO: Add Description**|
|autopilotEvents|[deviceManagementAutopilotEvent](../resources/intune-devicemanagementautopilotevent.md) collection|**TODO: Add Description**|
|cartToClassAssociations|[cartToClassAssociation](../resources/intune-carttoclassassociation.md) collection|**TODO: Add Description**|
|categories|[deviceManagementSettingCategory](../resources/intune-devicemanagementsettingcategory.md) collection|**TODO: Add Description**|
|comanagedDevices|[managedDevice](../resources/intune-manageddevice.md) collection|**TODO: Add Description**|
|comanagementEligibleDevices|[comanagementEligibleDevice](../resources/intune-comanagementeligibledevice.md) collection|**TODO: Add Description**|
|complianceManagementPartners|[complianceManagementPartner](../resources/intune-compliancemanagementpartner.md) collection|**TODO: Add Description**|
|conditionalAccessSettings|[onPremisesConditionalAccessSettings](../resources/intune-onpremisesconditionalaccesssettings.md)|**TODO: Add Description**|
|dataSharingConsents|[dataSharingConsent](../resources/intune-datasharingconsent.md) collection|**TODO: Add Description**|
|depOnboardingSettings|[depOnboardingSetting](../resources/intune-deponboardingsetting.md) collection|**TODO: Add Description**|
|derivedCredentials|[deviceManagementDerivedCredentialSettings](../resources/intune-devicemanagementderivedcredentialsettings.md) collection|**TODO: Add Description**|
|detectedApps|[detectedApp](../resources/intune-detectedapp.md) collection|**TODO: Add Description**|
|deviceCategories|[deviceCategory](../resources/intune-devicecategory.md) collection|**TODO: Add Description**|
|deviceCompliancePolicies|[deviceCompliancePolicy](../resources/intune-devicecompliancepolicy.md) collection|**TODO: Add Description**|
|deviceCompliancePolicyDeviceStateSummary|[deviceCompliancePolicyDeviceStateSummary](../resources/intune-devicecompliancepolicydevicestatesummary.md)|**TODO: Add Description**|
|deviceCompliancePolicySettingStateSummaries|[deviceCompliancePolicySettingStateSummary](../resources/intune-devicecompliancepolicysettingstatesummary.md) collection|**TODO: Add Description**|
|deviceComplianceScripts|[deviceComplianceScript](../resources/intune-devicecompliancescript.md) collection|**TODO: Add Description**|
|deviceConfigurationConflictSummary|[deviceConfigurationConflictSummary](../resources/intune-deviceconfigurationconflictsummary.md) collection|**TODO: Add Description**|
|deviceConfigurationDeviceStateSummaries|[deviceConfigurationDeviceStateSummary](../resources/intune-deviceconfigurationdevicestatesummary.md)|**TODO: Add Description**|
|deviceConfigurationRestrictedAppsViolations|[restrictedAppsViolation](../resources/intune-restrictedappsviolation.md) collection|**TODO: Add Description**|
|deviceConfigurations|[deviceConfiguration](../resources/intune-deviceconfiguration.md) collection|**TODO: Add Description**|
|deviceConfigurationsAllManagedDeviceCertificateStates|[managedAllDeviceCertificateState](../resources/intune-managedalldevicecertificatestate.md) collection|**TODO: Add Description**|
|deviceConfigurationUserStateSummaries|[deviceConfigurationUserStateSummary](../resources/intune-deviceconfigurationuserstatesummary.md)|**TODO: Add Description**|
|deviceEnrollmentConfigurations|[deviceEnrollmentConfiguration](../resources/intune-deviceenrollmentconfiguration.md) collection|**TODO: Add Description**|
|deviceHealthScripts|[deviceHealthScript](../resources/intune-devicehealthscript.md) collection|**TODO: Add Description**|
|deviceManagementPartners|[deviceManagementPartner](../resources/intune-devicemanagementpartner.md) collection|**TODO: Add Description**|
|deviceManagementScripts|[deviceManagementScript](../resources/intune-devicemanagementscript.md) collection|**TODO: Add Description**|
|deviceShellScripts|[deviceShellScript](../resources/intune-deviceshellscript.md) collection|**TODO: Add Description**|
|domainJoinConnectors|[deviceManagementDomainJoinConnector](../resources/intune-devicemanagementdomainjoinconnector.md) collection|**TODO: Add Description**|
|embeddedSIMActivationCodePools|[embeddedSIMActivationCodePool](../resources/intune-embeddedsimactivationcodepool.md) collection|**TODO: Add Description**|
|exchangeConnectors|[deviceManagementExchangeConnector](../resources/intune-devicemanagementexchangeconnector.md) collection|**TODO: Add Description**|
|exchangeOnPremisesPolicies|[deviceManagementExchangeOnPremisesPolicy](../resources/intune-devicemanagementexchangeonpremisespolicy.md) collection|**TODO: Add Description**|
|exchangeOnPremisesPolicy|[deviceManagementExchangeOnPremisesPolicy](../resources/intune-devicemanagementexchangeonpremisespolicy.md)|**TODO: Add Description**|
|groupPolicyCategories|[groupPolicyCategory](../resources/intune-grouppolicycategory.md) collection|**TODO: Add Description**|
|groupPolicyConfigurations|[groupPolicyConfiguration](../resources/intune-grouppolicyconfiguration.md) collection|**TODO: Add Description**|
|groupPolicyDefinitionFiles|[groupPolicyDefinitionFile](../resources/intune-grouppolicydefinitionfile.md) collection|**TODO: Add Description**|
|groupPolicyDefinitions|[groupPolicyDefinition](../resources/intune-grouppolicydefinition.md) collection|**TODO: Add Description**|
|groupPolicyMigrationReports|[groupPolicyMigrationReport](../resources/intune-grouppolicymigrationreport.md) collection|**TODO: Add Description**|
|groupPolicyObjectFiles|[groupPolicyObjectFile](../resources/intune-grouppolicyobjectfile.md) collection|**TODO: Add Description**|
|groupPolicyUploadedDefinitionFiles|[groupPolicyUploadedDefinitionFile](../resources/intune-grouppolicyuploadeddefinitionfile.md) collection|**TODO: Add Description**|
|importedDeviceIdentities|[importedDeviceIdentity](../resources/intune-importeddeviceidentity.md) collection|**TODO: Add Description**|
|importedWindowsAutopilotDeviceIdentities|[importedWindowsAutopilotDeviceIdentity](../resources/intune-importedwindowsautopilotdeviceidentity.md) collection|**TODO: Add Description**|
|intents|[deviceManagementIntent](../resources/intune-devicemanagementintent.md) collection|**TODO: Add Description**|
|intuneBrandingProfiles|[intuneBrandingProfile](../resources/intune-intunebrandingprofile.md) collection|**TODO: Add Description**|
|iosUpdateStatuses|[iosUpdateDeviceStatus](../resources/intune-iosupdatedevicestatus.md) collection|**TODO: Add Description**|
|managedDeviceEncryptionStates|[managedDeviceEncryptionState](../resources/intune-manageddeviceencryptionstate.md) collection|**TODO: Add Description**|
|managedDeviceOverview|[managedDeviceOverview](../resources/intune-manageddeviceoverview.md)|**TODO: Add Description**|
|managedDevices|[managedDevice](../resources/intune-manageddevice.md) collection|**TODO: Add Description**|
|managementConditions|[managementCondition](../resources/intune-managementcondition.md) collection|**TODO: Add Description**|
|managementConditionStatements|[managementConditionStatement](../resources/intune-managementconditionstatement.md) collection|**TODO: Add Description**|
|mobileAppTroubleshootingEvents|[mobileAppTroubleshootingEvent](../resources/intune-mobileapptroubleshootingevent.md) collection|**TODO: Add Description**|
|mobileThreatDefenseConnectors|[mobileThreatDefenseConnector](../resources/intune-mobilethreatdefenseconnector.md) collection|**TODO: Add Description**|
|ndesConnectors|[ndesConnector](../resources/intune-ndesconnector.md) collection|**TODO: Add Description**|
|notificationMessageTemplates|[notificationMessageTemplate](../resources/intune-notificationmessagetemplate.md) collection|**TODO: Add Description**|
|remoteActionAudits|[remoteActionAudit](../resources/intune-remoteactionaudit.md) collection|**TODO: Add Description**|
|remoteAssistancePartners|[remoteAssistancePartner](../resources/intune-remoteassistancepartner.md) collection|**TODO: Add Description**|
|reports|[deviceManagementReports](../resources/intune-devicemanagementreports.md)|**TODO: Add Description**|
|resourceOperations|[resourceOperation](../resources/intune-resourceoperation.md) collection|**TODO: Add Description**|
|roleAssignments|[deviceAndAppManagementRoleAssignment](../resources/deviceandappmanagementroleassignment.md) collection|**TODO: Add Description**|
|roleDefinitions|[roleDefinition](../resources/intune-roledefinition.md) collection|**TODO: Add Description**|
|roleScopeTags|[roleScopeTag](../resources/intune-rolescopetag.md) collection|**TODO: Add Description**|
|settingDefinitions|[deviceManagementSettingDefinition](../resources/intune-devicemanagementsettingdefinition.md) collection|**TODO: Add Description**|
|softwareUpdateStatusSummary|[softwareUpdateStatusSummary](../resources/intune-softwareupdatestatussummary.md)|**TODO: Add Description**|
|telecomExpenseManagementPartners|[telecomExpenseManagementPartner](../resources/intune-telecomexpensemanagementpartner.md) collection|**TODO: Add Description**|
|templates|[deviceManagementTemplate](../resources/intune-devicemanagementtemplate.md) collection|**TODO: Add Description**|
|termsAndConditions|[termsAndConditions](../resources/intune-termsandconditions.md) collection|**TODO: Add Description**|
|troubleshootingEvents|[deviceManagementTroubleshootingEvent](../resources/intune-devicemanagementtroubleshootingevent.md) collection|**TODO: Add Description**|
|userExperienceAnalyticsAppHealthApplicationPerformance|[userExperienceAnalyticsAppHealthApplicationPerformance](../resources/intune-userexperienceanalyticsapphealthapplicationperformance.md) collection|**TODO: Add Description**|
|userExperienceAnalyticsBaselines|[userExperienceAnalyticsBaseline](../resources/intune-userexperienceanalyticsbaseline.md) collection|**TODO: Add Description**|
|userExperienceAnalyticsCategories|[userExperienceAnalyticsCategory](../resources/intune-userexperienceanalyticscategory.md) collection|**TODO: Add Description**|
|userExperienceAnalyticsDevicePerformance|[userExperienceAnalyticsDevicePerformance](../resources/intune-userexperienceanalyticsdeviceperformance.md) collection|**TODO: Add Description**|
|userExperienceAnalyticsDeviceStartupHistory|[userExperienceAnalyticsDeviceStartupHistory](../resources/intune-userexperienceanalyticsdevicestartuphistory.md) collection|**TODO: Add Description**|
|userExperienceAnalyticsDeviceStartupProcesses|[userExperienceAnalyticsDeviceStartupProcess](../resources/intune-userexperienceanalyticsdevicestartupprocess.md) collection|**TODO: Add Description**|
|userExperienceAnalyticsDeviceStartupProcessPerformance|[userExperienceAnalyticsDeviceStartupProcessPerformance](../resources/intune-userexperienceanalyticsdevicestartupprocessperformance.md) collection|**TODO: Add Description**|
|userExperienceAnalyticsMetricHistory|[userExperienceAnalyticsMetricHistory](../resources/intune-userexperienceanalyticsmetrichistory.md) collection|**TODO: Add Description**|
|userExperienceAnalyticsOverview|[userExperienceAnalyticsOverview](../resources/intune-userexperienceanalyticsoverview.md)|**TODO: Add Description**|
|userExperienceAnalyticsRegressionSummary|[userExperienceAnalyticsRegressionSummary](../resources/intune-userexperienceanalyticsregressionsummary.md)|**TODO: Add Description**|
|userExperienceAnalyticsScoreHistory|[userExperienceAnalyticsScoreHistory](../resources/intune-userexperienceanalyticsscorehistory.md) collection|**TODO: Add Description**|
|userPfxCertificates|[userPFXCertificate](../resources/intune-userpfxcertificate.md) collection|**TODO: Add Description**|
|windowsAutopilotDeploymentProfiles|[windowsAutopilotDeploymentProfile](../resources/intune-windowsautopilotdeploymentprofile.md) collection|**TODO: Add Description**|
|windowsAutopilotDeviceIdentities|[windowsAutopilotDeviceIdentity](../resources/intune-windowsautopilotdeviceidentity.md) collection|**TODO: Add Description**|
|windowsAutopilotSettings|[windowsAutopilotSettings](../resources/intune-windowsautopilotsettings.md)|**TODO: Add Description**|
|windowsFeatureUpdateProfiles|[windowsFeatureUpdateProfile](../resources/intune-windowsfeatureupdateprofile.md) collection|**TODO: Add Description**|
|windowsInformationProtectionAppLearningSummaries|[windowsInformationProtectionAppLearningSummary](../resources/intune-windowsinformationprotectionapplearningsummary.md) collection|**TODO: Add Description**|
|windowsInformationProtectionNetworkLearningSummaries|[windowsInformationProtectionNetworkLearningSummary](../resources/intune-windowsinformationprotectionnetworklearningsummary.md) collection|**TODO: Add Description**|
|windowsMalwareInformation|[windowsMalwareInformation](../resources/intune-windowsmalwareinformation.md) collection|**TODO: Add Description**|

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.deviceManagement",
  "baseType": "microsoft.graph.entity",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.deviceManagement",
  "id": "String (identifier)",
  "settings": {
    "@odata.type": "microsoft.graph.deviceManagementSettings"
  },
  "maximumDepTokens": "Integer",
  "intuneAccountId": "Guid",
  "lastReportAggregationDateTime": "String (timestamp)",
  "deviceComplianceReportSummarizationDateTime": "String (timestamp)",
  "legacyPcManangementEnabled": "Boolean",
  "unlicensedAdminstratorsEnabled": "Boolean",
  "intuneBrand": {
    "@odata.type": "microsoft.graph.intuneBrand"
  },
  "subscriptionState": "String",
  "subscriptions": "String",
  "managedDeviceCleanupSettings": {
    "@odata.type": "microsoft.graph.managedDeviceCleanupSettings"
  },
  "adminConsent": {
    "@odata.type": "microsoft.graph.adminConsent"
  },
  "deviceProtectionOverview": {
    "@odata.type": "microsoft.graph.deviceProtectionOverview"
  },
  "windowsMalwareOverview": {
    "@odata.type": "microsoft.graph.windowsMalwareOverview"
  },
  "accountMoveCompletionDateTime": "String (timestamp)",
  "userExperienceAnalyticsSettings": {
    "@odata.type": "microsoft.graph.userExperienceAnalyticsSettings"
  }
}
```
