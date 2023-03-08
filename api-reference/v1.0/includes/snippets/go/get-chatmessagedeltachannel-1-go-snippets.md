---
description: "Automatically generated file. DO NOT MODIFY"
---

```go

//THE GO SDK IS IN PREVIEW. NON-PRODUCTION USE ONLY
graphClient := msgraphsdk.NewGraphServiceClient(requestAdapter)


requestTop := int32(2)

requestParameters := &graphconfig.TeamItemChannelItemMessagesDelta()RequestBuilderGetQueryParameters{
	Top: &requestTop,
}
configuration := &graphconfig.TeamItemChannelItemMessagesDelta()RequestBuilderGetRequestConfiguration{
	QueryParameters: requestParameters,
}

result, err := graphClient.TeamsById("team-id").ChannelsById("channel-id").Messages().Delta().Get(context.Background(), configuration)


```