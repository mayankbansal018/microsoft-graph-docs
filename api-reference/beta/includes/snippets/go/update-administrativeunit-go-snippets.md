---
description: "Automatically generated file. DO NOT MODIFY"
---

```go

//THE GO SDK IS IN PREVIEW. NON-PRODUCTION USE ONLY
graphClient := msgraphsdk.NewGraphServiceClient(requestAdapter)

requestBody := msgraphsdk.NewAdministrativeUnit()
displayName := "Greater Seattle District Technical Schools"
requestBody.SetDisplayName(&displayName)
options := &msgraphsdk.AdministrativeUnitRequestBuilderPatchOptions{
	Body: requestBody,
}
administrativeUnitId := "administrativeUnit-id"
result, err := graphClient.AdministrativeUnitsById(&administrativeUnitId).Patch(options)


```