---
description: "Automatically generated file. DO NOT MODIFY"
---

```go

//THE GO SDK IS IN PREVIEW. NON-PRODUCTION USE ONLY
graphClient := msgraphsdk.NewGraphServiceClient(requestAdapter)

requestBody := graphmodels.NewTeamsAppSettings()
allowUserRequestsForAppAccess := true
requestBody.SetAllowUserRequestsForAppAccess(&allowUserRequestsForAppAccess) 

result, err := graphClient.Teamwork().TeamsAppSettings().Patch(context.Background(), requestBody, nil)


```