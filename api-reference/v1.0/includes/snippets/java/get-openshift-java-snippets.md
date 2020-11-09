---
description: "Automatically generated file. DO NOT MODIFY"
---

```java

IGraphServiceClient graphClient = GraphServiceClient.builder().authenticationProvider( authProvider ).buildClient();

OpenShiftCollectionPage openShifts = graphClient.teams("{id}").schedule().openShifts()
	.buildRequest()
	.get();

```