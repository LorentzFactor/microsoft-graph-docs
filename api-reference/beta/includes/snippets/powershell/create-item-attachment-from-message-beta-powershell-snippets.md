---
description: "Automatically generated file. DO NOT MODIFY"
---

```powershell

Import-Module Microsoft.Graph.Mail

$params = @{
	"@odata.type" = "#microsoft.graph.itemAttachment"
	Name = "Holiday event"
	Item = @{
		"@odata.type" = "microsoft.graph.event"
		Subject = "Discuss gifts for children"
	}
}

New-MgUserMessageAttachment -UserId $userId -MessageId $messageId -BodyParameter $params

```