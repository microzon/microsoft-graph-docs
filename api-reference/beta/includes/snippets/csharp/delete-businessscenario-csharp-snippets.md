---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

await graphClient.Solutions.BusinessScenarios["{businessScenario-id}"]
	.Request()
	.DeleteAsync();

```