# List SharePoint Sites

## Description
`list sharepoint sites` module executes reconnaissance to find all SharePoint sites in the tenant.

## Trigger
```
MAAD Attack Arsenal -> "SharePoint" -> 1
```

## MITRE ATT&CK Information

| Tactic         | Technique                                                                                                                                                                                                                                     |
| -------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Collection | [Data from Information Repositories: Sharepoint](https://attack.mitre.org/techniques/T1213/002/)|

## Additional Details
Microsoft services being accessed by this module:

* [SharePoint](https://www.microsoft.com/en-us/microsoft-365/sharepoint/collaboration)

External PowerShell module used: 

* [PnP.PowerShell](https://pnp.github.io/powershell/)