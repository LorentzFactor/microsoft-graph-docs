---
description: "Automatically generated file. DO NOT MODIFY"
---

```powershell

Import-Module Microsoft.Graph.PersonalContacts

$params = @{
	GivenName = "Pavel"
	Surname = "Bansky"
	EmailAddresses = @(
		@{
			Address = "pavelb@contoso.onmicrosoft.com"
			Name = "Pavel Bansky"
			Type = "personal"
		}
		@{
			Address = "pavelb@fabrikam.onmicrosoft.com"
			Name = "Pavel Bansky"
			Type = "other"
			OtherLabel = "Volunteer work"
		}
	)
	Phones = @(
		@{
			Number = "+1 732 555 0102"
			Type = "business"
		}
	)
}

New-MgUserContact -UserId $userId -BodyParameter $params

```