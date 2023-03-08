---
description: "Automatically generated file. DO NOT MODIFY"
---

```go

//THE GO SDK IS IN PREVIEW. NON-PRODUCTION USE ONLY
graphClient := msgraphsdk.NewGraphServiceClient(requestAdapter)

requestBody := graphmodels.NewGroup()
additionalData := map[string]interface{}{
graphlearn_courses := graphmodels.New()
courseId := "123"
graphlearn_courses.SetCourseId(&courseId) 
courseName := "New Managers"
graphlearn_courses.SetCourseName(&courseName) 
courseType := "Online"
graphlearn_courses.SetCourseType(&courseType) 
	requestBody.SetGraphlearn_courses(graphlearn_courses)
}
requestBody.SetAdditionalData(additionalData)

result, err := graphClient.GroupsById("group-id").Patch(context.Background(), requestBody, nil)


```