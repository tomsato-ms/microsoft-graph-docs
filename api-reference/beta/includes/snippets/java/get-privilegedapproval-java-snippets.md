---
description: "Automatically generated file. DO NOT MODIFY"
---

```java

IGraphServiceClient graphClient = GraphServiceClient.builder().authenticationProvider( authProvider ).buildClient();

PrivilegedApprovalCollectionPage privilegedApproval = graphClient.privilegedApproval()
	.buildRequest()
	.get();

```