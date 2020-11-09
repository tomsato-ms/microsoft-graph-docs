---
description: "Automatically generated file. DO NOT MODIFY"
---

```java

IGraphServiceClient graphClient = GraphServiceClient.builder().authenticationProvider( authProvider ).buildClient();

DriveItemSearchCollectionPage search = graphClient.me().drive().root()
	.search("Contoso Project")
	.buildRequest()
	.get();

```