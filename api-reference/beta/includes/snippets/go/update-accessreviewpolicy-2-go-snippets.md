---
description: "Automatically generated file. DO NOT MODIFY"
---

```go

//THE GO SDK IS IN PREVIEW. NON-PRODUCTION USE ONLY
graphClient := msgraphsdk.NewGraphServiceClient(requestAdapter)

requestBody := msgraphsdk.NewAccessReviewPolicy()
isGroupOwnerManagementEnabled := true
requestBody.SetIsGroupOwnerManagementEnabled(&isGroupOwnerManagementEnabled)
options := &msgraphsdk.PolicyRequestBuilderPatchOptions{
	Body: requestBody,
}
result, err := graphClient.IdentityGovernance().AccessReviews().Policy().Patch(options)


```